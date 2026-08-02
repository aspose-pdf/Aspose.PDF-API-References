---
title: "Document.Pages"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Document свойство. Получает или задает коллекцию страниц документа. Обратите внимание, что страницы нумеруются с 1 в коллекции"
type: docs
weight: 490
url: /ru/net/aspose.pdf/document/pages/
---
## Document.Pages property

Получает или задает коллекцию страниц document. Обратите внимание, что страницы нумеруются с 1 в коллекции.

```csharp
public PageCollection Pages { get; }
```

## Примеры

Ниже приведён пример, демонстрирующий работу со страницами документа: как получить количество страниц и как получить прямоугольник первой страницы документа.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### См. также

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


