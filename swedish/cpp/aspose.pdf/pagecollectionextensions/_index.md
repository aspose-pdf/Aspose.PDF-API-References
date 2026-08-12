---
title: "Aspose::Pdf::PageCollectionExtensions klass"
linktitle: "PageCollectionExtensions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PageCollectionExtensions klass. Representerar förlängningsmetoden för att uppdatera sidhuvud- och sidfotspaginering i C++."
type: docs
weight: 13300
url: /sv/cpp/aspose.pdf/pagecollectionextensions/
---
## PageCollectionExtensions class


Representerar förlängningsmetoden för att uppdatera sidhuvud- och sidfotspaginering.

```cpp
class PageCollectionExtensions
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static [AddBatesNumbering](./addbatesnumbering/)(const System::SharedPtr\<PageCollection\>\&, System::Action\<System::SharedPtr\<BatesNArtifact\>\>) | Lägger till Bates-numrering på varje sida i den angivna sidkollektionen med den specificerade åtgärden för att konfigurera [BatesNArtifact](../batesnartifact/). |
| static [AddBatesNumbering](./addbatesnumbering/)(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<BatesNArtifact\>\&) | Lägger till det angivna Bates-numreringsartefaktet till varje sida i den givna sidkollektionen. |
| static [AddPagination](./addpagination/)(const System::SharedPtr\<PageCollection\>\&, const System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<PaginationArtifact\>\>\>\&) | Lägger till de angivna pagineringsartefakterna till varje sida i den givna sidkollektionen. |
| static [DeleteBatesNumbering](./deletebatesnumbering/)(const System::SharedPtr\<PageCollection\>\&) | Tar bort alla Bates-numreringsartefakter från varje sida i den givna sidkollektionen. |
| [PageCollectionExtensions](./pagecollectionextensions/)() |  |
| static [UpdatePagination](./updatepagination/)(const System::SharedPtr\<PageCollection\>\&) | Uppdaterar sidhuvudets och sidfotens sidnummer och datum för alla sidor. Detta fungerar om dokumentet har minst ett pagineringsartefakt med speciella inställningsdata. Alla sidor i samlingen kommer att uppdateras med källartefakten enligt dess inställningar. |
## Se även

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
