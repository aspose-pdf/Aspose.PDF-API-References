---
title: "Aspose::Pdf::LoadOptions::ResourceLoadingStrategy typedef"
linktitle: "ResourceLoadingStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LoadOptions::ResourceLoadingStrategy typedef. Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av Aspose.Pdf i molnet är direkt åtkomst till refererade filer omöjlig, och någon anpassad kod som placeras i en speciell metod bör användas. Denna delegat definierar signaturen för en sådan anpassad metod i C++."
type: docs
weight: 700
url: /sv/cpp/aspose.pdf/loadoptions/resourceloadingstrategy/
---
## ResourceLoadingStrategy typedef


Ibland är det nödvändigt att undvika användning av den interna laddaren för externa resurser (som bilder eller CSS-filer) och tillhandahålla en anpassad metod som hämtar de begärda resurserna från någonstans. Till exempel, vid användning av [Aspose.Pdf](../../) i molnet är direkt åtkomst till refererade filer omöjlig, och någon anpassad kod som placeras i en speciell metod bör användas. Denna delegat definierar signaturen för en sådan anpassad metod.

```cpp
using Aspose::Pdf::LoadOptions::ResourceLoadingStrategy =  System::MulticastDelegate<System::SharedPtr<Aspose::Pdf::LoadOptions::ResourceLoadingResult>(const System::String&)>
```


## Se även

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
