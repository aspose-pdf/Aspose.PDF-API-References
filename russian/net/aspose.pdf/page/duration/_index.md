---
title: "Page.Duration"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Page. Получает или задает длительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации. Возвращает 1, если длительность не определена."
type: docs
weight: 110
url: /ru/net/aspose.pdf/page/duration/
---
## Page.Duration property

Получает или задает длительность отображения страницы. Это время в секундах, в течение которого страница должна отображаться во время презентации. Возвращает -1, если длительность не определена.

```csharp
public double Duration { get; set; }
```

## Примеры

Пример демонстрирует, как получить длительность страницы

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### См. также

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


