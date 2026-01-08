# my-understanding-of-cryptography

### cryptography

- public-key cryptography
  - primitives
    - signature: RSA, ECDSA, Ed25519
    - key exchange: (EC)DH, X25519
  - applications
    - public-key signature
      - X.509 (public-key authentication)
      - code signing
      - JWT (when using RS256 / ES256 / EdDSA)
    - authenticated key exchange (AKE)
      - server-authenticated
        - TLS
        - SSH
        - QUIC
      - mutual-authenticated
        - mTLS

- symmetric cryptography
  - primitives
    - AEAD
    - MAC (HMAC)
  - applications
    - data encryption
      - secure channels (TLS record layer, SSH transport)
    - token authentication
      - JWT (when using HS256)

- cryptographic hash functions
  - primitives
    - SHA-2, SHA-3
  - applications
    - HMAC
    - KDF (HKDF)
    - password hashing (Argon2)
