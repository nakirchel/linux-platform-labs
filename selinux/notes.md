# SE Linux Notes
## Security Enhanced Linux

getenforce

	enforcinag - blocks and logs violations
	permissive - logs but does not block
	disabled - off

setenforce
restorecon
semanage
ls -Z
ps -eZ
sestatus ( coming back to this after more labs )
SE Linux labels files and processes
Apache needs the correct context
restorecon restores default labels
