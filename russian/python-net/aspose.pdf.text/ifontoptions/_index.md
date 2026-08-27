---
title: "IFontOptions"
second_title: "Aspose.PDF for Python via .NET справочник API"
description: "Полезные свойства для настройки поведения шрифта"
type: docs
weight: 180
url: /ru/python-net/aspose.pdf.text/ifontoptions/
---

## IFontOptions class

Полезные свойства для настройки поведения шрифта

Тип IFontOptions раскрывает следующие члены:
## Свойства
| Имя | Описание |
| :- | :- |
| notify_about_font_embedding_error | Иногда невозможно встроить требуемый шрифт в документ. Существует множество причин, например<br/>            ограничения лицензии или отсутствие требуемого шрифта на целевом компьютере.<br/>            Когда возникает такая ситуация, её не так просто обнаружить, потому что шрифт встраивается через установку <br/>            флага свойства Font.IsEmbedded = true; Конечно, можно прочитать это свойство сразу после его установки, но<br/>            это неудобный подход. Флаг NotifyAboutFontEmbeddingError вводит механизм исключения <br/>            для случаев, когда попытка встроить шрифт завершилась неудачей. Если этот флаг установлен, будет выброшено исключение типа<br/>            [FontEmbeddingException](/pdf/python-net/aspose.pdf/fontembeddingexception/). По умолчанию false. |

### См. также

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

