# -=[ Hidden Things Of Freelancer Game ]=-
```ini
Server.dll 06CD85 508B->EB40 = disable anticheat measures ~adoxa
```
```ini
Content.dll 0x0A84A1 74->EB = Do not read locked_gate under [mPlayer] section of .fl file ~He||oween
```
```ini
Freelancer.exe 0x13C0AA 83F810->83F8FF = Break Limit of Comm Inbox (Act_EtherComm) pt.1 ~He||oween
Freelancer.exe 0x13C183 83F810->83F8FF = Break Limit of Comm Inbox (Act_EtherComm) pt.2 ~He||oween
```

# -=[ Ini Keys ]=-
```ini
[FactionProps]
assassinate_target = <target> ;; Not checked
...
```
```ini
[Archetype]
;; It is preload section of sys.ini(ex. li01.ini) like precache in Sourcegames
;; For server-side preloads only simple keys for explosions
simple = <simple> ;; nickname key value from [Simple] section of shiparch.ini
;; For client-side preloads all
;; Additional keys
voice = <voice> ;; nickname key value from voices_*.ini (ex. voices_space_female.ini)
asteroid = <asteroid> ;; nickname key value from asteroidarch.ini
...
```
```ini
[Trigger]
Act_ChangeState = SUCCEED, SILENT ;; Do not show MISSION SUCCESS but show only FIND A JOB
...
```
```ini
[AnySection]
inherit = <object> ;; takes properties of <object>, if key is absent - SinglePlayer() is called
```
```ini
[EncounterFormation]
ship_by_npc_arch = 1, 1, Liberty_Battleship ;; Cheapest encounter variant (don't do in production)
pilot = battleship_default

[Creation]
permutation = 0, 3
```
```ini
[CollisionConsts]
;; In constants.ini
damage = <damage>
max_impact_speed = <speed>
```
# -=[ CRASH offsets and reasons ]=-
```ini
common.dll 9143 BC46 Specified loadout for [MsnSolar] or [KillableSolar] absent in loadouts.ini.
```


