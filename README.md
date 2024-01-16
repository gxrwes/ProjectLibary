# ProjectLibary
A libary of all projects and last releases
## WAVE
### WAVE-CLI
wave can be called with properties so it can be executed with other jobs
these are the launchoptions:
- "-nomenu"  : disables the menue loading, add this if you want to autorun
- "-csvpath" : follow this with the path to a job csv, look at the JOBLIST chapter
- "-nogpu"  : disables Nvidia GPU support for Handbreak, encoding will be done on CPU
- "-info"   : prints info when running
- "-moreinfo"   : prints more info when running
 currently supported handbreak presets
#### Framerate Options:
- Fast 720p30: --preset="Fast 720p30"
- Very Fast 720p30: --preset="Very Fast 720p30"
- HQ 1080p30 Surround: --preset="HQ 1080p30 Surround"
- Super HQ 1080p30 Surround: --preset="Super HQ 1080p30 Surround"
- Fast 1080p30: --preset="Fast 1080p30"
- Very Fast 1080p30: --preset="Very Fast 1080p30"
- Ultra HQ 2K30 Surround: --preset="Ultra HQ 2K30 Surround"
- Ultra HQ 4K30 Surround: --preset="Ultra HQ 4K30 Surround"
- Fast 4K30: --preset="Fast 4K30"
- Very Fast 4K30: --preset="Very Fast 4K30"
- Fast 720p60: --preset="Fast 720p60"
- Very Fast 720p60: --preset="Very Fast 720p60"
- Fast 1080p60: --preset="Fast 1080p60"
- Very Fast 1080p60: --preset="Very Fast 1080p60"
- Ultra HQ 2K60 Surround: --preset="Ultra HQ 2K60 Surround"
- Ultra HQ 4K60 Surround: --preset="Ultra HQ 4K60 Surround"
- Fast 4K60: --preset="Fast 4K60"
- Very Fast 4K60: --preset="Very Fast 4K60"

#### High-Quality Options:
- High Quality 720p30: --preset="High Quality 720p30"
- High Quality 1080p30 Surround: --preset="High Quality 1080p30 Surround"
- High Quality 2K30 Surround: --preset="High Quality 2K30 Surround"
- High Quality 4K30 Surround: --preset="High Quality 4K30 Surround"
- High Quality 720p60: --preset="High Quality 720p60"
- High Quality 1080p60: --preset="High Quality 1080p60"
- High Quality 2K60 Surround: --preset="High Quality 2K60 Surround"
- High Quality 4K60 Surround: --preset="High Quality 4K60 Surround"

