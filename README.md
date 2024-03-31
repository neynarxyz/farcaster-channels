# Update 1.11.24
Warpcast has launched permissionless channel creation and hundreds of new channels have been created since. New Neynar APIs [here](https://docs.neynar.com/reference/list-all-channels) offer real time channel data.

# farcaster-power-user-badges

A public repository for power user badges (updated each week Tuesdays at 12AM UTC
per https://www.supercast.xyz/c/0x4ee78c2e0f383d51e0285a3f8cb7941adf2cf70f )

update with a command like:

`curl GET https://api.warpcast.com/v2/power-badge-users > yyyymmdd.json`

# farcaster-channels
A directory for well-known channels across different Farcaster clients

Channels are (currently) a client-only feature, pioneered on the [Warpcast](https://warpcast.com/) client. Channels use [FIP-2](https://github.com/farcasterxyz/protocol/discussions/71) on the Farcaster protocol, but it's up to clients how to render them.

This repo serves as a public good for mapping well-known channels across Farcaster clients.


## How to fetch this data over an API

### Example to fetch by client
```
curl https://raw.githubusercontent.com/neynarxyz/farcaster-channels/main/warpcast.json
```

### Contributing guidelines
Open a PR to add or update
- clients: add new clients (e.g. Warpcast is a client and channels within Warpcast are stored in warpcast.json)
- channels: add new channels to existing client lists (e.g. add to the warpcast.json list if new channels get added on Warpcast)
- channel metadata: edit channel metadata (e.g. if channel name changes for a parent_url)
  
