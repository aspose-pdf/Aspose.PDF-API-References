---
title: "System::Security::Cryptography::Pkcs::CmsSigner class"
linktitle: "CmsSigner"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::Pkcs::CmsSigner class. Tillhandahåller ett API för att signera objekt med hjälp av CMS. Signerar inte objekt själva, använd SignedCMS-klassen för att göra det. Inte implementerad. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.security.cryptography.pkcs/cmssigner/
---
## CmsSigner class


Tillhandahåller ett API för att signera objekt med CMS. Signerar inte objekt själva, använd SignedCMS-klassen för att göra det. Inte implementerad. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class CmsSigner : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CmsSigner](./cmssigner/)(const SharedPtr\<X509Certificates::X509Certificate2\>\&) | Initierar undertecknare med X509‑certifikat. |
| [get_DigestAlgorithm](./get_digestalgorithm/)() const | Hämtar hash‑algoritm som används med signaturen. |
| [get_IncludeOption](./get_includeoption/)() const | Kontrollerar vilka certifikat från kedjan som kommer att inkluderas i signaturen. |
| [set_DigestAlgorithm](./set_digestalgorithm/)(const SharedPtr\<Oid\>\&) | Ställer in hash‑algoritm som används med signaturen. |
| [set_IncludeOption](./set_includeoption/)(X509Certificates::X509IncludeOption) | Anger vilka certifikat från kedjan som ska inkluderas i signaturen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PDF for C++](../../)
