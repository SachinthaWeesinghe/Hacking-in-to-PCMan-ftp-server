# Hacking-in-to-PCMan-ftp-server
PCMan is win32 application that is vulnerable to buffer overflow attack
PCMan FTP Server 2.0.7 has a public vulnerability CVE-2013-4730 based on buffer overflow that is allowed remote attacker to execute arbitrary code via client command. This is a stack based buffer overflow vulnerability. In order to preform a buffer overflow, we need to use specific code in specific space in the stack.
