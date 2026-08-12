---
title: "Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages metod"
linktitle: "get_ExplicitListOfSavedPages"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages metod. Med denna egenskap kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i denna lista måste ha 1‑baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i denna lista påverkar inte deras ordning i den resulterande HTML‑sidan/-sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll‑PDF‑filen. Om denna lista är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf/htmlsaveoptions/get_explicitlistofsavedpages/
---
## HtmlSaveOptions::get_ExplicitListOfSavedPages method


Med den här egenskapen kan du explicit definiera vilka sidor i dokumentet som ska konverteras. Sidor i den här listan måste ha 1‑baserade nummer. Dvs. giltiga sidnummer måste tas från intervallet (1...[NumberOfPagesInConvertedDocument]). Ordningen på sidorna i listan påverkar inte deras ordning i de resulterande HTML‑sidorna – i resultatet kommer sidorna alltid att visas i den ordning de förekommer i käll‑PDF‑filen. Om listan är null (som standard) konverteras alla sidor. Om något sidnummer i listan ligger utanför intervallet för befintliga sidor (1-[amountOfPagesInDocument]) kastas ett undantag.

```cpp
System::ArrayPtr<int32_t> Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages() override
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
