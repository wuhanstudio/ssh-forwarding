
# Allow Forwarding

Change /etc/ssh/sshd_config

	X11Forwarding yes
	AllowAgentForwarding yes
	AllowTcpForwarding yes
	GatewayPorts yes

# Keep Alive

Change /etc/ssh/sshd_config

	ClientAliveInterval 60
	ClientAliveCountMax 5

