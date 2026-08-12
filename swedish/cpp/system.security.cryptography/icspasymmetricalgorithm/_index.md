---
title: "System::Security::Cryptography::ICspAsymmetricAlgorithm klass"
linktitle: "ICspAsymmetricAlgorithm"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::ICspAsymmetricAlgorithm klass. Bas-klass för asymmetrisk algoritm. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 2100
url: /sv/cpp/system.security.cryptography/icspasymmetricalgorithm/
---
## ICspAsymmetricAlgorithm class


Bas-klass för asymmetrisk algoritm. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class ICspAsymmetricAlgorithm : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [ExportCspBlob](./exportcspblob/)(bool) | Exporterar blob med nyckelinformation. |
| virtual [get_CspKeyContainerInfo](./get_cspkeycontainerinfo/)() | RTTI-information. |
| virtual [ImportCspBlob](./importcspblob/)(ByteArrayPtr) | Importerar nyckelinformation från data-blob. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
