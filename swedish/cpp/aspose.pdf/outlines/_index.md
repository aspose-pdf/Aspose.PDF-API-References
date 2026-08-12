---
title: "Aspose::Pdf::Outlines klass"
linktitle: "Outlines"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Outlines klass. Klassen beskriver en samling av konturer i C++."
type: docs
weight: 12700
url: /sv/cpp/aspose.pdf/outlines/
---
## Outlines class


Klassen beskriver en samling av dispositioner.

```cpp
class Outlines : public System::Collections::Generic::ICollection<System::SharedPtr<OutlineItemCollection>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) | Lägger till ett dispositionsobjekt i samlingen. |
| virtual [Clear](./clear/)() | Rensar alla objekt från samlingen. |
| virtual [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const | Kastar alltid NotImplementedException. |
| virtual [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) | Kopierar konturposterna till en [System.Array](../../system/array/), med start vid ett specifikt [System.Array](../../system/array/) index. |
| virtual [get_Count](./get_count/)() const | Hämtar antal. |
| virtual [get_IsReadOnly](./get_isreadonly/)() const | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| virtual [get_VisibleCount](./get_visiblecount/)() | Hämtar det totala antalet innehållsposter på alla nivåer i dokumentets innehållshierarki. |
| virtual [GetEnumerator](./getenumerator/)() | Returnerar en enumerator som itererar genom samlingen. |
| virtual [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) | Ta bort en post i innehållssamlingen. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
