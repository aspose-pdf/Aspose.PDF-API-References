---
title: Rect
second_title: Aspose.PDF для справочника API .NET
description: Получает или задает прямоугольник страницы. Поле обрезки страницы возвращается если указано в противном случае возвращается поле медиа страницы. Обратите внимание что это свойство не учитывает поворот страницы. Чтобы получить прямоугольник страницы с учетом поворота используйте ActualRect.
type: docs
weight: 230
url: /ru/net/aspose.pdf/page/rect/
---
## Page.Rect property

Получает или задает прямоугольник страницы. Поле обрезки страницы возвращается, если указано, в противном случае возвращается поле медиа страницы. Обратите внимание, что это свойство не учитывает поворот страницы. Чтобы получить прямоугольник страницы с учетом поворота, используйте ActualRect.

```csharp
public Rectangle Rect { get; set; }
```

### Примеры

Пример демонстрирует, как получить прямоугольник страницы:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### Смотрите также

* class [Rectangle](../../rectangle)
* class [Page](../../page)
* пространство имен [Aspose.Pdf](../../page)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->