# Write-up for underthewire.tech/century
Powershell walkthroughs for Century Wargames on [underthewire](https://underthewire.tech/wargames).  
(Note: all passwords are lowercase)

## Century1
> The goal of this level is to log into the game using credentials obtained via Slack.

The password, when prompted, is **century1**.
```powershell
PS C:\users\TheLinuxJedi\desktop> ssh century1@century.underthewire.tech -p 22
```

## Century2
> The password for Century2 is the build version of the instance of PowerShell installed on this system.
```powershell
PS C:\users\century1\desktop> $PSVersionTable

Name                           Value
----                           -----
PSVersion                      5.1.14393.6343
PSEdition                      Desktop
PSCompatibleVersions           {1.0, 2.0, 3.0, 4.0...}
BuildVersion                   10.0.14393.6343
CLRVersion                     4.0.30319.42000
WSManStackVersion              3.0
PSRemotingProtocolVersion      2.3
SerializationVersion           1.1.0.1
```
The password for Century2 is: **10.0.14393.6343**
