---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: Свойство страницы. Получает или устанавливает продолжительность отображения страницы. Это время в секундах, в течение которого страница будет отображаться во время презентации. Возвращает 1, если продолжительность не определена
type: docs
weight: 110
url: /ru/net/aspose.pdf/page/duration/
---
## Свойство Page.Duration

Получает или устанавливает продолжительность отображения страницы. Это время в секундах, в течение которого страница будет отображаться во время презентации. Возвращает -1, если продолжительность не определена.

```csharp
public double Duration { get; set; }
```

## Примеры

Пример демонстрирует, как получить продолжительность страницы

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### См. также

* класс [Page](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)