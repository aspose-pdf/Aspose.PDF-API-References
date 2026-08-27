---
title: "Document.Pages"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 属性。获取或设置文档页面的集合。注意，集合中的页面编号从 1 开始"
type: docs
weight: 490
url: /zh/net/aspose.pdf/document/pages/
---
## Document.Pages property

获取或设置文档页面的集合。请注意，集合中的页面编号从 1 开始。

```csharp
public PageCollection Pages { get; }
```

## 示例

下面的示例演示如何操作文档页面：如何获取页面数量以及如何获取文档起始页的矩形。

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### 另请参见

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


