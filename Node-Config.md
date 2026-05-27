# Node Configuration

Winchester Meshtastic runs stock default settings, no custom channel or passphrase.

## Configuration

| Setting      | Value                                                        |
|--------------|--------------------------------------------------------------|
| Region       | US (915 MHz)                                                 |
| Modem Preset | LongFast                                                     |
| Channel      | Default (no custom name or PSK)                              |
| Hop Limit    | 3                                                            |
| Device Role  | `CLIENT_BASE` if mounted or fixed; `CLIENT` for portable use |

Verify or change these under **Settings → Radio Configuration → LoRa** in the Meshtastic app.

## Anchor Node Candidates

A useful anchor node has:

- Fixed installation
- Elevation or clear line of sight toward other nodes or populated areas (the west side of Winchester is higher in elevation than the east side)
- Reliable power (solar or wired)

If your location fits, reach out in the OSW Discord, well-positioned fixed nodes are valuable to the network and may be considered as dedicated relays through a community conversation.
