# brave-browser-builds

These are not official builds. This repo is just for testing, do not use!



<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>


...but if your going to ignore us and do it anyways here's some info that might be helpfull




### Windows

Both of these are packages are signed with the following windows code signing cert.

SHA256: 97:06:28:F7:8B:25:49:3D:AB:9C:CD:40:DE:93:9C:19:3C:BA:69:5B:92:2B:C2:03:F8:F2:C4:C6:B8:99:FB:61
SHA1:   D8:FB:5F:D2:EC:50:48:77:74:26:E0:6E:40:E9:A0:7D:2A:31:A9:58
MD5:    45:04:40:07:D7:FE:86:99:18:BA:8A:97:97:49:F0:54

#### BraveBrowserDevSetup.exe
A minimal download that bootstraps the latest available windows build, and will update automatically when new builds are available.

#### brave_installer-x64.exe
Stand alone installer for windows which has updates disabled by default since it depends on functionality in BraveBrowserDevSetup.exe (If you need to ensure updates are disabled in all cases, you'll want to pass the --disable_brave_extension flag to the Brave binary).


### Darwin

Currently signed with the following Apple Developer cert:

SHA256: 18:54:C0:85:BE:23:EA:8C:EF:FC:44:38:83:6C:91:0B:25:AC:9B:49:04:5E:5C:9C:FD:BF:04:7E:35:2A:FD:0E
SHA1: 39:2F:0B:A6:5B:34:8B:1F:A2:FA:02:8A:A1:17:52:A0:1B:84:81:A5
MD5: F:A6:54:0A:B4:A3:5A:C9:3A:95:4D:80:5C:59:BB:B7

#### Brave-Browser-Dev.dmg
This is the standalone installer and will enable updates in the background (not always obvious this is working currently but try navigating to chrome://chrome and giving it some time to download in the background).


### Linux
  Packages here are not currently signed, will update this section shortly.
  

  
 
