---
title: IFontOptions.NotifyAboutFontEmbeddingError
second_title: Aspose.PDF for .NET API Reference
description: Свойство IFontOptions. Иногда невозможно встроить желаемый шрифт в документ. Существует множество причин, например, лицензионные ограничения или когда желаемый шрифт не найден на целевом компьютере. Когда возникает такая ситуация, это не просто обнаружить, потому что желаемый шрифт встраивается через набор флага свойства Font.IsEmbedded = true; Конечно, возможно прочитать это свойство сразу после его установки, но это неудобный подход. Флаг NotifyAboutFontEmbeddingError обеспечивает механизм исключений для случаев, когда попытка встроить шрифт не удалась. Если этот флаг установлен, будет выброшено исключение типа [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). По умолчанию false.
type: docs
weight: 10
url: /ru/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## Свойство IFontOptions.NotifyAboutFontEmbeddingError

Иногда невозможно встроить желаемый шрифт в документ. Существует множество причин, например, лицензионные ограничения или когда желаемый шрифт не найден на целевом компьютере. Когда возникает такая ситуация, это не просто обнаружить, потому что желаемый шрифт встраивается через набор флага свойства Font.IsEmbedded = true; Конечно, возможно прочитать это свойство сразу после его установки, но это неудобный подход. Флаг NotifyAboutFontEmbeddingError обеспечивает механизм исключений для случаев, когда попытка встроить шрифт не удалась. Если этот флаг установлен, будет выброшено исключение типа [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). По умолчанию false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### См. также

* интерфейс [IFontOptions](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)