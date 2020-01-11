### List of commands available presently

Command| Does...
:-----:|:-----:
`Start`|Start a file
`Start()`|Start a executable
`Reg`|Execute reg.exe in command-line
`Run`|Execute all sorts of commands in command-line
`Try`|Test reg.exe queries in command-line
`Get`|Download a file with Wget in command-line. Support `DEFAULT` paramter, to download content to output diretory set in Settings menu, or setting an custom output path after download URL, e.g. `Get,http://www.imirin.com/files/16/Cleanmgr/1/Cleanmgr.zip,Debotnet-Files`
`GetRaw`|Download raw file content with Wget in command-line. Custom output directory is supported as in `Get` command
`Url`|Open a hyperlink in web per default web browser
`Echo`|Test Mode ONLY in command-line
`TaskKill`|Kill task with name or PID in command-line
`rm`|Deletes a file
`rmdir`|Deletes a directory

### List of app parameter available presently

Parameter| Does...
:-----:|:-----:
`STDOUT (default switch)`|Captures the console output to Debotnet
`SHOWCLI`|Redirects the ouput to cmd.exe and shows the command prompt during execution
`- (none parameter)`|Performs the command-line tasks silent and without output
