---
title: "System::Drawing::Imaging::EncoderParameter-klass"
linktitle: "EncoderParameter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Drawing::Imaging::EncoderParameter-klass. Tjänar som en behållare som används för att skicka värden till en bildkodare. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.drawing.imaging/encoderparameter/
---
## EncoderParameter class


Tjänar som en behållare som används för att skicka värden till en bildkodare. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class EncoderParameter : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EncoderParameter](./encoderparameter/)() | Skapar en ny instans av [EncoderParameter](./)‑klass. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, uint8_t, bool) | Skapar en ny instans av [EncoderParameter](./)‑klass. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int16_t) | Skapar en ny instans av [EncoderParameter](./)‑klass. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t) | Skapar en ny instans av [EncoderParameter](./)‑klass. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t) | Skapar en ny instans av [EncoderParameter](./)‑klass. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar ett bråk. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int64_t, int64_t) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar ett intervall av heltalsvärden. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int32_t, int32_t, int32_t, int32_t) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar ett intervall av bråktal. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const String\&) | Skapar en ny instans av [EncoderParameter](./)‑klass. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<uint8_t\>\&, bool) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar en array av värden. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int16_t\>\&) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar en array av värden. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar en array av värden. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar en array av bråktal. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int64_t\>\&, const ArrayPtr\<int64_t\>\&) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar en array av intervall av heltal. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&, const ArrayPtr\<int32_t\>\&) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar en array av intervall av bråktal. |
| [EncoderParameter](./encoderparameter/)(const SharedPtr\<Encoder\>\&, int, EncoderParameterValueType, void *) | Skapar en ny instans av [EncoderParameter](./)‑klass som representerar det angivna antalet värden av den angivna typen som läses från den angivna bufferten. |
| [get_Encoder](./get_encoder/)() const | Returnerar [Encoder](../encoder/)-objektet som är associerat med det aktuella [EncoderParameter](./)-objektet. |
| [get_NumberOfValues](./get_numberofvalues/)() const | Returnerar antalet värden som representeras av det aktuella objektet. |
| [get_Type](./get_type/)() const | Returnerar typen av de värden som representeras av det aktuella objektet. |
| [set_Encoder](./set_encoder/)(const EncoderPtr\&) | Associerar det angivna [Encoder](../encoder/)-objektet med det aktuella [EncoderParameter](./)-objektet. |
| [~EncoderParameter](./~encoderparameter/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Library [Aspose.PDF for C++](../../)
