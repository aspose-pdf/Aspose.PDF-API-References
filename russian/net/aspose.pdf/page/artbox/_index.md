---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: Свойство страницы. Получает или устанавливает арт-бокс страницы
type: docs
weight: 30
url: /ru/net/aspose.pdf/page/artbox/
---
## Свойство Page.ArtBox

Получает или устанавливает арт-бокс страницы.

```csharp
public Rectangle ArtBox { get; set; }
```

## Примеры

Пример демонстрирует, как получить арт-бокс страницы:

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)