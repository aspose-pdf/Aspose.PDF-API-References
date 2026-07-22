---
title: "System::Security::Cryptography::ToBase64Transform class"
linktitle: "ToBase64Transform"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Security::Cryptography::ToBase64Transform class. Konverterar CryptoStream‑klassens instans till base64. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 5000
url: /sv/cpp/system.security.cryptography/tobase64transform/
---
## ToBase64Transform class


Konverterar [CryptoStream](../cryptostream/) klassinstans till base 64. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class ToBase64Transform : public System::Security::Cryptography::ICryptoTransform
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clear](./clear/)() | Frigör alla resurser. |
| [Dispose](./dispose/)() | Frigör operativsystemets resurser som erhållits av det aktuella objektet. |
| virtual [get_CanReuseTransform](./get_canreusetransform/)() | Hämtar ett värde som indikerar om den aktuella transformen kan återanvändas. |
| [get_CanTransformMultipleBlocks](./get_cantransformmultipleblocks/)() | Hämtar ett värde som indikerar om flera block kan transformeras. |
| virtual [get_InputBlockSize](./get_inputblocksize/)() | Inmatningsblockstorlek. |
| virtual [get_OutputBlockSize](./get_outputblocksize/)() | Utmatningsblockstorlek. |
| [TransformBlock](./transformblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) | Bearbetar ett datablok och kopierar data till utmatningsarrayen. |
| [TransformFinalBlock](./transformfinalblock/)(System::ArrayPtr\<uint8_t\>, int32_t, int32_t) | Behandlar sista datablocket och beräknar utdatavärdet. |
| virtual [~ToBase64Transform](./~tobase64transform/)() | Destruktor. |
## Se även

* Class [ICryptoTransform](../icryptotransform/)
* Namespace [System::Security::Cryptography](../)
* Library [Aspose.PDF for C++](../../)
