---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 方法。通过印章 ID 删除指定页面上的印章
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

通过印章 ID 删除指定页面上的印章。

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 将删除印章的页面编号。 |
| stampId | Int32 | 应该被删除的印章的标识符。 |

## 示例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

从文档的所有页面中通过 ID 删除印章。

```csharp
public void DeleteStampById(int stampId)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stampId | Int32 | 应该被删除的印章的标识符。 |

## 示例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### 另请参阅

* 类 [PdfContentEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)