---
title: "Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages method"
linktitle: "get_ExplicitListOfSavedPages"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages method. С помощью этого свойства вы можете явно задать, какие страницы документа должны быть конвертированы. Страницы в этом списке должны иметь нумерацию, начинающуюся с 1. То есть допустимые номера страниц берутся из диапазона (1...[NumberOfPagesInConvertedDocument]). Порядок появления страниц в этом списке не влияет на их порядок в результирующем HTML‑документе — в результирующих страницах они всегда будут располагаться в том порядке, в котором они присутствуют в исходном PDF. Если этот список равен null (как по умолчанию), будут конвертированы все страницы. Если любой номер страницы из этого списка выходит за пределы существующих страниц (1-[amountOfPagesInDocument]), будет выброшено исключение в C++."
type: docs
weight: 800
url: /ru/cpp/aspose.pdf/htmlsaveoptions/get_explicitlistofsavedpages/
---
## HtmlSaveOptions::get_ExplicitListOfSavedPages method


С помощью этого свойства вы можете явно задать, какие страницы документа следует конвертировать. Страницы в этом списке должны иметь нумерацию, начинающуюся с 1. Т.е. допустимые номера страниц должны быть взяты из диапазона (1...[NumberOfPagesInConvertedDocument]). Порядок появления страниц в этом списке не влияет на их порядок в результирующем HTML‑документе(ах) — в результирующих страницах они всегда будут идти в том порядке, в котором они присутствуют в исходном PDF. Если этот список равен null (как по умолчанию), будут конвертированы все страницы. Если любой номер страницы из этого списка выходит за пределы существующих страниц (1-[amountOfPagesInDocument]), будет выброшено исключение.

```cpp
System::ArrayPtr<int32_t> Aspose::Pdf::HtmlSaveOptions::get_ExplicitListOfSavedPages() override
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
