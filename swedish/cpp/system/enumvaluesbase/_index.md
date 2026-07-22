---
title: "System::EnumValuesBase‑klass"
linktitle: "EnumValuesBase"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::EnumValuesBase klass. En basklass för en klass som representerar metainformation om uppräkningstyp i C++."
type: docs
weight: 2500
url: /sv/cpp/system/enumvaluesbase/
---
## EnumValuesBase class


En basklass för en klass som representerar metainformation om en uppräkningstyp.

```cpp
class EnumValuesBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [GetNames](./getnames/)(const TypeInfo\&) | Hämtar en array med namnen på konstanterna i en specificerad uppräkning. |
| static [GetUnderlyingType](./getunderlyingtype/)(const TypeInfo\&) | Returnerar den underliggande typen för den specificerade uppräkningen. |
| static [GetValues](./getvalues/)(const TypeInfo\&) | Returnerar en array som innehåller alla värden för den specificerade uppräkningstypen. |
| static [Parse](./parse/)(const TypeInfo\&, const String\&, bool) | Returnerar ett objekt som representerar ett värde för uppräkningskonstanten av den specificerade uppräkningstypen med det specificerade namnet. |
| static [ToObject](./toobject/)(const TypeInfo\&, uint64_t) | Konverterar det specificerade 64‑bitars osignerade heltalsvärdet till en uppräkningsmedlem. |
| static [ToObject](./toobject/)(const TypeInfo\&, const SharedPtr\<Object\>\&) | Konverterar det specificerade objektet med ett heltalsvärde till en uppräkningsmedlem. |
## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
