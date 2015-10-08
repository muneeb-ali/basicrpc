# basicrpc
A very simple Python RPC client. 

Currently only supports TCP netstrings (used in python Twisted servers). This client is **not** compliant with JSON-RPC 1.0/2.0 specifications and ignores them on purpose.

Installation:
> pip install basicrpc

Example:
```
from basicrpc import Proxy

c = Proxy(YOUR_SERVER_IP, YOUR_SERVER_PORT)
print c.ping()
``` 

The above example assumes that a function 'ping' is defined at the server side.
