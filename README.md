# patch_anyconnect
Workaround script for Cisco AnyConnect on Mac

Cisco AnyConnect will monitor route table changes and keep it as the one when it was connected. So you cannot change the route table after the connection was established. There are some tips to hack vpnagentd but VPN app is always updating. This is the simple workaround script to keep your own route rule.

Basicly it keeps the route rules before AnyConnect was connected.

- Keep all your VPNs connected
- Disconnect AnyConnect
- Insert route rules
- Connect AnyConnect
