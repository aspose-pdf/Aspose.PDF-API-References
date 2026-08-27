---
title: "PdfContentEditor.DeleteStampById"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。 根据 stamp ID 删除指定页面上的 stamp。"
type: docs
weight: 340
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

根据图章 ID 删除指定页面上的图章。

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 将删除 stamp 的页码。 |
| stampId | Int32 | 应删除的 stanp 标识符。 |

## 示例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

根据 ID 删除文档所有页面上的图章。

```csharp
public void DeleteStampById(int stampId)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stampId | Int32 | 应删除的 stamp 标识符。 |

## 示例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


