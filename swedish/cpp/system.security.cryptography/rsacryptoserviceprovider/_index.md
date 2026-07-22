---
title: "System::Security::Cryptography::RSACryptoServiceProvider-klass"
linktitle: "RSACryptoServiceProvider"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::RSACryptoServiceProvider-klass. RSA-algoritm i CSP-form. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 3500
url: /sv/cpp/system.security.cryptography/rsacryptoserviceprovider/
---
## RSACryptoServiceProvider class


[RSA](../rsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class RSACryptoServiceProvider : public System::Security::Cryptography::RSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Decrypt](./decrypt/)(const ByteArrayPtr\&, bool) | Dekrypterar meddelande. Ej implementerad. |
| [Decrypt](./decrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) override | Dekrypterar indata med den specificerade utfyllnadsläget. |
| [Dispose](./dispose/)() override | Frigör data associerad med objektet. |
| [Encrypt](./encrypt/)(const ByteArrayPtr\&, bool) | Krypterar meddelande. Ej implementerad. |
| [Encrypt](./encrypt/)(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) override | Krypterar indata med den specificerade utfyllnadsläget. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Exporterar blob med information om nyckeln. Ej implementerad. |
| [ExportParameters](./exportparameters/)(bool) override | Exporterar CSP-parametrar. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Hämtar ett [CspKeyContainerInfo](../cspkeycontainerinfo/)‑objekt. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Kontrollerar nyckelutbytesalgoritmen som är associerad med objektet. |
| [get_KeySize](./get_keysize/)() override | Hämtar nyckelstorlek som används av algoritmen. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Kontrollerar om nyckeln är beständig i CSP‑objektet. |
| [get_PublicOnly](./get_publiconly/)() const | Kontrollerar om endast den offentliga nyckeln finns i CSP‑objektet. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Hämtar signaturalgoritmen som är associerad med CSP‑objektet. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Kontrollerar om nyckeln är beständig i maskinlagret istället för användarlagret. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Importerar blob med information om nyckeln. Ej implementerad. |
| [ImportParameters](./importparameters/)(RSAParameters) override | Importerar CSP-parametrar. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)() | RTTI-information. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Konstruktor. Ej implementerad. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(const RSAParameters\&) | Konstruktor. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(int32_t) | Konstruktor. |
| [RSACryptoServiceProvider](./rsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Konstruktor. Ej implementerad. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Definierar om nyckeln är beständig i CSP‑objektet. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Definierar om nyckeln är beständig i maskinlagret istället för användarlagret. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) | Beräknar signaturen för det angivna inmatningsvärdet. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) | Beräknar signaturen för det angivna inmatningsvärdet. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) | Beräknar signaturen för det angivna inmatningsvärdet. |
| [SignHash](./signhash/)(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) override | Beräknar signaturen för det specificerade hashvärdet. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Beräknar signaturen för angivet inmatningsvärde. Ej implementerad. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) | Kontrollerar datasignatur. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Kontrollerar datasignatur. |
| [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) override | Verifierar att signaturen för den specificerade hash‑värdet är giltig. |
## Se även

* Class [RSA](../rsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
