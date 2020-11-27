# SCM Notifier

SCM Notifier is a tool to monitor Git and SVN repositories.

This program is originally forked from SVN Notifier (http://svnnotifier.tigris.org/).

This is a fork from https://github.com/pocorall/scm-notifier

### [Download Latest Version - Nov 2020](https://github.com/pocorall/scm-notifier/releases/download/16.00.00/SCM_Notifier.exe)

Latest Version resolves following:
- Git repos always reporting need update for Git 2.29.2
- Status checking thread hangs for Git repo with many branches
- Update all not working for Git repos


### Run requirements
* Subversion (optional)
* TortoiseSVN (optional)
* Git
* TortoiseGit
* Microsoft Windows 2000/XP/Vista/7/8/8.1/10
* Microsoft .NET Framework 4.5

If you want to use Git only, let the configuration for path to Subversion and TortoiseSVN left blank.

### Build requirements
* Microsoft Visual Studio 2010 or above, C#


### Configuration
To run SCM Notifier properly, you have to specify paths to executables of Subversion, TortoiseSVN, Git and TortoiseGit. It can be specified in Settings dialog shown below:

![Bad configuration](https://raw.github.com/pocorall/scm-notifier/master/docs/settings.png)

If it is not set properly, notification worn't work (shown in red icon).

![Bad configuration](https://raw.github.com/pocorall/scm-notifier/master/docs/badConfig.png)


### License

This software is licensed under [GNU General Public License](http://www.gnu.org/licenses/licenses.html#GPL)
