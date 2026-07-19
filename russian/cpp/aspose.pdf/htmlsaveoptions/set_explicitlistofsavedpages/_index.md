---
title: "Метод Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages"
linktitle: "set_ExplicitListOfSavedPages"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages метод. С помощью этого свойства вы можете явно задать, какие страницы документа должны быть конвертированы. Номера страниц в этом списке должны быть 1‑based, т.е. допустимые номера страниц берутся из диапазона (1...[NumberOfPagesInConvertedDocument]). Порядок появления страниц в этом списке не влияет на их порядок в результирующем HTML‑файле(ах) — в результатных страницах они всегда будут располагаться в том порядке, в котором находятся в исходном PDF. Если список равен null (по умолчанию), будут конвертированы все страницы. Если какой‑либо номер страницы из списка выходит за пределы существующих страниц (1-[amountOfPagesInDocument]), в C++ будет выброшено исключение."
type: docs
weight: 3100
url: /ru/cpp/aspose.pdf/htmlsaveoptions/set_explicitlistofsavedpages/
---
## HtmlSaveOptions::set_ExplicitListOfSavedPages method


С помощью этого свойства вы можете явно задать, какие страницы документа следует конвертировать. Страницы в этом списке должны иметь нумерацию, начинающуюся с 1. Т.е. допустимые номера страниц должны быть взяты из диапазона (1...[NumberOfPagesInConvertedDocument]). Порядок появления страниц в этом списке не влияет на их порядок в результирующем HTML‑документе(ах) — в результирующих страницах они всегда будут идти в том порядке, в котором они присутствуют в исходном PDF. Если этот список равен null (как по умолчанию), будут конвертированы все страницы. Если любой номер страницы из этого списка выходит за пределы существующих страниц (1-[amountOfPagesInDocument]), будет выброшено исключение.

```cpp
void Aspose::Pdf::HtmlSaveOptions::set_ExplicitListOfSavedPages(System::ArrayPtr<int32_t> value) override
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
