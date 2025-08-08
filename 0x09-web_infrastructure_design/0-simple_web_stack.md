# Simple Web Stack for www.foobar.com

## Architecture Overview

```plaintext
User's Computer
       |
       | 1. DNS Lookup (www.foobar.com)
       |
       v
Domain Name System (DNS) -> www.foobar.com -> 8.8.8.8 (Server IP)
       |
       | 2. HTTP/HTTPS Request to Server IP
       |
       v
```
+----------------------------------+
|          Single Server            |
|  IP: 8.8.8.8                    |
|                                  |
| +----------------------------+  |
| |      Nginx Web Server      |  |
| +----------------------------+  |
|             |                    |
|             | Pass Request to    |
|             | Application Server |
| +----------------------------+  |
| |   Application Server (e.g.  |  |
| |   PHP-FPM, Node.js, etc.)   |  |
| +----------------------------+  |
|             |                    |
|             | Queries/Updates    |
|             |                    |
| +----------------------------+  |
| |         MySQL Database      |  |
| +----------------------------+  |
+----------------------------------+
