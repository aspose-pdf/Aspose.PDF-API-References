---
title: "Aspose::Pdf::Text::FontSourceCollection-klass"
linktitle: "FontSourceCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::FontSourceCollection-klass. Representerar en samling av teckensnittskällor i C++."
type: docs
weight: 1400
url: /sv/cpp/aspose.pdf.text/fontsourcecollection/
---
## FontSourceCollection class


Representerar samlingen av teckensnittskällor.

```cpp
class FontSourceCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FontSource>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FontSource\>\&) override | Lägger till ett nytt teckensnittskällobjekt i samlingen. |
| [Clear](./clear/)() override | Rensar teckensnittskällsamlingen. |
| [Contains](./contains/)(const System::SharedPtr\<FontSource\>\&) const override | Bestämmer om ett element finns i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FontSource\>\>, int32_t) override | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [Delete](./delete/)(const System::SharedPtr\<FontSource\>\&) | Tar bort teckensnittskällelementet. |
| [get_Count](./get_count/)() const override | Hämtar antalet [Font](../font/) objekt‑element som faktiskt finns i samlingen. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för hela samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar teckensnittselementet på det angivna indexet. |
| [Remove](./remove/)(const System::SharedPtr\<FontSource\>\&) override | Tar bort teckensnittskällelementet. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
