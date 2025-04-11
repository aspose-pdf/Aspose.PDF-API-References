---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: Свойство документа. Получает или устанавливает коллекцию страниц документа. Обратите внимание, что страницы нумеруются с 1 в коллекции
type: docs
weight: 470
url: /ru/net/aspose.pdf/document/pages/
---
## Свойство Document.Pages

Получает или устанавливает коллекцию страниц документа. Обратите внимание, что страницы нумеруются с 1 в коллекции.

```csharp
public PageCollection Pages { get; }
```

## Примеры

Пример ниже демонстрирует, как работать со страницами документа: как получить количество страниц и как получить прямоугольник начальной страницы документа.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### См. также

* класс [PageCollection](../../pagecollection/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)