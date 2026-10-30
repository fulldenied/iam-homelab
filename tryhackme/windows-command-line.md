# Windows Command Line (TryHackMe)

Date: Oct 29, 2026

## What I learned

- **Network connections:** `netstat` shows active connections, the ports in use, and their state, and which application owns each one.
- **Navigating the file system:** move through folders with `cd` and list their contents with `dir`. `cd` with no arguments shows the current directory (where I am).
- **Connectivity:** `ping` sends ICMP packets to check if a host is reachable.
- **Processes:** `tasklist` lists running processes and `taskkill` ends one.
- **Environment variables:** `set` shows the system's environment variables.
- **Permissions:** `whoami /groups` shows the groups my account belongs to, including whether I have administrator rights.
- **Getting help:** adding `/?` to any command (for example, `netstat /?`) shows how to use it and its options. This is the most useful one.
