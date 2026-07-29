---
title: "PdfContentEditor.DeleteStamp"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。根据印章索引删除指定页面上的多个印章"
type: docs
weight: 330
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## PdfContentEditor.DeleteStamp method

按图章索引删除指定页面上的多个图章。

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 将删除 stamp 的页码。 |
| index | Int32[] | 印章索引。 |

## 示例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


