# server-monitor
Bash script to monitor HTTP and generic TCP services.

Only requires curl and ping (Linux and Windows is supported)
Supports ICMP, HTTP(S) and generic TCP connections
Enforce IPv4 or IPv4 for single checks
Define a alias name behind the URL
Send a ASCII Bell on state changes
Works on Git Bash (MinGW) on Windows
Limit the number of checks to use the script as healthcheck in CI pipelines
