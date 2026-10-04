# browserdb

browserdb shows you what your browser tells every website you visit. It is a simple, dark site with sharp boxes. Each box shows one piece of information, like your WebRTC IP, your screen size or your timezone.

## What it shows

- WebRTC IP
- User agent, platform and languages
- Timezone
- Screen size, window size, pixel ratio and color depth
- CPU threads and device memory
- WebGL renderer (your graphics card)
- Canvas fingerprint
- Connection, battery and storage
- Privacy settings like Do Not Track
- Referrer and automation flag

## Privacy

Everything is read inside your browser and nothing is sent to a server. The only exception is the WebRTC check. It asks a public STUN server (`stun.l.google.com`) which address it can see.
