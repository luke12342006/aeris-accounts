# Aeris — account

Archivio degli account di [Aeris](https://github.com/luke12342006/aeris-releases).

Ogni file in `accounts/` è un account **cifrato** (XChaCha20-Poly1305) con una chiave
ricavata da email e password (Argon2id) e **firmato** (Ed25519) con la chiave di
pubblicazione di Aeris. Il nome del file deriva anch'esso da email e password: senza la
password non si può sapere a chi appartiene un file né se un'email ha un account.

Qui non c'è nessun dato leggibile e nessun codice.
