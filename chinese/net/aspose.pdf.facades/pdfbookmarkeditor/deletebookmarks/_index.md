---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfBookmarkEditor 方法。删除 PDF 文档中的所有书签"
type: docs
weight: 40
url: /zh/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

删除 PDF document 的所有书签。

```csharp
public void DeleteBookmarks()
```

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

删除 PDF document 的书签。

```csharp
public void DeleteBookmarks(string title)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| title | String | 已删除书签的标题。 |

## 示例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### 另请参见

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


