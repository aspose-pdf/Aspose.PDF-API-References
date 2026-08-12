---
title: "System::Security::Cryptography::DSACryptoServiceProvider klass"
linktitle: "DSACryptoServiceProvider"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::DSACryptoServiceProvider klass. DSA-algoritm i CSP-form. Objekt av denna klass bör endast allokeras med System::MakeObject() funktion. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system.security.cryptography/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider class


[DSA](../dsa/) algorithm in CSP form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class DSACryptoServiceProvider : public System::Security::Cryptography::DSA,
                                 public System::Security::Cryptography::ICspAsymmetricAlgorithm
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CreateSignature](./createsignature/)(ByteArrayPtr) override | Skapa [DSA](../dsa/) signatur för den angivna datan. |
| [Dispose](./dispose/)() override | Frigör data associerad med objektet. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)() | Konstruktor. Använder standardparametrar. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const DSAParameters\&) | Konstruktor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(const SharedPtr\<CspParameters\>\&) | Konstruktor. Ej implementerad. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t) | Konstruktor. |
| [DSACryptoServiceProvider](./dsacryptoserviceprovider/)(int32_t, const SharedPtr\<CspParameters\>\&) | Konstruktor. Ej implementerad. |
| [ExportCspBlob](./exportcspblob/)(bool) override | Exporterar blob med information om nyckeln. Ej implementerad. |
| [ExportParameters](./exportparameters/)(bool) override | Exporterar CSP-parametrar. |
| [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() override | Hämtar ett [CspKeyContainerInfo](../cspkeycontainerinfo/)‑objekt. |
| [get_KeyExchangeAlgorithm](./get_keyexchangealgorithm/)() override | Kontrollerar nyckelutbytesalgoritmen som är associerad med objektet. |
| [get_KeySize](./get_keysize/)() override | Hämtar nyckelstorlek. |
| [get_PersistKeyInCsp](./get_persistkeyincsp/)() const | Kontrollerar om nyckeln är beständig i CSP‑objektet. |
| [get_PublicOnly](./get_publiconly/)() const | Kontrollerar om endast den offentliga nyckeln finns i CSP‑objektet. |
| [get_SignatureAlgorithm](./get_signaturealgorithm/)() override | Hämtar signaturalgoritm att använda. |
| static [get_UseMachineKeyStore](./get_usemachinekeystore/)() | Kontrollerar om nyckeln är beständig i maskinlagret istället för användarlagret. |
| [ImportCspBlob](./importcspblob/)(ByteArrayPtr) override | Importerar blob med information om nyckeln. Ej implementerad. |
| [ImportParameters](./importparameters/)(DSAParameters) override | Importerar alla parametrar från datastrukturen. |
| [set_PersistKeyInCsp](./set_persistkeyincsp/)(bool) | Definierar om nyckeln är beständig i CSP‑objektet. |
| static [set_UseMachineKeyStore](./set_usemachinekeystore/)(bool) | Definierar om nyckeln är beständig i maskinlagret istället för användarlagret. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Beräknar signaturen för det angivna inmatningsvärdet. |
| [SignData](./signdata/)(const SharedPtr\<IO::Stream\>\&) | Beräknar signaturen för det angivna inmatningsvärdet. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Beräknar signaturen för det angivna inmatningsvärdet. |
| [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | RTTI-information. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | RTTI-information. |
| [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | RTTI-information. |
| [SignHash](./signhash/)(const ByteArrayPtr\&, const String\&) | Beräknar signaturen för det angivna inmatningsvärdet. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Kontrollerar datasignatur. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna binära strömmen är giltig. |
| [VerifyHash](./verifyhash/)(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) | Kontrollerar datasignatur. |
| [VerifySignature](./verifysignature/)(ByteArrayPtr, ByteArrayPtr) override | Verifiera [DSA](../dsa/)‑signatur för den angivna datan. |
## Se även

* Class [DSA](../dsa/)
* Class [ICspAsymmetricAlgorithm](../icspasymmetricalgorithm/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
