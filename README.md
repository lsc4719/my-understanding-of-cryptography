# my-understanding-of-cryptography

### cryptography

- public-key cryptography
  - primitives
    - signature: RSA, ECDSA, Ed25519
    - key exchange: (EC)DH, X25519
  - applications
    - signature applications
      - X.509 (public-key authentication)
      - JWT (claim authentication)
      - code signing
    - authenticated key exchange (AKE)
      - server-authenticated: TLS, SSH, QUIC
      - mutual-authenticated: mTLS
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
