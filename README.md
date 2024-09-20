# `veracrypt`

TrueCrypt and VeraCrypt bindings for Dart using the 
[`veracrypt`](https://crates.io/crates/veracrypt) crate.  This project is a re-
implementation of the original TrueCrypt encryption/decryption algorithms and 
their newer continuances in VeraCrypt.  VeraCrypt is a trademark is owned by 
IDRIX.  This project is no way affiliated with IDRIX nor claims ownership of 
any of their copyrighted work nor trademarks.

## Getting started
Run the command-line interface:
```sh
dart pub activate veracrypt
veracrypt
```

or use the library as in:
```dart
dart pub add veracrypt
```
<!--
```dart
import 'package:veracrypt/veracrypt.dart';

void main() {
  final veracrypt = VeraCrypt();
  final password = 'password';
  final volumePath = 'path/to/volume';
  final result = veracrypt.mount(password, volumePath);
  print(result.fileList);
}
```
