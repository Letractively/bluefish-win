<h1><font color='#FF0000'>
Please note that there is now an installer available for the <a href='http://bluefish.openoffice.nl'>Bluefish Editor</a> for Windows since version 1.3.7.<br>
<br>
The version listed here is severely outdated and unsupported!<br>
<br>
Please use the installers available from <a href='http://sourceforge.net/projects/bluefish/files/'>http://sourceforge.net/projects/bluefish/files/</a>
</font></h1>
<br />
<br />
<br />
<br />
<br />
# Bluefish-win32 #
## built on [bluefish 1.0.7](http://bluefish.openoffice.nl) ##
This is just a minimal working version of bluefish on Windows.

In order to run the program, GTK+ must be installed and the installation path added to the system path variable.

> The GTK+ runtime is available here as an installer:
> [sourceforge downloads](http://sourceforge.net/project/showfiles.php?group_id=121075&package_id=132255&release_id=521423)
> Select file gtk+-2.10.13-setup.exe

> It should work with the runtime listed below:
> http://ftp.gnome.org/pub/gnome/binaries/win32/gtk+/2.10/gtk+-2.10.14.zip
> Additionally, the shared libraries in the bin folder are also needed as they are not provided by the GTK runtime installer.

> The release version listed here was compiled with MSYS and MinGW on Win XP sp2. There is a bunch of dependencies required to build bluefish, most are available from the above ftp repository.  As soon as I can find some time I will generate a list of the depedencies and the download locations.

> One note, Orbit2 needed to be an older version as the newest version at the compile time would not work.  This appears to be an issue with Orbit2 as other programs seem to have the same problem.

> Please use the issue tracker to report bugs.

> I finally got a hold of a Vista machine for testing and Bluefish-win should now install without error.

> The installer has been updated to download GTK+ and install it if it is not installed.

May 12, 2008
> Added the language translation files to the installer.  I am waiting for feedback.

Jan 21,2010
> After more than a year without being able to work on this project,it is time to call it quits.  At least now there is officially a [build for Windows.](http://bluefish.openoffice.nl/)
> As of February 1, 2010, I will be removing the download links from this sight although svn will still be available.

