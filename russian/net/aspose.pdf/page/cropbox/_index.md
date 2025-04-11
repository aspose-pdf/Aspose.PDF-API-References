---
title: Page.CropBox
second_title: Aspose.PDF for .NET API Reference
description: Свойство страницы. Получает или устанавливает обрезной прямоугольник страницы
type: docs
weight: 100
url: /ru/net/aspose.pdf/page/cropbox/
---
## Свойство Page.CropBox

Получает или устанавливает обрезной прямоугольник страницы.

```csharp
public Rectangle CropBox { get; set; }
```

## Примеры

Пример демонстрирует, как получить обрезной прямоугольник страницы:

```csharp
Document document = new Document("sample.pdf");
Rectangle cropBox = document.Pages[1].CropBox;
```

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)