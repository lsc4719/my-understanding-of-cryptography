# my-understanding-of-cryptography

### cryptography

- public-key cryptography
  - primitives
    - signature: RSA, ECDSA, Ed25519
    - key exchange: (EC)DH, X25519
  - applications
    - signature
      - X.509 (public-key authentication)
      - JWT (claim authentication)
      - code signing
    - signature + key exchange
      - server-authenticated AKE: TLS, SSH, QUIC
      - mutual-authenticated AKE: mTLS
- symmetric cryptography
  - primitives
    - AEAD
- cryptographic hash functions
  - primitives
    - SHA-2, SHA-3
  - applications
    - HMAC
    - KDF (HKDF)
    - password hashing (Argon2)
