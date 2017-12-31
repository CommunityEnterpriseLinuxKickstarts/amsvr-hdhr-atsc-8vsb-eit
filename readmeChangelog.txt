*Bugs are tracked in sf "tickets". 
*Please check to see if a problem(bug) is already being worked on at SF(tickets) before you submit a new request.

r70 known bugs/todo:
- liveconfig is messy and needs much migrated to rpms. 
- after a install, other newly created accounts need system wide icewm menu's and startup options, test with skel options.


r69 Dec-31-2017
- updated the script: createNewAutoMythSvrHdHrEitImage.sh, with --tmpdir set to /tmp/TMPDIR
  For now, Make sure you have enough space in /tmp before running or modify script to where you do have space.
- moved the path "/myth/music/musicArt" to /myth/musicArt ,updated automythserver-filesystem rpm
- fixed storage group default configuration which caused recordings to go to /myth instead of /myth/recordings,
  updated automythserver-eit-stages rpm
r68 
- Added Changelog.txt to liveimage
r67
- Added kernel-lt to rpms list.
r66
- Initial Public Release
