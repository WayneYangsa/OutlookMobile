# AutodetectDebugging

## How to use this script
**Step1**: Download this script to your Computer 

**Step2**: Open Powershell to locate the folder where the script is

**Step3**: Run `.\AuoDetectDebugging.ps1 -Email {yourTestEmailAddress}`

**For example**: `.\AuoDetectDebugging.ps1 -Email "test@contoso.com"`

## For Hybrid Exchange accounts

You can also run the command with additional params like this:

<<<<<<< HEAD
`.\AuoDetectDebugging.ps1 -Email {yourTestEmailAddress} -Hybrid` 
=======
### `-Hybrid`

`.\AuodetectDebugging.ps1 -Email {yourTestEmailAddress} -Hybrid` 
>>>>>>> daed23beb65b9c8f16ebac1ddd0778ebd1284315
`-Hybrid` will call the On-Prem AutoDiscover endpoint additonally.

**For example:** `.\AuoDetectDebugging.ps1 -Email "hybrid@contoso.com" -Hybrid`

<<<<<<< HEAD
`.\AuoDetectDebugging.ps1 -Email {yourTestEmailAddress} -Hybrid -CustomAutoD {theHostnameOfCustomAutoDiscover}` 
=======

### `-CustomAutoD`

`.\AuodetectDebugging.ps1 -Email {yourTestEmailAddress} -Hybrid -CustomAutoD {theHostnameOfCustomAutoDiscover}` 
>>>>>>> daed23beb65b9c8f16ebac1ddd0778ebd1284315

`-CustomAutoD {theHostnameOfCustomAutoDiscover}` allows you specificing the custom OnPrem AutoDiscover Hostname.

**For example：** `.\AuoDetectDebugging.ps1 -Email "hybrid@contoso.com" -Hybrid -CustomAutoD "autodiscover.contoso.com"`

NOTE: For `callOnPremAutoDV2` function, it's from https://github.com/tweekerz/PowerShell/tree/master/TestHMAEAS
