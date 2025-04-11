---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: Свойство страницы. Получает или устанавливает обрезной прямоугольник страницы
type: docs
weight: 290
url: /ru/net/aspose.pdf/page/trimbox/
---
## Свойство Page.TrimBox

Получает или устанавливает обрезной прямоугольник страницы.

```csharp
public Rectangle TrimBox { get; set; }
```

## Примеры

Пример демонстрирует, как получить обрезной прямоугольник страницы:

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)