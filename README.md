# Complete Media Docker Compose File

After installing jellyfin multiple times and its supporting containers. i fialy came up with this self contained stack.  The stack contains the following containers

- Jellyfin
- Radarr
- Sonarr
- QBittorrent
- File Browser

The most interesting part of this compose file is the network. All containers have a static IP. This helps with preventing un predictable behavior when deployed. The operation of the containers remain consistent accross all deployments

Note: the compose file is self explainatory however, i will continue to add more information as and when time beocmes available
