---
title: CreateWebLink
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt einen Weblink im PDF-Dokument.
type: docs
weight: 300
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

Erstellt einen Weblink im PDF-Dokument.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| url | String | Das Ziel des Weblinks. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem Weblink verbundenes Rechteck erstellt wird. |
| clr | Color | Die Farbe des Rechtecks für einen aktiven Klick. |
| actionName | Enum[] | Das Array von Aktionen (Mitglieder der PredefinedAction-Enumeration), die der Ausführung von Menüelementen in Acrobat Viewer entsprechen. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

Erstellt einen Weblink im PDF-Dokument.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| url | String | Das Ziel des Weblinks. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem Weblink verbundenes Rechteck erstellt wird. |
| clr | Color | Die Farbe des Rechtecks für einen aktiven Klick. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

Erstellt einen Weblink im PDF-Dokument.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für aktiven Klick. |
| url | String | Das Ziel des Weblinks. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der ein mit einem Weblink verbundenes Rechteck erstellt wird. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### Siehe auch

* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
