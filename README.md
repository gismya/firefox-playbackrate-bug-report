# firefox-playbackrate-bug-report

Bug report for a playbackrate bug in Firefox.

When a video file without sound is connected to createMediaElementSource, the playbackrate is no longer applied and fixed at 1x. The `playbackRate` property is reporting the correct value, but the video is not playing at the correct speed.
