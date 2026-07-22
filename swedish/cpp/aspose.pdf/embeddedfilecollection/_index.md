---
title: "Aspose::Pdf::EmbeddedFileCollection klass"
linktitle: "EmbeddedFileCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::EmbeddedFileCollection klass. Klass som representerar en samling av inbäddade filer i C++."
type: docs
weight: 4300
url: /sv/cpp/aspose.pdf/embeddedfilecollection/
---
## EmbeddedFileCollection class


Klass som representerar samling av inbäddade filer.

```cpp
class EmbeddedFileCollection : public System::Collections::Generic::ICollection<System::SharedPtr<FileSpecification>>
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<FileSpecification\>\&) override | Lägger till specifikation för inbäddad fil i samlingen. |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<FileSpecification\>\&) | Lägger till fil i inbäddade filer med den angivna nyckeln. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<FileSpecification\>\>, int32_t) override | Kopierar en array av [FileSpecification](../filespecification/) objekt till samlingen. |
| [Delete](./delete/)(const System::String\&) | Ta bort inbäddad fil efter namn. |
| [Delete](./delete/)() | Ta bort alla inbäddade filer från dokumentet. |
| [DeleteByKey](./deletebykey/)(const System::String\&) | Raderar fil från samlingen efter dess nyckel i samlingen. |
| [FindByName](./findbyname/)(const System::String\&) | Returnerar inbäddad fil efter dess namn. |
| [get_Count](./get_count/)() const override | Hämtar antalet inbäddade filer i samlingen. |
| [get_IsSynchronized](./get_issynchronized/)() | Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [get_Keys](./get_keys/)() | Returnerar en lista med nycklar för filbilagor. |
| [get_SyncRoot](./get_syncroot/)() const | Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en samlingsenumerator. |
| [idx_get](./idx_get/)(int32_t) | Hämtar inbäddad fil efter dess index. |
| [idx_get](./idx_get/)(const System::String\&) | Hämtar inbäddad fil efter dess namn. |
## Se även

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
