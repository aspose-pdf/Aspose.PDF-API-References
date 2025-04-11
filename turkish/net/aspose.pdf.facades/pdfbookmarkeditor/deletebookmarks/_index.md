---
title: PdfBookmarkEditor.DeleteBookmarks
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metodu. PDF belgesinin tüm yer imlerini siler
type: docs
weight: 40
url: /tr/net/aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/
---
## DeleteBookmarks() {#deletebookmarks}

PDF belgesinin tüm yer imlerini siler.

```csharp
public void DeleteBookmarks()
```

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks();
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## DeleteBookmarks(string) {#deletebookmarks_1}

PDF belgesinin yer imini siler.

```csharp
public void DeleteBookmarks(string title)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| title | String | Silinen yer iminin başlığı. |

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.DeleteBookmarks("existing bookmark title");
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* sınıf [PdfBookmarkEditor](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)