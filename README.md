# Venu

Venu is a location-aware social platform with real-time chat, calls, and mobile
clients.

[Launch the interactive product demo](https://ayoubodf-dev.github.io/venu-showcase/)

![Venu web interface](docs/images/demo.png)

## Highlights

- React Native mobile experience
- Location-aware discovery
- Real-time chat and presence
- Voice and video calling
- Desktop companion experience

## Architecture

```mermaid
flowchart LR
    Mobile["React Native mobile"] --> API["Private application API"]
    Desktop["Desktop client"] --> API
    API --> Realtime["Realtime messaging"]
    API --> Location["Location services"]
    API --> Storage["Application data"]
    Mobile --> Calls["WebRTC calls"]
    Desktop --> Calls
```

## Source availability

The mobile, desktop, and backend implementations are private and proprietary.
This public repository is a source-free product showcase.

Copyright © 2026 Ayoub Odf. All rights reserved.
