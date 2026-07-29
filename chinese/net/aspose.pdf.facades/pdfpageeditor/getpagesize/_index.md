---
title: "PdfPageEditor.GetPageSize"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfPageEditor 方法。返回指定页面的页面大小"
type: docs
weight: 160
url: /zh/net/aspose.pdf.facades/pdfpageeditor/getpagesize/
---
## PdfPageEditor.GetPageSize method

返回指定页面的页面大小。

```csharp
public PageSize GetPageSize(int page)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 页面 | Int32 | 页索引。文档页面从 1 开始编号。 |

### 返回值

结果是 PageSize 的实例。使用返回对象的 Width 和 Height 属性来获取页面宽度和高度。

## 示例

以下示例演示了 GetPageSize 方法的使用：

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
PageSize size = editor.GetPageSize(1);
Console.WriteLine("Size of 1st page : " + size.Width + " x " + size.Height);
```

### 另请参见

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


