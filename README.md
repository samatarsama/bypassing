# Windows UAC Lab

A PowerShell lab script that explores User Account Control (UAC) elevation behavior through the Windows Connection Manager Profile Installer (CMSTP).

The [source script](bypass.ps1) generates an INF file and invokes CMSTP. Its default command attempts to change a Microsoft Defender exclusion. Review the source in an isolated Windows lab.
