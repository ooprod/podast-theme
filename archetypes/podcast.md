+++
episodeType = "full" # "full", "trailer" or "bonus"
episode = "" # required for full episodes
season = "" # required for full episodes
title = "{{ replace .Name "-" " " | title }}"
explicit = "no"
audio = "" # full URL to podcast audio
audioSize = 0 # make a HTTP HEAD request to audio URL and check a Content-Length header
audioType = "audio/mpeg"
audioDuration = 0 # in seconds
date = {{ .Date }}
video = "" #id only
tags = []
draft = true
+++

Initial description of this episode.

<!--more-->

Other information about the episode