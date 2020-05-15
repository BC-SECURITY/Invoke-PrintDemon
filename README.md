#PrintDemon
This is an [Empire](https://github.com/BC-SECURITY/Empire) launcher PoC using [PrintDemon](https://github.com/ionescu007/PrintDemon) and [Faxhell](https://github.com/ionescu007/faxhell), the [CVE-2020-1048](https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2020-1048) is a privilege escalation vulnerability that allows a persistent threat through Windows Print Spooler.
The vulnerability allows an unprivileged user to gain system-level privileges.Based on @ionescu007 PoC.

##Code Borrowed from
https://github.com/ionescu007/PrintDemon
https://github.com/ionescu007/faxhell
https://stackoverflow.com/questions/4442122/send-raw-zpl-to-zebra-printer-via-usb
https://stackoverflow.com/questions/29759854/how-to-connect-to-tcp-socket-with-powershell-to-send-and-receive-data