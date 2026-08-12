---
title: "Aspose::Pdf::Text::FontSubstitutionCollection-klass"
linktitle: "FontSubstitutionCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::FontSubstitutionCollection-klass. Representerar en samling av teckensnittssubstitutionsstrategier i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.pdf.text/fontsubstitutioncollection/
---
## FontSubstitutionCollection class


Representerar samlingen av teckensnittbytesstrategier.

```cpp
class FontSubstitutionCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FontSubstitution>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FontSubstitution\>\&) override | Lägger till ett nytt teckensnittssubstitutionsobjekt i samlingen. |
| [Clear](./clear/)() override | Rensar teckensnittssubstitutionssamlingen. |
| [Contains](./contains/)(const System::SharedPtr\<FontSubstitution\>\&) const override | Bestämmer om ett element finns i samlingen. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FontSubstitution\>\>, int32_t) override | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen. |
| [get_Count](./get_count/)() const override | Hämtar antalet [Font](../font/) objekt‑element som faktiskt finns i samlingen. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator för hela samlingen. |
| [idx_get](./idx_get/)(int32_t) | Hämtar teckensnittselementet på det angivna indexet. |
| [Remove](./remove/)(const System::SharedPtr\<FontSubstitution\>\&) override | Tar bort teckensnittssubstitutionselementet. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
