---
title: "Aspose::Pdf::Text::TextFragmentCollection-klass"
linktitle: "TextFragmentCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextFragmentCollection-klass. Representerar en samling av textfragment i C++."
type: docs
weight: 4500
url: /sv/cpp/aspose.pdf.text/textfragmentcollection/
---
## TextFragmentCollection class


Representerar en samling av textfragment.

```cpp
class TextFragmentCollection : public System::Collections::Generic::ICollection<System::SharedPtr<TextFragment>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<TextFragment\>\&) override | Lägger till textfragment‑elementet på det angivna indexet. |
| [Clear](./clear/)() override | Rensar alla objekt från samlingen. |
| [Contains](./contains/)(const System::SharedPtr\<TextFragment\>\&) const override | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<TextFragment\>\>, int32_t) override | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [get_Count](./get_count/)() const override | Hämtar antalet [TextFragment](../textfragment/) objekt‑element som faktiskt finns i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för hela samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar textfragment‑elementet på det angivna indexet. |
| [Remove](./remove/)(const System::SharedPtr\<TextFragment\>\&) override | Tar bort angivet objekt från samlingen och tar även bort det från dokumentet. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
