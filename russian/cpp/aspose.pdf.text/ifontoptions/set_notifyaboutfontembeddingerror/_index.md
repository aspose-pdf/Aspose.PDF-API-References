---
title: "Метод Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError"
linktitle: "set_NotifyAboutFontEmbeddingError"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError method. Иногда невозможно встроить требуемый шрифт в документ. Существует множество причин, например ограничения лицензии или отсутствие требуемого шрифта на целевом компьютере. Когда возникает такая ситуация, её не так просто обнаружить, поскольку шрифт встраивается с помощью свойства Font.IsEmbedded = true; Конечно, можно прочитать это свойство сразу после установки, но это неудобно. Флаг NotifyAboutFontEmbeddingError вводит механизм исключения для случаев, когда попытка встроить шрифт завершилась неудачей. Если этот флаг установлен, будет выброшено исключение типа Aspose::Pdf::FontEmbeddingException. По умолчанию false в C++."
type: docs
weight: 200
url: /ru/cpp/aspose.pdf.text/ifontoptions/set_notifyaboutfontembeddingerror/
---
## IFontOptions::set_NotifyAboutFontEmbeddingError method


Иногда невозможно встроить требуемый шрифт в документ. Существует множество причин, например ограничения лицензии или отсутствие требуемого шрифта на целевом компьютере. Когда возникает такая ситуация, её не так просто обнаружить, поскольку шрифт встраивается с помощью свойства Font.IsEmbedded = true; Конечно, можно прочитать это свойство сразу после установки, но это неудобно. Флаг NotifyAboutFontEmbeddingError вводит механизм исключения для случаев, когда попытка встроить шрифт завершилась неудачей. Если этот флаг установлен, будет выброшено исключение типа [Aspose::Pdf::FontEmbeddingException](../../../aspose.pdf/fontembeddingexception/) . По умолчанию false.

```cpp
virtual void Aspose::Pdf::Text::IFontOptions::set_NotifyAboutFontEmbeddingError(bool value)=0
```

## См. также

* Class [IFontOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
