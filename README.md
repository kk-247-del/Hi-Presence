# Hi Presence

**Hi Presence** is a fundamentally different class of real-time communication system. It rejects the dominant digital metaphor of "messaging as exchange" and instead treats interaction as **co-presence**. 

In the Hi Presence environment, **Moments** occur only when the conditions for shared focus are satisfied and dissolve the instant those conditions fail. Nothing is sent, nothing is received, and nothing is stored. Interaction is not an object that moves between people, but a state that briefly exists between them.

## 🔐 Absolute Security: End-to-End Encrypted
Privacy in Hi Presence is not a policy; it is a structural impossibility of data persistence.

* **Full E2EE:** All text and voice streams are secured with **End-to-End Encryption (AES-256 / RSA)**. Keys are generated at the moment of instantiation and exist only in volatile memory (RAM).
* **Zero Knowledge:** The backend never sees text, voice, media, or encryption keys. 
* **Zero Persistence:** Because there is no "send" primitive, no data is ever written to a local disk or a remote database. When a Moment collapses, the keys and the data are wiped instantly. You cannot leak what does not exist.

## The Core Laws
Hi Presence is governed by five non-negotiable engineering constraints:
1.  **No Presence, No State**: If required participants are not foregrounded and active, no surface, stream, or buffer exists.
2.  **No Send Primitive**: There is no `send()` or `submit()`. Interaction exists only as `express()` or `escalate()`.
3.  **No Persistent Objects**: Text and voice exist only as live streams. Nothing is serializable beyond the Moment.
4.  **Immediate Collapse**: Any violation of presence—a screen lock or backgrounding the app—triggers an immediate and irreversible teardown.
5.  **Seamless Escalation**: Transitioning from text to voice is an unmute of an "always-warm" E2EE pipeline, not a new session request.

## Technical Stack
* **Framework:** Flutter (Windows Native)
* **Engine:** MomentEngine™ (Custom Signaling & Teardown Logic)
* **Real-time Engine:** WebRTC (Peer-to-Peer)
* **Security:** AES-256 / RSA End-to-End Encryption
* **State Management:** Riverpod

## Current Functional Status (Alpha)
This repository implements the foundational layers of the architecture:
* **Presence Detection**: Continuous evaluation of device state and foreground activity.
* **Moment Instantiation**: Establishing the shared E2EE surface only when mutual engagement is proven.
* **Live Text Streaming**: Real-time expression where typing *is* the interaction.
* **Voice Escalation**: Secure audio tracks that activate within an existing Moment.
* **Collapse Engine**: The "Panic-Wipe" logic that clears UI, keys, and buffers upon any presence failure.

---

## License
Copyright © 2026 **Cariselle Technologies**.

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
