# Git - Docker mod for sabnzbd

This mod adds git to sabnzbd, to be installed/updated during container start.

In sabnzbd docker arguments, set an environment variable `DOCKER_MODS=linuxserver/mods:sabnzbd-git`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:sabnzbd-git|linuxserver/mods:sabnzbd-mod2`
