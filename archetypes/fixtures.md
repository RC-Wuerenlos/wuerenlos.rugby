---
title: '{{ replace .File.ContentBaseName `-` ` ` | title }}'
date: '{{ .Date }}'
draft: false

kickoff: '{{ .Date }}'
seasons: [""]
venues: [""]
leagues: ""
homescore: 0
guestscore: 0
teams:
  - name: "wuerenlos-men"
    home: false
    players:
      - player: "player-name"
        position: "scrumhalf"
  - name: "team-name"
    home: true
---
