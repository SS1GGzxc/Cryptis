# Cryptis

Fast tiny library for converting between hex and string

# Install

```sh
  npm install cryptis
```
```sh
  yarn add cryptis
```
```sh
  pnpm add cryptis
```

## Get Started

Encrypt message
``` javascript
  import {encrypt} from 'cryptis';

  const message = "Hello world!";

  console.log("Encrypted message: " + encrypt(message)); // Encrypted message: 48656c6c6f20776f726c6421
```

Decrypt message
``` javascript
  import {decrypt} from 'cryptis';

  const message = "48656c6c6f20776f726c6421";

  console.log("Decrypted message: " + decrypt(message)); // Encrypted message: Hello world!
```
