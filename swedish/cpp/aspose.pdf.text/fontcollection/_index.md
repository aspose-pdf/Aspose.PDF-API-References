---
title: "Aspose::Pdf::Text::FontCollection-klass"
linktitle: "FontCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::FontCollection-klass. Representerar en teckensnittssamling i C++."
type: docs
weight: 1100
url: /sv/cpp/aspose.pdf.text/fontcollection/
---
## FontCollection class


Representerar teckensnittssamling.

```cpp
class FontCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Font>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<Font\>\&, System::String\&) | Lägger till ett nytt teckensnitt i teckensnittresurserna och returnerar det automatiskt tilldelade namnet på teckensnittresursen. |
| [Contains](./contains/)(const System::String\&) const | Kontrollerar om teckensnittet finns i teckensnittssamlingen. |
| [Contains](./contains/)(const System::SharedPtr\<Font\>\&) const override | Bestämmer om samlingen innehåller ett specifikt värde. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Font\>\>, int32_t) override | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [get_Count](./get_count/)() const override | Hämtar antalet [Font](../font/) objekt‑element som faktiskt finns i samlingen. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för hela samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar teckensnittselementet på det angivna indexet. |
| [idx_get](./idx_get/)(const System::String\&) | Hämtar teckensnittet från samlingen med teckensnittets namn. Ett undantag kastas om teckensnittet inte hittas. |
| [Remove](./remove/)(const System::SharedPtr\<Font\>\&) override | Tar bort angivet objekt från samlingen. |
## Anmärkningar


[Font](../font/) collections represented by [FontCollection](./) class are used in several scenarios. For example, in resources with [Resources::Fonts](../) property. 
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
