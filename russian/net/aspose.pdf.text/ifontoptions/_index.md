---
title: Interface IFontOptions
second_title: Aspose.PDF for .NET API Reference
description: Интерфейс Aspose.Pdf.Text.IFontOptions. Полезные свойства для настройки поведения шрифта
type: docs
weight: 10610
url: /ru/net/aspose.pdf.text/ifontoptions/
---
## Интерфейс IFontOptions

Полезные свойства для настройки поведения шрифта

```csharp
public interface IFontOptions
```

## Свойства

| Имя | Описание |
| --- | --- |
| [NotifyAboutFontEmbeddingError](../../aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/) { get; set; } | Иногда невозможно встроить желаемый шрифт в документ. Существует множество причин, например, ограничения лицензии или когда желаемый шрифт не найден на целевом компьютере. Когда возникает такая ситуация, это не просто обнаружить, потому что желаемый шрифт встраивается через набор свойств флага Font.IsEmbedded = true; Конечно, можно прочитать это свойство сразу после его установки, но это неудобный подход. Флаг NotifyAboutFontEmbeddingError обеспечивает механизм исключений для случаев, когда попытка встроить шрифт не удалась. Если этот флаг установлен, будет выброшено исключение типа [`FontEmbeddingException`](../../aspose.pdf/fontembeddingexception/). По умолчанию false. |

### См. также

* пространство имен [Aspose.Pdf.Text](../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../)