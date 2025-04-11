---
title: PdfBookmarkEditor.ExportBookmarksToXML
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor 方法。将书签导出到 XML 文件
type: docs
weight: 50
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

将书签导出到 XML 文件。

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlFile | 字符串 | 输出的 XML 文件。 |

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### 另请参阅

* 类 [PdfBookmarkEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

将书签导出到 XML 流。

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | 流 | 数据将存储的输出流。 |

### 另请参阅

* 类 [PdfBookmarkEditor](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)