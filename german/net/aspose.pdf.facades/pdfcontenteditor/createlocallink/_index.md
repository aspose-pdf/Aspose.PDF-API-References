---
title: PdfContentEditor.CreateLocalLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt einen lokalen Link im PDF-Dokument
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
| rect | Rectangle | Das Rechteck für den aktiven Klick. |
| desPage | Int32 | Die Zielseite. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der das Rechteck mit dem lokalen Link erstellt wird. |
| clr | Color | Die Farbe des Rechtecks für den aktiven Klick. |
| actionName | Enum[] | Das Array von Aktionen (Mitglieder des PredefinedAction-Enums), die den auszuführenden Menüelementen im Acrobat-Viewer entsprechen. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

Erstellt einen lokalen Link im PDF-Dokument.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für den aktiven Klick. |
| desPage | Int32 | Die Zielseite. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der das Rechteck mit dem lokalen Link erstellt wird. |
| clr | Color | Die Farbe des Rechtecks für den aktiven Klick. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

Erstellt einen lokalen Link im PDF-Dokument.

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für den aktiven Klick. |
| desPage | Int32 | Die Zielseite. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der das Rechteck mit dem lokalen Link erstellt wird. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)