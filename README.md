# gc-audio-edge-zh

Stand-in read-aloud audio for https://shanchuan.org/middle (on-demand clips, zh), recorded from the site's spoken scripts with a Microsoft Edge voice. The site plays a Serena recording first when one exists.

Layout: `<lang>/<key>.mp3`, and `<subject>/<topic>/manifest.js` = `LabAudioManifest({lesson: 'edge:<subject>/<topic>', voice, <lang>: '<key> ...'})`.
