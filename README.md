# Signal-Protocol-Demo
A simple implementation of the Signal Protocol as a demonstration of secure end-to-end encryption.

The Signal Protocol (formerly TextSecure Protocol) defines a cryptographic encryption protocol for secure end-to-end encryption.
It was created by Open Whisper Systems for use in their secure messaging app TextSecure but has since been released, open-source to the wider community.
It has become hugely popular and earned its name as the de facto standard for securing messaging, voice and video communications.
Some of the largest adopters include Facebook Messenger and WhatsApp.

I've put together this demonstration using the Signal Protocol javascript APIs (available at the link below). It creates two users and sends a couple of encrpyted messages between them.

https://github.com/signalapp/libsignal-protocol-javascript
 
Note: InMemorySignalProtocolStore.js (and helpers.js) is taken from the signal github in the link above. In practice you can use your own store implementation.
