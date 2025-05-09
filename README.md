# -=[ Hidden Things Of Freelancer Game ]=-

```ini
Content.dll 0x0A84A1 74 > EB He||oween Do not read locked_gate under [mPlayer] section of .fl file
```
```ini
Freelancer.exe 0x13C0AA 83 F8 10 > 83 F8 FF He||oween Break Limit of Comm Inbox (Act_EtherComm) pt.1
Freelancer.exe 0x13C183 83 F8 10 > 83 F8 FF He||oween Break Limit of Comm Inbox (Act_EtherComm) pt.2
```

# -=[ Ini Keys ]=-
```ini
[FactionProps]
assassinate_target = <target> ;; Not checked
...
```
```ini
[Archetype]
;; It is preload section (like precache in Sourcegames)
;; For SP preloads all
;; For MP preloads only simple for explosions
...
```
```ini
[Trigger]
Act_ChangeState = SUCCEED, SILENT ;; Do not show MISSION SUCCESS but show only FIND A JOB
```
# -=[ CRASH offsets and reasons ]=-
```ini
common.dll    9143    BC46    Specified loadout for [MsnSolar] or [KillableSolar] is not defined in loadouts.ini.
```


