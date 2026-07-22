---
title: "System::BoxedValue-klass"
linktitle: "BoxedValue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::BoxedValue-klass. Representerar ett inramat värde. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 900
url: /sv/cpp/system/boxedvalue/
---
## BoxedValue class


Representerar ett inramat värde. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<class T>class BoxedValue : public System::BoxedValueBase,
                                    public std::conditional_t<BoxedValueDetail::ImplementsInterface_v<T, IComparable<T>>, BoxedValueDetail::Comparable<T, BoxedValue<T>>, BoxedValueDetail::NonComparable>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av det inramade värdet som representeras av klassen |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BoxedValue](./boxedvalue/)(const T\&) | Skapar ett objekt som representerar det angivna värdet inramat. |
| [Equals](./equals/)(ptr) override | Bestämmer likheten mellan de inramade värdena som representeras av det aktuella och det angivna objektet. |
| [GetHashCode](./gethashcode/)() const override | Returnerar en hashkod för det aktuella objektet. |
| [GetType](./gettype/)() const override | Hämtar det faktiska objektets typ. |
| [GetTypeCode](./gettypecode/)() const override | Returnerar värdet som representerar typen av det inramade värdet som representeras av det aktuella objektet. |
| [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const override | Returnerar numeriskt värde av det inramade objektet om det kan kastas, annars noll. |
| [is](./is/)() const | Bestämmer om typen av det inramade värdet som representeras av det aktuella objektet är **V**. |
| [IsBoxedEnum](./isboxedenum/)() override | Bestämmer om det aktuella objektet representerar ett inramat värde av enum-typ. |
| static [Parse](../boxedvaluebase/parse/)(const TypeInfo\&, const String\&, bool) | Inramar värdet av en uppräkningskonstant från den angivna uppräkningen med det angivna namnet. En parameter anger om skiftläget ska ignoreras vid tolkning av strängen som specificerar namnet på uppräkningskonstanten. |
| static [Parse](../boxedvaluebase/parse/)(const TypeInfo\&, const String\&) | Inramar värdet av en uppräkningskonstant från den angivna uppräkningen med det angivna namnet. |
| [ToString](./tostring/)() const override | Konverterar det inramade värdet som representeras av det aktuella objektet till en sträng. |
| [ToString](../boxedvaluebase/tostring/)(const System::String\&) const | Konverterar det inramade objektet till en sträng med angiven formatsträng. |
| [unbox](./unbox/)() const | Avramar värdet som representeras av det aktuella objektet. |

## Se även

* Class [BoxedValueBase](../boxedvaluebase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
