---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor metodu. Belirtilen sayfa için yer imi oluşturur
type: docs
weight: 20
url: /tr/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Belirtilen sayfa için yer imi oluşturur.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bookmarkName | String | Belirtilen yer imi adı. |
| pageNumber | Int32 | Belirtilen hedef sayfa. |

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Belirtilen sayfalar için yer imleri oluşturur.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bookmarkName | String[] | Yer imleri başlık dizisi. |
| pageNumber | Int32[] | Yer imleri hedef sayfa dizisi. |

## Örnekler

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Ayrıca Bakınız

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)