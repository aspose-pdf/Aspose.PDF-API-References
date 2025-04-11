---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: Свойство страницы. Получает или устанавливает область выреза страницы
type: docs
weight: 70
url: /ru/net/aspose.pdf/page/bleedbox/
---
## Свойство Page.BleedBox

Получает или устанавливает область выреза страницы.

```csharp
public Rectangle BleedBox { get; set; }
```

## Примеры

Пример демонстрирует, как получить область выреза страницы:

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### См. также

* класс [Rectangle](../../rectangle/)
* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)