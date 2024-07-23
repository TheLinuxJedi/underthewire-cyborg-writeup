# Write-up for underthewire.tech/century
Powershell walkthroughs for Century Wargames on [underthewire](https://underthewire.tech/wargames).  
(Note: all passwords are lowercase)

## Cyborg1
> The goal of this level is to log into the game using credentials obtained via Slack.

The password, when prompted, is **cyborg1**.
```powershell
PS C:\users\TheLinuxJedi\desktop> ssh century1@century.underthewire.tech -p 22
```

## Cyborg2
> The password for Century2 is the build version of the instance of PowerShell installed on this system.
```powershell
PS C:\users\cyborg1\desktop> get-aduser -filter 'name -like "*roger*"' -Properties st


DistinguishedName : CN=Rogers\, Chris\ ,OU=T-65,OU=X-Wing,DC=underthewire,DC=tech
Enabled           : False
GivenName         : Chris
Name              : Rogers, Chris
ObjectClass       : user
ObjectGUID        : ee6450f8-cf70-4b1d-b902-a837839632bd
SamAccountName    : chris.rogers
SID               : S-1-5-21-758131494-606461608-3556270690-2177
st                : kansas
Surname           : Rogers
UserPrincipalName : chris.rogers
```
The password for Century2 is: **kansas**

## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


## Cyborg3
>

```powershell

```
The password for Cybgorg3 is: ****


