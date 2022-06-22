# neurul-server-pack
 
## Setup
### Server Login
1. Connect to server via the command line.

     ```
     ssh \[username]@\[serverip])
     ```
2. Enter the password for the specified username.
### Reverse Proxy
1. Navigate to /neurul-server-pack/reverse-proxy.
2. Update customsettings.json.

     ```
     nano customsettings.json
     ```
3. Run using docker-compose.

     ```
     docker-compose -f docker-compose.yml -f docker-compose.override.yml up
     ```
