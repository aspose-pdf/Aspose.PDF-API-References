---
title: "PdfBookmarkEditor.DeleteBookmarks"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfBookmarkEditor メソッド。PDF ドキュメントのすべてのブックマークを削除します"
type: docs
weight: 40
url: /ja/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

PDF Document のすべてのブックマークを削除します。

```csharp
public void DeleteBookmarks()
```

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

PDF Document のブックマークを削除します。

```csharp
public void DeleteBookmarks(string title)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| title | String | 削除されたブックマークのタイトルです。 |

## 例

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


