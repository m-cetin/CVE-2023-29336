# CVE-2023-29336 - Win32k Local Privilege Escalation - PoC

Details have emerged about a now-patched actively exploited security flaw in Microsoft Windows that could be abused by a threat actor to gain elevated privileges on affected systems.

The vulnerability, tracked as CVE-2023-29336, is rated 7.8 for severity and concerns an elevation of privilege bug in the Win32k component.

"An attacker who successfully exploited this vulnerability could gain SYSTEM privileges," Microsoft disclosed in an advisory issued last month as part of Patch Tuesday updates.

Avast researchers Jan Vojtěšek, Milánek, and Luigino Camastra were credited with discovering and reporting the flaw.

Win32k.sys is a kernel-mode driver and an integral part of the Windows architecture, being responsible for graphical device interface (GUI) and window management.

While the exact specifics surrounding in-the-wild abuse of the flaw is presently not known, Numen Cyber has deconstructed the patch released by Microsoft to craft a proof-of-concept (PoC) exploit for Windows Server 2016.
