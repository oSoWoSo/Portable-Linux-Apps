
 OpenShot is a cross-platform video editor, with support for Linux, Mac
 and Windows. This is the official x86_64 AppImage of the project.
 
 KNOWN ISSUE: the desktop integration prompt is enabled by default, so
 if you click "Yes" the launcher of the app will appear doubled in the 
 application menu. To remove this one, copy/paste this command:
 
     - rm ~/.local/share/applications/appimagekit-openshot-qt.desktop
 
 To prevent the AppImage from always prompting for desktop integration
 when you run it, just copy/paste the following two commands: 
 
     - mkdir ~/.local/share/appimagekit
     - touch ~/.local/share/appimagekit/no_desktopintegration
 
 SITE: https://www.openshot.org

 SOURCE: https://github.com/OpenShot/openshot-qt