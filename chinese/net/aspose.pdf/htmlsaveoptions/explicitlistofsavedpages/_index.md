---
title: "HtmlSaveOptions.ExplicitListOfSavedPages"
second_title: "Aspose.PDF for .NET API 参考"
description: "HtmlSaveOptions 属性。使用此属性可以显式定义应转换的 Document 的哪些 Page。列表中的 Page 必须使用从 1 开始的编号，即有效的 Page 编号应取自 1…NumberOfPagesInConvertedDocument 的范围。列表中 Page 的出现顺序不影响结果 HTML 页面中的顺序，结果页面始终按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（默认情况），则会转换所有 Page。如果列表中的任何 Page 编号超出当前 Document 中的 Page 数量，将抛出异常。"
type: docs
weight: 70
url: /zh/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

使用此属性，您可以明确指定文档的哪些页面应被转换。此列表中的页面必须使用从 1 开始的编号。即，页面编号必须取自范围 (1...[NumberOfPagesInConvertedDocument])。列表中页面出现的顺序不影响结果 HTML 页面中的顺序——结果页面始终按照它们在源 PDF 中出现的顺序排列。如果此列表为 null（默认情况下），则会转换所有页面。如果此列表中的任何页面编号超出现有页面的范围 (1-[amountOfPagesInDocument])，将抛出异常。

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### 另请参见

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


