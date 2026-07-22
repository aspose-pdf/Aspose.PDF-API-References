---
title: "System::Security::Cryptography::FromBase64Transform class"
linktitle: "FromBase64Transform"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::FromBase64Transform class. Konverterar CryptoStream‑klassens instans från base64. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 1500
url: /sv/cpp/system.security.cryptography/frombase64transform/
---
## FromBase64Transform class


Konverterar [CryptoStream](../cryptostream/) klassens instans från base64. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class FromBase64Transform : public System::Security::Cryptography::ICryptoTransform
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clear](./clear/)() | Frigör alla resurser. |
| [Dispose](./dispose/)() | Frigör operativsystemets resurser som erhållits av det aktuella objektet. |
| [FromBase64Transform](./frombase64transform/)() | Konstruktor. |
| [FromBase64Transform](./frombase64transform/)(FromBase64TransformMode) | Konstruktor. |
| virtual [get_CanReuseTransform](./get_canreusetransform/)() | Hämtar ett värde som indikerar om den aktuella transformen kan återanvändas. |
| [get_CanTransformMultipleBlocks](./get_cantransformmultipleblocks/)() | Hämtar ett värde som indikerar om flera block kan transformeras. |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Inmatningsblockstorlek. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Utmatningsblockstorlek. |
| [TransformBlock](./transformblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) |  |
| [TransformFinalBlock](./transformfinalblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) |  |
| virtual [~FromBase64Transform](./~frombase64transform/)() | Destruktor. |
## Se även

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
