All credit goes to SandboxEscaper.

Added a payload.dll (exploit.dll in the project) that adds local admin using WinExec

This won't crash spoolsv.exe unlike msf and cobalt payloads, probably because these don't return true or exit on process which terminates spools.

*I have not updated the SLN file to account for renamed payload files or directories. You probably need to change these.*

Modify the command to suit your needs. Use ur imagination.

Original includes the files with dll payload

Ported is from: https://www.securityartwork.es/2018/11/19/win7-8-10-2008-2012-32-64bits-exploit-programador-de-tareas-via-alpc-cve-2018-8440/

credit to Roberto for porting exploit to win7 and onward!

Please don't message me for help on this, just read the article and source code.

Password for rar is in article
