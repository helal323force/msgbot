# Messenger ↔ Minecraft Bridge

Minecraft Railway service variables:
- `MC_BRIDGE_TOKEN` = long random secret

Messenger/Curly Railway service variables:
- `MC_BRIDGE_URL` = Minecraft bot Railway public HTTPS URL
- `MC_BRIDGE_TOKEN` = same secret as Minecraft service

Copy `mc.js` into the same command folder as the existing Curly-V2 command `.js` files.
Then use `/mc bind` in each Messenger group that should receive notifications.
