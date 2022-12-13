# neurul-server-pack
 
## Setup
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
