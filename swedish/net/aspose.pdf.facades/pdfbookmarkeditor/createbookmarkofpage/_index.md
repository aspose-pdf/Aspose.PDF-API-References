---
title: "PdfBookmarkEditor.CreateBookmarkOfPage"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfBookmarkEditor metod. Skapar bokmärke för den angivna sidan"
type: docs
weight: 20
url: /sv/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Skapar bokmärke för den angivna sidan.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bookmarkName | String | Det angivna bokmärkesnamnet. |
| pageNumber | Int32 | Den angivna destinationssidan. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Skapar bokmärken för de angivna sidorna.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bookmarkName | String[] | Array med bokmärkestitlar. |
| pageNumber | Int32[] | Array med bokmärkes destinationssidor. |

## Exempel

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Se även

* class [PdfBookmarkEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


