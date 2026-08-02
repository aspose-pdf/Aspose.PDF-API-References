---
title: "Интерфейс IFontOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Интерфейс Aspose.Pdf.Text.IFontOptions. Полезные свойства для настройки поведения шрифта"
type: docs
weight: 10790
url: /ru/net/aspose.pdf.text/ifontoptions/
---
## IFontOptions interface

Полезные свойства для настройки поведения шрифта

```csharp
public interface IFontOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Иногда невозможно встроить требуемый шрифт в документ. Существует множество причин, например ограничения лицензии или отсутствие требуемого шрифта на целевом компьютере. В такой ситуации его трудно обнаружить, поскольку требуемый шрифт встраивается с помощью флага свойства Font.IsEmbedded = true; Конечно, можно прочитать это свойство сразу после установки, но такой подход неудобен. Флаг NotifyAboutFontEmbeddingError вводит механизм исключений для случаев, когда попытка встроить шрифт завершилась неудачей. Если этот флаг установлен, будет выброшено исключение типа [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/). По умолчанию false. |

### См. также

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


