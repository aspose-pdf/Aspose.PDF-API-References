---
title: "IFontOptions.NotifyAboutFontEmbeddingError"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство IFontOptions. Иногда невозможно встроить требуемый шрифт в документ. Существует множество причин, например ограничения лицензии или отсутствие требуемого шрифта на целевом компьютере. В такой ситуации его трудно обнаружить, потому что шрифт считается встроенным при установленном флаге свойства Font.IsEmbedded = true. Конечно, можно прочитать это свойство сразу после его установки, но это неудобно. Флаг NotifyAboutFontEmbeddingError вводит механизм исключения для случаев, когда попытка встроить шрифт завершается неудачей. Если этот флаг установлен, будет выброшено исключение типа FontEmbeddingException. По умолчанию false."
type: docs
weight: 10
url: /ru/net/aspose.pdf.text/ifontoptions/notifyaboutfontembeddingerror/
---
## IFontOptions.NotifyAboutFontEmbeddingError property

Иногда невозможно встроить требуемый шрифт в документ. Существует множество причин, например ограничения лицензии или отсутствие требуемого шрифта на целевом компьютере. В такой ситуации её трудно обнаружить, потому что шрифт считается встроенным при установленном флаге свойства Font.IsEmbedded = true; Конечно, можно прочитать это свойство сразу после его установки, но это неудобно. Флаг NotifyAboutFontEmbeddingError вводит механизм исключения для случаев, когда попытка встроить шрифт завершается неудачей. Если этот флаг установлен, будет выброшено исключение типа [`FontEmbeddingException`](../../../aspose.pdf/fontembeddingexception/). По умолчанию false.

```csharp
public bool NotifyAboutFontEmbeddingError { get; set; }
```

### См. также

* interface [IFontOptions](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


