---
title: "System::Security::Cryptography::ICryptoTransform-klass"
linktitle: "ICryptoTransform"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::ICryptoTransform-klass. Basklass för kryptografisk transformering. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2000
url: /sv/cpp/system.security.cryptography/icryptotransform/
---
## ICryptoTransform class


Basklass för kryptografisk transformering. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ICryptoTransform : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Inmatningsblockstorlek. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Utmatningsblockstorlek. |
| virtual [TransformBlock](./transformblock/)(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) | RTTI-information. |
| virtual [TransformFinalBlock](./transformfinalblock/)(ArrayPtr\<uint8_t\>, int, int) | Behandlar sista datablocket och beräknar utdatavärdet. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
