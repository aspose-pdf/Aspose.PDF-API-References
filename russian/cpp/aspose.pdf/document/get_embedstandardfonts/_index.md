---
title: "метод Aspose::Pdf::Document::get_EmbedStandardFonts"
linktitle: "get_EmbedStandardFonts"
second_title: "Справочник API Aspose.PDF для C++"
description: "метод Aspose::Pdf::Document::get_EmbedStandardFonts. Свойство, которое указывает, что документ должен встраивать все стандартные шрифты Type1, у которых флаг IsEmbedded установлен в true. Все шрифты PDF могут быть встроены в документ простым установлением флага IsEmbedded в true, но стандартные шрифты PDF Type1 являются исключением из этого правила. Встраивание стандартных шрифтов Type1 требует много времени, поэтому для встраивания этих шрифтов необходимо не только установить флаг IsEmbedded в true для указанного шрифта, но и установить дополнительный флаг на уровне документа — EmbedStandardFonts = true; Это свойство можно установить только один раз для всех шрифтов. По умолчанию false в C++."
type: docs
weight: 2700
url: /ru/cpp/aspose.pdf/document/get_embedstandardfonts/
---
## Document::get_EmbedStandardFonts method


Свойство, которое объявляет, что документ должен встраивать все стандартные шрифты Type1, у которых флаг IsEmbedded установлен в true. Все шрифты PDF могут быть встроены в документ просто путем установки флага IsEmbedded в true, но стандартные шрифты PDF Type1 являются исключением из этого правила. Встраивание стандартных шрифтов Type1 требует много времени, поэтому для встраивания этих шрифтов необходимо не только установить флаг IsEmbedded в true для указанного шрифта, но и установить дополнительный флаг на уровне документа — EmbedStandardFonts = true; Это свойство можно задать только один раз для всех шрифтов. По умолчанию false.

```cpp
bool Aspose::Pdf::Document::get_EmbedStandardFonts() const
```

## См. также

* Class [Document](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
