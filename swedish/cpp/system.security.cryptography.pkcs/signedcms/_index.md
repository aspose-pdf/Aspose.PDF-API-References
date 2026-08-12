---
title: "System::Security::Cryptography::Pkcs::SignedCms klass"
linktitle: "SignedCms"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::Pkcs::SignedCms klass. Signerar innehåll enligt CMS/PKCS #7‑standarden. Ej implementerad. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.security.cryptography.pkcs/signedcms/
---
## SignedCms class


Signerar innehåll enligt CMS/PKCS #7‑standarden. Ej implementerad. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class SignedCms : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [ComputeSignature](./computesignature/)(const SharedPtr\<CmsSigner\>\&, bool) | Skapar en signatur. |
| [Encode](./encode/)() | Kodar CMS/PKCS #7‑meddelande. |
| [SignedCms](./signedcms/)(const SharedPtr\<ContentInfo\>\&, bool) | Konstruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography::Pkcs](../)
* Library [Aspose.PDF for C++](../../)
