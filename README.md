# edr-issues

This is the place where you will find known bugs and planned features for the [EDR](https://edr.deadlykungfu.ninja/)

Ici sont repertoriés tous les bugs et tous les suggestions qui vont etre implementées dans l'[EDR](https://edr.deadlykungfu.ninja/)

# Changelog

### 0.7

#### Features
- Search multiple trains (separated by a comma , ) https://github.com/DKFN/edr-issues/issues/26
- The steam avatar and player name is displayed. Steam was implemented on the backend. https://github.com/DKFN/edr-issues/issues/33
- HU language is now available ! -no issue-
- Some railway symbols that are not normalized across countries are now localized https://github.com/DKFN/edr-issues/issues/43
- Server name is now displayed -no issue-

#### Fixes

- MASSIVE performance gain. The UI was becoming laggy. Thread code (web workers) was optimized, React optimizations were implemented. RAM usage will be higher but CPU usage was divided by 7. -internal issue-
- 24hrs format as the norm, as it seems to be the norm in the industry https://github.com/DKFN/edr-issues/issues/50
- Correctly format hour https://github.com/DKFN/edr-issues/issues/44

### 0.6

#### Features

- Long calculations are offloaded in a background thread using WebWorkers -internal issue-
- Server timezone is now taken into account. All game servers are now open ! https://github.com/DKFN/edr-issues/issues/39 
- Station name is now displayed https://github.com/DKFN/edr-issues/issues/37
- Posts images are now optimized https://github.com/DKFN/edr-issues/issues/36

#### Fixes
- Some clients have a slower refresh rate of 1mn instead of 5-10s https://github.com/DKFN/edr-issues/issues/31
- Servers are ordered depending on locale choices https://github.com/DKFN/edr-issues/issues/28


### 0.5

Actually two releases merged into one

#### Features

- Multiple posts trains are now merged in one row (Sosnowiec) https://github.com/DKFN/edr-issues/issues/10
- Header is now sticky on the page ! https://github.com/DKFN/edr-issues/issues/29
- Add station name [#37](https://github.com/DKFN/edr-issues/issues/37)
- Better color palette for more accessibility https://github.com/DKFN/edr-issues/issues/21


#### Fixes
- Auto refresh does not filter Offline trains in Online mode https://github.com/DKFN/edr-issues/issues/30 & https://github.com/DKFN/edr-issues/issues/15
- Departure time is not taken into account when calculating delay https://github.com/DKFN/edr-issues/issues/24
- Fix icons for MPE/MOJ/ROJ type https://github.com/DKFN/edr-issues/issues/22
- Unable to play at Gora https://github.com/DKFN/edr-issues/issues/35
- Small memory leak https://github.com/DKFN/edr-issues/issues/32
- Select screen background https://github.com/DKFN/edr-issues/issues/17

#### Backend
- NGINX reverse proxies add a layer of cache
- CDN bypass for train queries because of some network problems (cached by NGINX)

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
