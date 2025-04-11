---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: Свойство страницы. Получает или устанавливает медиабокс страницы
type: docs
weight: 180
url: /ru/net/aspose.pdf/page/mediabox/
---
## Свойство Page.MediaBox

Получает или устанавливает медиабокс страницы.

```csharp
public Rectangle MediaBox { get; set; }
```

## Примеры

Пример демонстрирует, как получить медиабокс страницы:

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)