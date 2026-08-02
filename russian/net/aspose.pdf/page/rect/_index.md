---
title: "Page.Rect"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Page. Получает или задает прямоугольник страницы. При получении возвращается crop‑box страницы, если он указан, иначе возвращается media‑box. При установке всегда задаётся media‑box. Обратите внимание, что это свойство не учитывает поворот страницы. Чтобы получить прямоугольник страницы с учётом поворота, используйте ActualRect."
type: docs
weight: 230
url: /ru/net/aspose.pdf/page/rect/
---
## Page.Rect property

Получает или задает прямоугольник страницы. При получении возвращается crop‑box страницы, если он указан, иначе возвращается media‑box. При установке всегда задаётся media‑box. Обратите внимание, что это свойство не учитывает поворот страницы. Чтобы получить прямоугольник страницы с учётом поворота, используйте ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

## Примеры

Пример демонстрирует, как получить прямоугольник страницы:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### См. также

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


