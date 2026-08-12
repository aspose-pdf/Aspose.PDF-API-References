---
title: "System::Security::Cryptography::RSA klass"
linktitle: "RSA"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSA klass. Basisklass för implementationer av RSA-algoritmen. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3400
url: /sv/cpp/system.security.cryptography/rsa/
---
## RSA class


Basisklass för implementationer av [RSA](./)‑algoritmen. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class RSA : public System::Security::Cryptography::AsymmetricAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [Create](./create/)() | Skapar standardimplementering av [RSA](./)‑algoritmen. |
| static [Create](./create/)(const String\&) | Skapar standardimplementering av [RSA](./)‑algoritmen. |
| static [Create](./create/)(int32_t) | Skapar standardimplementering av [RSA](./)‑algoritmen med specificerad nyckelstorlek. |
| static [Create](./create/)(const RSAParameters\&) | Skapar standardimplementering av [RSA](./)‑algoritmen med specificerade parametrar. |
| static [CreateFromXmlString](./createfromxmlstring/)(const String\&) | Skapar standardimplementering av [RSA](./)‑algoritmen med specificerade XML‑kodade parametrar. |
| virtual [Decrypt](./decrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) | Dekrypterar indata med den specificerade utfyllnadsläget. |
| virtual [DecryptValue](./decryptvalue/)(ByteArrayPtr) | Dekrypterar värde med privat nyckel. |
| virtual [Encrypt](./encrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) | Krypterar indata med den specificerade utfyllnadsläget. |
| virtual [EncryptValue](./encryptvalue/)(ByteArrayPtr) | Krypterar värde med privat nyckel. |
| virtual [ExportParameters](./exportparameters/)(bool) | Exporterar alla parametrar. |
| [FromXmlString](./fromxmlstring/)(String) override | Initierar objekt med XML‑kodade parametrar. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | RTTI-information. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Hämtar signaturalgoritmen som är associerad med CSP‑objektet. |
| virtual [ImportParameters](./importparameters/)(RSAParameters) | Importerar alla parametrar från datastrukturen. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Beräknar hashvärdet för den specificerade dataarrayen med den specificerade hash‑algoritmen och utfyllnad, och signerar resultatet. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Beräknar hashvärdet för den specificerade dataarrayen med den specificerade hash‑algoritmen och utfyllnad, och signerar resultatet. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Beräknar hashvärdet för den specificerade binära strömmen med den specificerade hash‑algoritmen och utfyllnad, och signerar resultatet. |
| virtual [SignHash](./signhash/)(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) | Beräknar signaturen för det specificerade hashvärdet. |
| [ToXmlString](./toxmlstring/)(bool) override | Exporterar alla parametrar i XML‑format. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) | Verifierar att signaturen för den angivna binära strömmen är giltig. |
| virtual [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) | Verifierar att signaturen för den specificerade hash‑värdet är giltig. |
## Se även

* Class [AsymmetricAlgorithm](../asymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
