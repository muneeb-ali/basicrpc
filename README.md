# basicrpc
A very simple Python RPC client

Installation:
> pip install basicrpc

Example:
```
from basicrpc import Proxy

c = Proxy(YOUR_SERVER_IP, YOUR_SERVER_PORT)
print c.ping()
``` 
