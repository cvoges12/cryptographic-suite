Cryptographic Suite
===================
**Notes on cryptography and protocols to use and when**

Current
-------
* Diffie-Hellman: ECDH (curve 25519)
* Digital Signature: ECDSA (curve 25519)
* Key Hash and Message Authentcation Code: Blake2s
* Hash Table: SipHash-2-4
* Symmetric Encryption: ChaCha20
* Encryption Authentication: Poly1305
* Key Derivation: HKDF
* SSL: TLS 1.3 w/ Perfect Forward Secrecy
* VPN: [Wireguard](https://www.wireguard.com/)
* [Noise protocol framework](http://www.noiseprotocol.org/)

Considerations
--------------
* ECIES
* ECOH
* AES-256 or higher
