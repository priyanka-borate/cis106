1.) A path is either relative or absolute. An absolute path always contains the root element and the complete directory list required to locate the file. A relative path needs to be combined with another path in order to access a file. For example, joe/foo is a relative path.

2.) Windows uses backslashes for paths, while everything else seems to use forward slashes.Modern software tries to automatically correct you when you type the wrong type of slash, so it doesn’t matter which type of slash you use most of the time. But, sometimes, the difference still matters.

3.) On Windows, you can't have a file named file and another file named FILE in the same folder. The Windows file system isn't case sensitive, so it treats these names as the same file. On Linux, the file system is case sensitive. This means that you could have files named file, File, and FILE in the same folder.

4.) The Filesystem Hierarchy Standard (FHS) defines the directory structure and directory contents in Linux distributions. It is maintained by the Linux Foundation. The latest version is 3.0, released on 3 June 2015. Linux distributions (and other operating systems) can voluntarily conform to the FHS. 

5.) 

| Directory| What is it used for? |
|----|----|----|
| /bin | Binary commands that are accessible for system administration, users and scripts.|
| /devDevice | Files such as DVD/CD |
| /etcStatic | configuration files, local to the machine |
| /homePersonal | Configuration files |
| /libShared | Libraries | 
| /optStatic | Shareable add-on software packages |
|/tmp | Temporary Files that should be deleted, when the system is rebooted |
| /var | Variable data files |
|/proc | Virtual file system,control and information centre for kernel|
| /usr | Shareable, read only applications and files | 

6.) The period at the beginning of a file name means that the file or directory is hidden. 

7.) The command I would use to list all the files inside the directory would be ls /usr/share/

8.)  If I am trying to move to the home directory, I would just type cd 

9.)  The command is telling the terminal to go to .config directory then the command has “htop” which is a command for an interactive process viewer, used to solve problems. Then it was would long list all the files alphabetically. 

10.) John can use 2 commands, the first command would be to use cd  * /var/www/html/webapp then he can use ls -lach. 