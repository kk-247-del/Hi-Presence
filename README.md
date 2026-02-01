Hi Presence
A House of Ariaka Project | Co-Presence via E2EE Moment Engineering
Hi Presence is not a messenger, a calling app, or a media-sharing platform. It is a fundamentally different class of real-time communication system that rejects the dominant metaphor of "messaging as exchange" and instead treats interaction as co-presence.

In this environment, Moments occur only when the conditions for shared focus are satisfied and dissolve the instant those conditions fail. Nothing is sent, nothing is received, and nothing is stored.

🔐 The Security Manifesto: Absolute Privacy
In Hi Presence, privacy is not a policy; it is a structural constraint of the architecture.

Key-by-Key E2EE: Live Text is encrypted and streamed at the character level. As you type, the character is encrypted and projected to the other participant. There is no "send" button because there is no "message object."

Always-Warm Voice: A secure, end-to-end encrypted audio pipeline is maintained within every Moment, allowing for seamless voice escalation without re-establishing a session.

Zero Persistence: No data is ever written to a local disk or a remote database. All encryption keys (AES-256 / RSA) are ephemeral and exist only in volatile memory (RAM).

Zero Knowledge: House of Ariaka servers act only as a signaling layer. We never see text, voice, media, or encryption keys.

🚀 The Web Bridge & Seamless Onboarding
To eliminate the friction of traditional app adoption, Hi Presence introduces the Presence Address system.

Generate & Share: A native app user (Android/iOS) can generate a one-time Presence Address.

No-Install Join: The recipient can join the Moment immediately via any modern web browser. No accounts or downloads required.

Web Limitations: To maintain the high-fidelity and security standards of the House of Ariaka, Web-based sessions are limited to 3 Moments. To unlock unlimited, persistent co-presence, users must transition to the native applications.

🛠 Engineering Laws (The Locus Class Blueprint)
Hi Presence is governed by five non-negotiable architectural constraints:

No Presence, No State: No surface or stream exists unless all required participants are foregrounded and active.

Key-by-Key Expression: Communication is a live event. We reject the "packaging" of thoughts into sent messages.

Immediate Collapse: If presence is broken (screen lock, app backgrounding, or focus loss), the MomentEngine™ triggers an irreversible teardown.

Hardware-Level Privacy: Panic-wipe gestures and background-detection ensure that no ghost of an interaction remains on the device.

P2P Escalation: Media is handled via Peer-to-Peer (WebRTC) protocols, ensuring the fastest possible throughput with the lowest possible exposure.

📱 Platform Status
Android: [Deployed/Live] - Full Native Experience.

iOS: [Deployed/Live] - Full Native Experience.

Web: [Live] - Seamless Join (3-Moment Limit).

Windows: [Phase 2 - In Review] - Native Desktop Integration.

⚙️ Technical Stack
Language: Dart / Flutter

Real-time Protocol: WebRTC (Secure P2P)

Security: AES-256-GCM / RSA-4096

State Architecture: MomentEngine™ (Custom Singleton)

Signaling: Lightweight E2EE Metadata Exchange

⚖️ License & Attribution
Hi Presence is a proprietary architectural implementation by House of Ariaka. The code in this repository is licensed under the MIT License.

Copyright © 2026 House of Ariaka. All rights reserved.
