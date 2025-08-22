![](./resc/logo-transparent.png)

# EnProto Specification

## Overview
`EnProto` is a lightweight and secure communication protocol designed for cross-platform interoperability using [Protocol Buffers (protobuf)](https://developers.google.com/protocol-buffers).
The protocol supports custom asymmetric key encryption (RSA) and symmetric authenticated encryption (AES-GCM) to provide confidentiality, integrity, and replay protection without relying on external certificate authorities (CAs).

The protocol defines standardized packet structures that can be implemented in multiple programming languages to enable seamless encrypted communication across distributed systems.
