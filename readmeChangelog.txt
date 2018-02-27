*Bugs are tracked in sf "tickets". 
*Please check to see if a problem(bug) is already being worked on at SF(tickets) before you submit a new request.



r7X known bugs/todo:
- liveconfig is messy and needs much migrated to rpms. 
- after a install, other newly created accounts need system wide icewm menu's and startup options, test with skel options.


r72 Feb-22-2018
- Renamed project to be more specific to its current intent and less generic.
- Sync with upstream SL repo ,upgraded to kernel-3.10.0-693.17.1, systemd-219-42
- Sync with upstream elrepo kernel repo , upgraded to kernel-lt-4.4.116-1

r71 Jan-18-2018
- Sync with upstream sl repo:
	- Red Hat Security Advisory updates for microcode,firmware,java
	- Advisory URLs: 
	- https://access.redhat.com/errata/RHSA-2018:0093
	- https://access.redhat.com/errata/RHSA-2018:0094
	- https://access.redhat.com/errata/RHSA-2018:0095

r70 Jan-07-2018
- Sync with upstream repos to update kernel/kernel-lt for vulnerabilities: Meltdown & Spectre
- kernel-lt-4.4.110-1
- kernel-3.10.0-693.11.6
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
