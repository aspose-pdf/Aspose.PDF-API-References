---
title: "System::BoxedValueBase-klass"
linktitle: "BoxedValueBase"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::BoxedValueBase-klass. En basklass som definierar ett gränssnitt och implementerar några grundläggande metoder för en avledd klass som representerar ett inbäddat värde. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 1000
url: /sv/cpp/system/boxedvaluebase/
---
## BoxedValueBase class


En basklass som definierar ett gränssnitt och implementerar några grundläggande metoder för en avledd klass som representerar ett inbäddat värde. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class BoxedValueBase : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetTypeCode](./gettypecode/)() const | Returnerar värdet som representerar typen av det inramade värdet som representeras av det aktuella objektet. |
| virtual [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const | Konverterar den boxed som representeras av det aktuella objektet till ett 64-bitars heltalsvärde. |
| virtual [IsBoxedEnum](./isboxedenum/)() | Bestämmer om det aktuella objektet representerar ett inramat värde av enum-typ. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&, bool) | Inramar värdet av en uppräkningskonstant från den angivna uppräkningen med det angivna namnet. En parameter anger om skiftläget ska ignoreras vid tolkning av strängen som specificerar namnet på uppräkningskonstanten. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&) | Inramar värdet av en uppräkningskonstant från den angivna uppräkningen med det angivna namnet. |
| [ToString](./tostring/)(const System::String\&) const | Konverterar det inramade objektet till en sträng med angiven formatsträng. |
| virtual [ToString](./tostring/)() const | Analog till C#‑metoden [Object.ToString()](../object/tostring/). Möjliggör konvertering av anpassade objekt till sträng. |
## Se även

* Class [Object](../object/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
