---
title: "PdfBookmarkEditor.ImportBookmarksWithXML"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfBookmarkEditor 方法。从 XML 文件导入书签到文档"
type: docs
weight: 70
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/
---
## ImportBookmarksWithXML(string) {#importbookmarkswithxml_1}

从 XML 文件导入书签到 document。

```csharp
public void ImportBookmarksWithXML(string xmlFile)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| xmlFile | String | 包含书签列表的 XML 文件。 |

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.ImportBookmarksWithXML("bookmarks.xml");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportBookmarksWithXML(Stream) {#importbookmarkswithxml}

从 XML 文件导入书签到 document。

```csharp
public void ImportBookmarksWithXML(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 包含书签数据的流。 |

### 另请参见

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


