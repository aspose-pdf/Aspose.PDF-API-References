---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfContentEditor 方法。删除文档所有页面中具有指定 ID 的印章。"
type: docs
weight: 350
url: /zh/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

从文档所有页面删除具有指定 ID 的图章。

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stampIds | Int32[] | 印章 ID 的数组。 |

## 示例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

根据多个图章 ID 删除指定页面上的图章。

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageNumber | Int32 | 将删除印章的页码。 |
| stampIds | Int32[] | 印章 ID 的数组。 |

## 示例

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### 另请参见

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


