# Default configuration file for James' BanManagement Plugin
localDatabase:
  host: localhost
  port: 3306
  database: banmanagement
  username: root
  password: ''
  bansTable: mb_bans
  bansRecordTable: mb_ban_records
  ipBansTable: mb_ip_bans
  ipBansRecordTable: mb_ip_records
  kicksTable: mb_kicks
  mutesTable: mb_mutes
  mutesRecordTable: mb_mutes_records
  playerIpsTable: mb_player_ips
  warningsTable: mb_warnings
  banAppealsTable: mb_ban1_appeals
  pinsTable: mb_pins
  staffTable: mb_staff
useUTF8: false
logIPs: true
serverName: ''
checkForUpdates: true
logKicks: false
cleanUp:
  kicks: 30
  banRecords: 0
  ipBanRecords: 0
  muteRecords: 0
  playerIPs: 30
  warnings: 0
scheduler:
  expiresCheck: 300
  bukkitUnban: 3
  newMutes: 8
  newBans: 8
  newIPBans: 8
mutedCommandBlacklist:
- msg
useSyncChat: false
timeLimits:
  mutes:
    Moderator: 1h
  bans:
    Moderator: 1d
use-partial-names: true
bukkit-ban: true
messages:
  ban: '&f[&aBanManager&f] &c[by]&f has banned the player &c[name] &f for &c[reason]'
  banKick: You have been banned for [reason]
  tempBan: '&f[&aBanManager&f] &c[by] &f has temporarily banned the player &c[name]
    &f for &9[expires] &f for &c[reason]'
  tempBanKick: You have been temporarily banned for [reason]
  ipBan: '&f[&aBanManager&f] &c[by] &f has banned the IP &c[ip] &f for &c[reason]'
  ipTempBan: '&4[by] has temporarily banned [ip] for [reason] which expires in [expires]'
  ipBanKick: Your IP has been banned for [reason]
  kicked: '&4[by] has kicked [name] for [reason]'
  kickedNo: '[name] has been kicked by [by]'
  kickReason: You have been kicked for [reason]
  kickNoReason: You have been kicked
  disconnectBan: You have been banned from this server for [reason]
  disconnectTempBan: 'Your ban expires in [expires] Reason: [reason]'
  disconnectIpBan: Your IP has been banned from this server for [reason]
  disconnectTempIpBan: 'Your ban expires in [expires] Reason: [reason]'
  mute: '&f[&aBanManager&f] &c[by] &f muted the player &c[name] &f for &c[reason]'
  muted: You have been permanently muted for [reason] by [by]
  tempMute: '&f[&aBanManager&f] &c[by] &f temporarily muted the player &c[name]&f
    for &9[expires] &f for &c[reason]'
  tempMuted: You have been temporarily muted for [reason] by [by] which expires in [expires]
  commandPermissionError: '&cYou do not have permission to use this command'
  banSelfError: '&cYou can''t ban yourself fool!'
  banExemptError: '&cYou do not have permission to ban this player'
  alreadyBannedError: '&c[name] is already banned'
  playerBanned: '[name] has been banned'
  multiplePlayersFoundError: '&cmultiple players found, please be more specific'
  importInProgressError: '&cAn import is already in progress'
  beginingPlayerImport: '&6Beginning banned player import'
  scanningDatabase: '&6'
  scanPlayersFound: '&6Players found: [found]'
  noPlayersImport: '&cNo players need importing, yay less work for me!'
  percentagePlayersImported: '&6[percent]% of players imported'
  playerImportComplete: '&6Player import complete!'
  beginingIpImport: '&6Beginning banned ip import'
  scanIpsFound: '&6Players found: [found]'
  noIpsImport: '&cNo IPs need importing, yay less work for me!'
  percentageIPsImported: '&6[percent]% of IPs imported'
  ipImportComplete: '&6IP import complete!'
  bmInfo: '&cName: &6[name]\n&cCurrent Ban: [currentBan]\n&cPrevious Bans: [previousBans]\n&cCurrent
    Mute: [currentMute]\n&cPrevious Mutes: [previousMutes]\n&cWarnings: [warningsCount]'
  ipBanned: '[ip] has been banned'
  ipTempBanned: '[ip] has been banned temporarily'
  ipSelfError: '&cYou can''t ip ban yourself fool!'
  ipPlayerOfflineError: '&c[name] is offline, unable to retrieve IP'
  ipTempBanKick: You have been temporarily banned for [reason]
  kickSelfError: '&cYou can''t kick yourself fool!'
  kickExemptError: '&cYou do not have permission to kick this player'
  playerKicked: '[name] has been kicked'
  playerNotOnline: '&cPlayer not found, are they online?'
  muteSelfError: '&cYou can''t mute yourself fool!'
  muteExemptError: '&cYou do not have permission to mute this player'
  alreadyMutedError: '&c[name] is already muted'
  playerMuted: '[name] has been muted'
  illegalDateError: '&cIllegal Date Format'
  playerTempBanned: '[name] has been temporarily banned'
  playerTempMuted: '[name] has been temporarily muted'
  unbanError: '&cYou can''t unban someone who isn''t banned!'
  playerUnbanned: '&6[by] unbanned [name]'
  ipUnbanned: '&6[by] unbanned ip [ip]'
  ipNotBannedError: '&c[ip] is not currently banned. You can''t unban someone who
    isn''t banned!'
  invalidIp: '&cInvalid IP!'
  invalidPlayer: '&cInvalid Player!'
  playerUnmuted: '[name] has been unmuted'
  playerNotMutedError: '&cYou can''t unmute someone who isn''t muted!'
  updateAvailable: '&A[version] update available'
  banTimeLimitError: '&cYou cannot ban for that length of time'
  muteTimeLimitError: '&cYou cannot mute for that length of time'
  warnSelfError: '&cYou can''t warn yourself fool!'
  warnExemptError: '&cYou do not have permission to warn this player'
  playerWarned: '[name] has been warned'
  warned: '&cYou have been warned by [by] for the following:\n[reason]'
  duplicateIP: '&cWarning: [player] has the same IP as the following banned players:\n&6[players]'
  consoleName: Console
  timeNow: now
  timeYear: year
  timeYears: years
  timeMonth: month
  timeMonths: months
  timeDay: day
  timeDays: days
  timeHour: hour
  timeHours: hours
  timeMinute: minute
  timeMinutes: minutes
  timeSecond: second
  timeSeconds: seconds 
