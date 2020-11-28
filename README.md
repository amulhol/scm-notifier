# SCM Notifier

SCM Notifier is a tool to monitor and give desktop notifications for Git and SVN repositories.

![Example](https://raw.github.com/amulhol/scm-notifier/master/docs/example.png)

This program was originally forked from SVN Notifier (http://svnnotifier.tigris.org/).

This is a fork from https://github.com/pocorall/scm-notifier

### [Download Latest Version - Nov 2020](https://github.com/amulhol/scm-notifier/releases/download/16.00.01/SCM_Notifier.exe)

Latest Version resolves following:
- Git repositories always reporting they need to be updated for Git 2.29.2
- Status checking thread hangs for Git repository with many branches
- Update all not working for Git repositories


### Run requirements
* Subversion (optional)
* TortoiseSVN (optional)
* Git
* TortoiseGit
* Microsoft Windows 2000/XP/Vista/7/8/8.1/10
* Microsoft .NET Framework 4.5

If you want to use Git only, the configuration for paths to Subversion and TortoiseSVN can be left blank.

### Build requirements
* Microsoft Visual Studio 2010 or above, C#


### Configuration
To run SCM Notifier properly, you have to specify paths to executables of Subversion, TortoiseSVN, Git and TortoiseGit. It can be specified in Settings dialog shown below:

![Bad configuration](https://raw.github.com/pocorall/scm-notifier/master/docs/settings.png)

If it is not set properly, notification worn't work (shown in red icon).

![Bad configuration](https://raw.github.com/pocorall/scm-notifier/master/docs/badConfig.png)


### License

This software is licensed under [GNU General Public License](http://www.gnu.org/licenses/licenses.html#GPL)
