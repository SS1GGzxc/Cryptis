# CryptoLoc
Fast tiny library for converting between hex, Base64 and string

# Install

```sh
  npm install cryptoloc
```
```sh
  yarn add cryptoloc
```
```sh
  pnpm add cryptoloc
```

## Get Started

### Hex
Encrypt message
``` javascript
  import {Hex} from 'cryptoloc';

  const message = "Hello world!";

  console.log("Encrypted message: " + Hex.encrypt(message)); // Encrypted message: 48656c6c6f20776f726c6421
```

Decrypt message
``` javascript
  import {Hex} from 'cryptoloc';

  const message = "48656c6c6f20776f726c6421";

  console.log("Decrypted message: " + Hex.decrypt(message)); // Encrypted message: Hello world!
```
### Base64
Encode message
``` javascript
  import {Base64} from 'cryptoloc';

  const message = "Hello world!";

  console.log("Encrypted message: " + Base64.encode(message)); // Encrypted message: SGVsbG8gV29ybGQh
```

Decode message
``` javascript
  import {Base64} from 'cryptoloc';

  const message = "SGVsbG8gV29ybGQh";

  console.log("Decrypted message: " + Base64.decode(message)); // Encrypted message: Hello world!
```
