# What is OpenSSL
OpenSSL is an open-source CMD toolkit that provides general-purpose cryptography and secure communication capabilities. It alows for generating keys and certificates used in protocols such as ssl/tls.


# OpenSSL libraries
### libcrypto
Provides encryption, hash funcitons, digital signatures, etc..
It also provides support for reading and writign digital certificates (also known as X.509 certificates)

### libssl
Provides funcitons to perform secure communication between 2 endpoints. It supports SSL/TLS, DTLS and QUIC standards.

libssl depends on libcrypt while libcrypto is independent.