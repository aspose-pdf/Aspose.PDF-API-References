---
title: "Aspose::Pdf::Text::IFontOptions класс"
linktitle: "IFontOptions"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::Text::IFontOptions. Полезные свойства для настройки поведения шрифта в C++."
type: docs
weight: 1700
url: /ru/cpp/aspose.pdf.text/ifontoptions/
---
## IFontOptions class


Полезные свойства для настройки поведения [Font](../font/).

```cpp
class IFontOptions : public virtual System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [get_NotifyAboutFontEmbeddingError](./get_notifyaboutfontembeddingerror/)() | Иногда невозможно встроить требуемый шрифт в документ. Существует множество причин, например ограничения лицензии или отсутствие требуемого шрифта на целевом компьютере. В такой ситуации его сложно обнаружить, потому что шрифт встраивается с помощью флага свойства Font.IsEmbedded = true; Конечно, можно прочитать это свойство сразу после установки, но такой подход неудобен. Флаг NotifyAboutFontEmbeddingError вводит механизм исключений для случаев, когда попытка встроить шрифт завершилась неудачей. Если этот флаг установлен, будет выброшено исключение типа [Aspose::Pdf::FontEmbeddingException](../../aspose.pdf/fontembeddingexception/). По умолчанию false. |
| virtual [set_NotifyAboutFontEmbeddingError](./set_notifyaboutfontembeddingerror/)(bool) | Иногда невозможно встроить требуемый шрифт в документ. Существует множество причин, например ограничения лицензии или отсутствие требуемого шрифта на целевом компьютере. В такой ситуации его сложно обнаружить, потому что шрифт встраивается с помощью флага свойства Font.IsEmbedded = true; Конечно, можно прочитать это свойство сразу после установки, но такой подход неудобен. Флаг NotifyAboutFontEmbeddingError вводит механизм исключений для случаев, когда попытка встроить шрифт завершилась неудачей. Если этот флаг установлен, будет выброшено исключение типа [Aspose::Pdf::FontEmbeddingException](../../aspose.pdf/fontembeddingexception/). По умолчанию false. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
