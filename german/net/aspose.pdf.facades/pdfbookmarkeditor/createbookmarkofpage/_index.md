---
title: PdfBookmarkEditor.CreateBookmarkOfPage
second_title: Aspose.PDF for .NET API Reference
description: PdfBookmarkEditor-Methode. Erstellt ein Lesezeichen für die angegebene Seite
type: docs
weight: 20
url: /de/net/aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/
---
## CreateBookmarkOfPage(string, int) {#createbookmarkofpage}

Erstellt ein Lesezeichen für die angegebene Seite.

```csharp
public void CreateBookmarkOfPage(string bookmarkName, int pageNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bookmarkName | String | Der angegebene Lesezeichenname. |
| pageNumber | Int32 | Die angegebene Zielseite. |

## Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateBookmarkOfPage(string[], int[]) {#createbookmarkofpage_1}

Erstellt Lesezeichen für die angegebenen Seiten.

```csharp
public void CreateBookmarkOfPage(string[] bookmarkName, int[] pageNumber)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bookmarkName | String[] | Array von Lesezeichentiteln. |
| pageNumber | Int32[] | Array von Zielseiten für Lesezeichen. |

## Beispiele

```csharp
PdfBookmarkEditor editor = new PdfBookmarkEditor();
editor.BindPdf("example.pdf");
editor.CreateBookmarkOfPage("bookmark for page 1", 1);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfBookmarkEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)