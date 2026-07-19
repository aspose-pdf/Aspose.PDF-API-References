---
title: "Aspose::Pdf::HtmlSaveOptions::get_FontSources метод"
linktitle: "get_FontSources"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::HtmlSaveOptions::get_FontSources метод. Источники предсохранённых шрифтов в C++."
type: docs
weight: 1100
url: /ru/cpp/aspose.pdf/htmlsaveoptions/get_fontsources/
---
## HtmlSaveOptions::get_FontSources method


Источники шрифтов предварительно сохранённых шрифтов.

```cpp
System::SharedPtr<Text::FontSourceCollection> Aspose::Pdf::HtmlSaveOptions::get_FontSources() const
```

## Примечания


Шрифты могут быть предварительно сохранены в целях кэширования, а затем переданы в процесс конвертации HTML. Например, это может быть полезно при разбиении документа и обработке страниц документа в нескольких потоках с единственным набором шрифтов.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FontSourceCollection](../../../aspose.pdf.text/fontsourcecollection/)
* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
