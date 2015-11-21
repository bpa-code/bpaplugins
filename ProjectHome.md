A repository of Plugins for SqueezeCenter created or maintained by bps. The plugins are only suitable for SqueezeCenter 7.3 or higher.  This repository was created so that the plugins may be downloaded and installed using the Extension Downloader.

The url to be used as the repository with Extension downloader: http://bpaplugins.googlecode.com/svn/trunk/repo.xml

**AACplus**

A Plugin Settings to enable playing AACplus stream types using mplayer. Discussion on AACplus on SC7 are mainly in this thread http://forums.slimdevices.com/showthread.php?t=41403 .  The wiki entry http://wiki.slimdevices.com/index.php/AACplus deals with older versions of AACplus.
v1.0 support SC7.0-7.2
v1.1 support SC 7.3-

**CDplayer**

A Plugin to enable an audio CD in the PC CD drive to be played through SqueezeCenter. Requires CDDA2WAV to be installed.

The main discussion thread in the forum is
http://forums.slimdevices.com/showthread.php?t=47288

V1.06 - Fix a Ubuntu problem when no CD in drive.

**NPRRadio**

NPR Plugin to make it easy to find and play popular NPR prgrams. A plugin also makes it easier to listen to complete NPR Radio. Each program menu (e.g. Morning Edition, All things considered etc.) will list the program sgements which can be played separately. For each program, there is a "play all items" which will create a playlist of all the segments in the program.

The main discussion thread in the forum is http://forums.slimdevices.com/showthread.php?t=51002

**FindArt**

FindArt plugins provides easy way for user to locate and download cover art from Amazon. All processing is within SqueezeCenter plugin.  It is not a bulk coverart application.

Main change in v2.04 has Squeezeplay support (i.e. Controller & Desktop) and "Find cover art" menu off all Track info web pages no longer limited to use with just playing track.

The main discussion and support thread in the forum is http://forums.slimdevices.com/showthread.php?t=49245


V1.0
  * Initial Release
V1.01
  * Bug fix
  * Artist can be added to Search request
Ver 2.04
  * Find Cover Art menu off Track Info page while browsing library - no longer limited to use only on playing track.
  * Find Art now works on Controller from Track Info displays.
  * Search related Find Art settings can be changed from Settings menu on Controller.
  * Find Art menu position on Track Info page is configurable (top,bottom,auto)
  * A preference setting to display a Custom Search facility on WebUI where user can change the search terms.  If Artist search is enabled then two fields will be shown but if Artist field can be left blank for a Title/Keyword search.
  * New artwork will show up on WebUI and controller/Squeezeplay without need for rescan.  On WebUI there may be a need to refresh pages/ clear browser cache. There is still some caching in Squeezeplay which can't be invalidated and prevents updated art being displayed immediately.  On Squeezeplay the new art work will not show up on menu that have already been "seen" until SC has been restarted.
  * fix for bug when search Title has accented characters.

**SharkPlay**

PR Plugin to make it easy to find and play popular NPR prgrams. A plugin also makes it easier to listen to complete NPR Radio. Each program menu (e.g. Morning Edition, All things considered etc.) will list the program segments which can be played separately. For each program, there is a "play all items" which will create a playlist of all the segments in the program.

The main discussion thread http://forums.slimdevices.com/showthread.php?t=54926.

V1.0  Initial release support for 7.0-7.2
V1.01 has supported for 7.3 onward.

Ubuntu installation should note the comments in the support thread about enabling the shark2 application (i.e. "chuser root shark2" and  "chmod +s shark2")  and the userid which runs squeezecenter (typically squeezecenter) should be a member of  Ubuntu "audio" group.

**TunerPlay**

A Windows only plugin to enable a Analog TV/FM Tuner cards to be tuned and play FM stations through SC.  Require VLC ( http://www.videolan.org/vlc/download-windows.html )  to be installed.

**WaveInput**

A Plugin to enable PC audio to be captured and played through SqueezeCenter.
There are version of Windows and Linux. In the Linux version the default setup uses ALSA but OSS also works.

Main discussion thread for Windows version http://forums.slimdevices.com/showthread.php?t=35718

Main discussion thread for Linux version http://forums.slimdevices.com/showthread.php?t=49584

**InfoBrowserClassicFMtracks**

InfoBrowser Addon to display the frecently played lists for Classic FM station.

**InfoBrowserSomaTracks**

InfoBrowser Addon to display the frecently played lists for Soma FM stations.