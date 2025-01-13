# cloudflared
Access SSH behind Cloudflared Tunnel

1. Add tunnel to the cloudflared dashboard
2. Setup WARP on the client
3. Setup Cloudflare Zero Trust ->
  - Tunnels -> The_Tunnel -> Private Network
  - Routes ->
  - Targets ->
  - Settings -> Warp Client
    - Device Enrollment Permissions
    - Profile Settings -> Configure -> Split Tunnels -> Exclude (Delete server IPs range)
