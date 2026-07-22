---
title: "Aspose::Pdf::OutlineCollection klass"
linktitle: "OutlineCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OutlineCollection klass. Representerar dokumentets dispositionshierarki i C++."
type: docs
weight: 12500
url: /sv/cpp/aspose.pdf/outlinecollection/
---
## OutlineCollection class


Representerar dokumentets dispositionshierarki.

```cpp
class OutlineCollection : public Aspose::Pdf::Outlines
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Lägger till ett dispositionsobjekt i samlingen. |
| [Clear](./clear/)() override | Rensar alla objekt från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<OutlineItemCollection\>\&) const override | Kontrollerar om samlingen innehåller det angivna objektet. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\>, int32_t) override | Kopierar dispositionsobjekten till en [System.Array](../../system/array/), med start vid ett specifikt [System.Array](../../system/array/) index. |
| [Delete](./delete/)() | Tar bort alla dispositionsobjekt från dokumentets disposition. |
| [Delete](./delete/)(const System::String\&) | Tar bort dispositionsobjektet med angiven titel från dokumentets disposition. |
| [get_Count](./get_count/)() const override | Antal objekt i samlingen. Vänligen förväxla inte med VisibleCount: VisibleCount ger antalet synliga dispositionsobjekt på alla nivåer. |
| [get_First](./get_first/)() const | Hämtar ett dispositionsobjekt som representerar det första toppnivåobjektet i dispositionen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [get_Last](./get_last/)() | Hämtar ett dispositionsobjekt som representerar det sista toppnivåobjektet i dispositionen. |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling. |
| [get_VisibleCount](./get_visiblecount/)() override | Antal är summan av antalet synliga underordnade dispositionsobjekt på alla nivåer. [Note](../note/): vänligen förväxla inte med Count som är antalet objekt i samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar dispositionsobjekt från samlingen efter index. |
| [Remove](./remove/)(const System::SharedPtr\<OutlineItemCollection\>\&) override | Kastar alltid NotImplementedException |
| [Remove](./remove/)(int32_t) | Ta bort objekt efter index. |
## Se även

* Class [Outlines](../outlines/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
