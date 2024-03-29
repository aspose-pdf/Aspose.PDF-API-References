---
title: DeleteBookmarks
second_title: Aspose.PDF for .NET API 参考
description: 删除 PDF 文档的所有书签
type: docs
weight: 40
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

删除 PDF 文档的所有书签。

```csharp
public void DeleteBookmarks()
```

### 例子

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* 部件 [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

删除 PDF 文档的书签。

```csharp
public void DeleteBookmarks(string title)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| title | String | 书签的标题已删除。 |

### 例子

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### 也可以看看

* class [PdfBookmarkEditor](../../pdfbookmarkeditor)
* 命名空间 [Aspose.Pdf.Facades](../../pdfbookmarkeditor)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
