---
title: "System::Security::Cryptography::ECDsaBotan klass"
linktitle: "ECDsaBotan"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::ECDsaBotan klass. ECDsa‑algoritm i Botan‑form. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1400
url: /sv/cpp/system.security.cryptography/ecdsabotan/
---
## ECDsaBotan class


[ECDsa](../ecdsa/) algorithm in Botan form. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ECDsaBotan : public System::Security::Cryptography::ECDsa
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ECDsaBotan](./ecdsabotan/)() | Konstruktor. Använder standardparametrar. |
| [ECDsaBotan](./ecdsabotan/)(const ECParameters\&) | Konstruktor. |
| [ECDsaBotan](./ecdsabotan/)(const ECCurve\&) | Konstruktor. |
| [ECDsaBotan](./ecdsabotan/)(int32_t) | Konstruktor. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PublicKey\&) | Konstruktor. |
| [ECDsaBotan](./ecdsabotan/)(const Botan::ECDSA_PrivateKey\&) | Konstruktor. |
| [ExportExplicitParameters](./exportexplicitparameters/)(bool) override | Exporterar explicita parametrar. |
| [ExportParameters](./exportparameters/)(bool) override | Exporterar namngivna eller explicita parametrar. |
| [FromXmlString](./fromxmlstring/)(String) override | Initierar objekt med XML‑kodade parametrar. Inte implementerad. |
| [FromXmlString](./fromxmlstring/)(const String\&, ECKeyXmlFormat) | Initierar objekt med XML‑kodade parametrar. Inte implementerad. |
| [GenerateKey](./generatekey/)(const ECCurve\&) override | Genererar ett nytt offentligt/privat nyckelpar för den angivna kurvan. |
| [get_HashAlgorithm](./get_hashalgorithm/)() const | Hämtar hash‑algoritm. |
| [HashData](./hashdata/)(ByteArrayPtr, int32_t, int32_t, HashAlgorithmName) override | Beräknar hash‑värdet för den angivna dataarrayen med den angivna hash‑algoritmen. |
| [HashData](./hashdata/)(StreamPtr, HashAlgorithmName) override | Beräknar hashvärdet för den angivna binära strömmen med den angivna hashalgoritmen. |
| [ImportParameters](./importparameters/)(const ECParameters\&) override | Importerar alla parametrar från datastrukturen. |
| [set_HashAlgorithm](./set_hashalgorithm/)(const HashAlgorithmName\&) | Ställer in hashalgoritm. |
| [set_KeySize](./set_keysize/)(int32_t) override | Ställer in nyckelstorlek. |
| [SignData](./signdata/)(const ByteArrayPtr\&) | Beräknar hashvärdet för den angivna dataarrayen och signerar resultatet. |
| [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t) | Beräknar hashvärdet för den angivna dataarrayen och signerar resultatet. |
| [SignData](./signdata/)(const StreamPtr\&) | Beräknar hashvärdet för den angivna binära strömmen och signerar resultatet. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, const HashAlgorithmName\&) | RTTI-information. |
| virtual [SignData](./signdata/)(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) | RTTI-information. |
| virtual [SignData](./signdata/)(const StreamPtr\&, const HashAlgorithmName\&) | RTTI-information. |
| [SignHash](./signhash/)(const ByteArrayPtr\&) override | Beräknar signaturen för det angivna inmatningsvärdet. |
| [ToXmlString](./toxmlstring/)(bool) override | Exporterar alla parametrar i XML-format. Inte implementerad. |
| [ToXmlString](./toxmlstring/)(ECKeyXmlFormat) | Exporterar alla parametrar i XML‑format. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&) | Verifierar att signaturen för den angivna binära strömmen är giltig. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna datan är giltig. |
| [VerifyData](./verifydata/)(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) | Verifierar att signaturen för den angivna binära strömmen är giltig. |
| [VerifyHash](./verifyhash/)(ByteArrayPtr, ByteArrayPtr) override | Kontrollerar datasignatur. |
## Se även

* Class [ECDsa](../ecdsa/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
