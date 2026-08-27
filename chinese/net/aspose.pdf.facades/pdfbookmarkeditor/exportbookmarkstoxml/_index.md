---
title: "PdfBookmarkEditor.ExportBookmarksToXML"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfBookmarkEditor 方法。将书签导出到 XML 文件"
type: docs
weight: 50
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/
---
## ExportBookmarksToXML(string) {#exportbookmarkstoxml_1}

将书签导出为 XML 文件。

```csharp
public void ExportBookmarksToXML(string xmlFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlFile | String | 输出的 XML 文件。 |

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ExportBookmarksToXML("bookmarks.xml");
```

### 另请参见

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ExportBookmarksToXML(Stream) {#exportbookmarkstoxml}

将书签导出为 XML 流。

```csharp
public void ExportBookmarksToXML(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于存储数据的输出流。 |

### 另请参见

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


