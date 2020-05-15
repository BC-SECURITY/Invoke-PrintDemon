# PrintDemon
This is an [PowerShell Empire](https://github.com/BC-SECURITY/Empire) launcher PoC using [PrintDemon](https://github.com/ionescu007/PrintDemon) and [Faxhell](https://github.com/ionescu007/faxhell). The module has the Faxhell dll already embedded which levages [CVE-2020-1048](https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2020-1048) for privilege escalation. The vulnerability allows an unprivileged user to gain system-level privileges and is based on @ionescu007 PoC.

![Invoke-Demon_Demo](https://user-images.githubusercontent.com/20302208/82018233-b6a83280-9639-11ea-8db0-28a82a5eb5d7.gif)

__Note__: This is a proof of concept. We have encountered some issues with printing to C:\Windows\System32\Ualapi.dll on some machines. We have not yet isolated what is causing this. You can drop the dll directly into System32 to test the launcher if you encounter issues.

## Code Borrowed from
https://github.com/ionescu007/PrintDemon
https://github.com/ionescu007/faxhell
https://stackoverflow.com/questions/4442122/send-raw-zpl-to-zebra-printer-via-usb
https://stackoverflow.com/questions/29759854/how-to-connect-to-tcp-socket-with-powershell-to-send-and-receive-data
