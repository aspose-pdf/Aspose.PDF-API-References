---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions 属性。通过此属性，您可以明确指定文档的哪些页面应该被转换。此列表中的页面必须具有基于1的编号。即，页面的有效编号必须取自范围 1...NumberOfPagesInConvertedDocument。此列表中页面的出现顺序不会影响结果 HTML 页面中的顺序 - 在结果页面中，页面始终将按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（如默认情况），则所有页面将被转换。如果此列表中的任何页面编号超出当前页面的范围（1-[amountOfPagesInDocument]），将抛出异常。
type: docs
weight: 70
url: /zh/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages 属性

通过此属性，您可以明确指定文档的哪些页面应该被转换。此列表中的页面必须具有基于1的编号。即，页面的有效编号必须取自范围 (1...[NumberOfPagesInConvertedDocument])。此列表中页面的出现顺序不会影响结果 HTML 页面中的顺序 - 在结果页面中，页面始终将按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（如默认情况），则所有页面将被转换。如果此列表中的任何页面编号超出当前页面的范围（1-[amountOfPagesInDocument]），将抛出异常。

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### 另请参阅

* 类 [HtmlSaveOptions](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)