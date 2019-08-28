# winrm_shell
Ruby script that calls an almost interactive shell via WinRM (TCP/5985) on an Windows machine.

# ./winrm_shell.rb -h

	Usage: ./winrm_shell.rb [options]

	Example:
	./winrm_shell.rb -s 192.169.0.5 -d contoso.com -u bob -p 'P@ssw0rd'

	Obs. Options --server, --user and --password are REQUIRED!

	Options:
	
    -h, --help                       Show this help message
    -s, --server SERVER              The server hostname or IP address.
    -d, --domain DOMAIN              The domain name.
    -u, --user USER                  The username.
    -p, --password PASSWORD          The user's password.


#                                                                                              #
#                     *** Do NOT use this for illegal or malicious use ***                     #
#                By running this, YOU are using this program at YOUR OWN RISK.                 #
#            This software is provided "as is", WITHOUT ANY guarantees OR warranty.            #
#                                                                                              #
