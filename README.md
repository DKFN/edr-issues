# edr-issues

This is the place where you will find known bugs and planned features for the [EDR](https://edr.deadlykungfu.ninja/)

Ici sont repertoriés tous les bugs et tous les suggestions qui vont etre implementées dans l'[EDR](https://edr.deadlykungfu.ninja/)

# Changelog
### 0.4

##### :czech_republic: :czech_republic: Welcome Czech Republic friends :partying_face: :czech_republic: :czech_republic:

_CZ1_ server is now available on the server list.
Documentation is now moving towards being mostly english


#### Features
- More precise detection a train passing the station (thanks IWhite!) https://github.com/DKFN/edr-issues/issues/18
- Nearest station of train displayed (thanks IWhite!) https://github.com/DKFN/edr-issues/issues/18
- Nearest station displayed https://github.com/DKFN/edr-issues/issues/18
- Current speed of train displayed -no issue-
- Line number is tied to destination, not in its own column -no issue-

#### Fixes
- Filter jumpy behavior when changing options https://github.com/DKFN/edr-issues/issues/13
- On-Line trains are never refreshed https://github.com/DKFN/edr-issues/issues/15
- UI is less wierd (but still a bit, we are in closed alpha :grin: ) -no issue-

#### Servers
- CDN configuration changed to reduce RPS to backend
- Backend now runs alpine to reduce node first invocation time
- Reduced backend memory per node from 1GB to 512Mb
- SimRail server crash will now serve stale cache data
- :motorcycle: > 30.000 request served on the first 6hrs of the test without issues, thanks all !

-------

### 0.3
- Fix Mettre des couleurs de labels au train en fonction du type (FRET, HLP, PASSAGER) https://github.com/DKFN/edr-issues/issues/6
- Fix Les filtres ne fonctionnent pas sur Sosnowiec https://github.com/DKFN/edr-issues/issues/4 
- Fix Diverses corrections du darkmode https://github.com/DKFN/edr-issues/issues/3
- Fix Corriger l'icone de la TRAXX https://github.com/DKFN/edr-issues/issues/1

### 0.2
- Release beta fermée
