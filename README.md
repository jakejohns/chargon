# chargon

Symmetrically encrypt a file with ChaCha20 using Argon2 KDF

**IMPORTANT NOTE: DO NOT ACTUALLY USE THIS FOR ANYTHING!!!**

This is just me screwing around with stuff, and not intended to actually secure
secrets. Just use [scrypt][scrypt-cli] or something real.

[scrypt-cli]: https://github.com/Tarsnap/scrypt#the-scrypt-encryption-utility

## Usage

**Most importantly: DON'T**

```sh
# encrypt:
$ chargon e < secret.txt > secret.txt.enc

# decrypt:
$ chargon d < secret.txt.enc > secret.txt
```
