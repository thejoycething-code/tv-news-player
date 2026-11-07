# TV news player

A tiny page that plays a YouTube channel's current live stream, muted, for Chris's Samsung TV launcher.
YouTube won't play inside an installed TV app, so the launcher shows this page in its news window instead.

- Sky News: `index.html?channel=UCoMdktPbSTixAyNGwb-UYkQ`
- GB News: `index.html?channel=UC0vn8ISa4LKMunLbzaXLnOQ`

The launcher sends `{type:"launcher", cmd:"mute"|"unmute"}` messages and receives `{type:"player", state:"playing"|"error"}`.
