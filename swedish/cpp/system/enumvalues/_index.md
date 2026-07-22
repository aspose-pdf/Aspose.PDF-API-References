---
title: "System::EnumValues klass"
linktitle: "EnumValues"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::EnumValues-klass. Tillhandahåller metainformation om uppräkningskonstanter av uppräkningstypen E i C++."
type: docs
weight: 2400
url: /sv/cpp/system/enumvalues/
---
## EnumValues class


Tillhandahåller metainformation om uppräkningskonstanter för uppräkningstypen **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```


| Parameter | Beskrivning |
| --- | --- |
| E | Typen av uppräkning |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [EnumValues](./enumvalues/)() | Skapar en instans. |
| [GetNames](./getnames/)() const override | Returnerar en array som innehåller alla namn på uppräkning **E**. |
| static [GetNames](../enumvaluesbase/getnames/)(const TypeInfo\&) | Hämtar en array med namnen på konstanterna i en specificerad uppräkning. |
| [GetUnderlyingType](./getunderlyingtype/)() const override | Returnerar den underliggande typen för den specificerade uppräkningen. |
| static [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const TypeInfo\&) | Returnerar den underliggande typen för den specificerade uppräkningen. |
| [GetValueOf](./getvalueof/)(const String\&, bool) const override | Returnerar ett inbakat värde för uppräkningskonstanten med det specificerade namnet. |
| [GetValueOf](./getvalueof/)(long) const override | Returnerar ett inbakat värde för uppräkningskonstanten med det specificerade värdet. |
| [GetValues](./getvalues/)() const override | Returnerar en array som innehåller alla värden för uppräkning **E**. |
| static [GetValues](../enumvaluesbase/getvalues/)(const TypeInfo\&) | Returnerar en array som innehåller alla värden för den specificerade uppräkningstypen. |
| static [Parse](../enumvaluesbase/parse/)(const TypeInfo\&, const String\&, bool) | Returnerar ett objekt som representerar ett värde för uppräkningskonstanten av den specificerade uppräkningstypen med det specificerade namnet. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, uint64_t) | Konverterar det specificerade 64‑bitars osignerade heltalsvärdet till en uppräkningsmedlem. |
| static [ToObject](../enumvaluesbase/toobject/)(const TypeInfo\&, const SharedPtr\<Object\>\&) | Konverterar det specificerade objektet med ett heltalsvärde till en uppräkningsmedlem. |
| virtual [~EnumValues](./~enumvalues/)() | Destruktor. |

## Se även

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
