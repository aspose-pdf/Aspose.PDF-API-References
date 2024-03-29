---
title: Pages
second_title: Aspose.PDF для справочника API .NET
description: Получает или задает коллекцию страниц документа. Обратите внимание что страницы в коллекции нумеруются с 1.
type: docs
weight: 450
url: /ru/net/aspose.pdf/document/pages/
---
## Document.Pages property

Получает или задает коллекцию страниц документа. Обратите внимание, что страницы в коллекции нумеруются с 1.

```csharp
public PageCollection Pages { get; }
```

### Примеры

Пример ниже демонстрирует, как работать со страницами документа: Как получить количество страниц и как получить прямоугольник начальной страницы документа.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### Смотрите также

* class [PageCollection](../../pagecollection)
* class [Document](../../document)
* пространство имен [Aspose.Pdf](../../document)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
