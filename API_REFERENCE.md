# API reference

Hashing, HMAC, random bytes, and AES-GCM are explicit host externs. Wrappers validate output sizes, AES key/nonce sizes, and empty HMAC keys before crossing the boundary. Hosts must use audited platform cryptography and return failure on authentication errors.

