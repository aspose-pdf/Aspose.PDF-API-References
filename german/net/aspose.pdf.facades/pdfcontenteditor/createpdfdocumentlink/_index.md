---
title: CreatePdfDocumentLink
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt einen Link zu einer anderen PDF-Dokumentseite.
type: docs
weight: 220
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## CreatePdfDocumentLink(Rectangle, string, int, int, Color, Enum[]) {#createpdfdocumentlink_2}

Erstellt einen Link zu einer anderen PDF-Dokumentseite.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| remotePdf | String | Das PDF-Dokument, dessen Seite geöffnet wird. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem Link verbundenes Rechteck erstellt wird. |
| destinationPage | Int32 | Die Zielseite. |
| clr | Color | Die Farbe des Rechtecks für einen aktiven Klick. |
| actionName | Enum[] | Das Array von Aktionen (Mitglieder der PredefinedAction-Enumeration), die der Ausführung von Menüelementen in Acrobat Viewer entsprechen. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

Erstellt einen Link zu einer anderen PDF-Dokumentseite.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| remotePdf | String | Das PDF-Dokument, dessen Seite geöffnet wird. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem Link verbundenes Rechteck erstellt wird. |
| destinationPage | Int32 | Die Zielseite. |
| clr | Color | Die Farbe des Rechtecks für einen aktiven Klick. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

Erstellt einen Link zu einer anderen PDF-Dokumentseite.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| remotePdf | String | Das PDF-Dokument, dessen Seite geöffnet wird. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem Link verbundenes Rechteck erstellt wird. |
| destinationPage | Int32 | Die Zielseite. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->