---
title: CreateLocalLink
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt einen lokalen Link im PDF-Dokument.
type: docs
weight: 190
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

Erstellt einen lokalen Link im PDF-Dokument.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| desPage | Int32 | Die Zielseite. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem lokalen Link verbundenes Rechteck erstellt wird. |
| clr | Color | Die Farbe des Rechtecks für einen aktiven Klick. |
| actionName | Enum[] | Das Array von Aktionen (Mitglieder der PredefinedAction-Enumeration), die der Ausführung von Menüelementen in Acrobat Viewer entsprechen. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

Erstellt einen lokalen Link im PDF-Dokument.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| desPage | Int32 | Die Zielseite. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem lokalen Link verbundenes Rechteck erstellt wird. |
| clr | Color | Die Farbe des Rechtecks für einen aktiven Klick. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

Erstellt einen lokalen Link im PDF-Dokument.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| desPage | Int32 | Die Zielseite. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem lokalen Link verbundenes Rechteck erstellt wird. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
