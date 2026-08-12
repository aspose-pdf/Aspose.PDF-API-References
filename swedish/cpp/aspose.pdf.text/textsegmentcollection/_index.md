---
title: "Aspose::Pdf::Text::TextSegmentCollection klass"
linktitle: "TextSegmentCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextSegmentCollection klass. Representerar en samling av textsegment i C++."
type: docs
weight: 5200
url: /sv/cpp/aspose.pdf.text/textsegmentcollection/
---
## TextSegmentCollection class


Representerar en samling av textsegment.

```cpp
class TextSegmentCollection : public System::Collections::Generic::ICollection<System::SharedPtr<TextSegment>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<TextSegment\>\&) override | Lägger till textsegmentelementet på det angivna indexet. |
| [Clear](./clear/)() override | Rensar alla objekt från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<TextSegment\>\&) const override | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<TextSegment\>\>, int32_t) override | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [get_Count](./get_count/)() const override | Hämtar antalet [TextSegment](../textsegment/) objekt‑element som faktiskt finns i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för hela samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar textsegmentelementet på det angivna indexet. |
| [Remove](./remove/)(const System::SharedPtr\<TextSegment\>\&) override | Tar bort angivet objekt från samlingen. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
