---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument
type: docs
weight: 110
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für den aktiven Klick. |
| application | String | Der Pfad der zu startenden Anwendung. |
| page | Int32 | Die Nummer der ursprünglichen Seite, auf der das mit dem Link verbundene Rechteck erstellt wird. |
| clr | Color | Die Farbe des Rechtecks für den aktiven Klick. |
| actionName | Enum[] | Das Array von Aktionen (Mitglieder des PredefinedAction-Enums), die den auszuführenden Menüelementen im Acrobat-Viewer entsprechen. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für den aktiven Klick. |
| application | String | Der Pfad der zu startenden Anwendung. |
| page | Int32 | Die Nummer der ursprünglichen Seite, auf der das mit dem Link verbundene Rechteck erstellt wird. |
| clr | Color | Die Farbe des Rechtecks für den aktiven Klick. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Erstellt einen Link zum Starten einer Anwendung im PDF-Dokument.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | Das Rechteck für den aktiven Klick. |
| application | String | Der Pfad der zu startenden Anwendung. |
| page | Int32 | Die Nummer der ursprünglichen Seite, auf der das mit dem Link verbundene Rechteck erstellt wird. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)