---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt eine Gummistempel-Annotation
type: docs
weight: 260
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Erstellt eine Gummistempel-Annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Nummer der Originalseite, auf der die Annotation erstellt wird. |
| annotRect | Rectangle | Das Annotationsrechteck, das den Standort der Annotation auf der Seite definiert. |
| icon | String | Ein Symbol, das zur Anzeige der Annotation verwendet werden soll. Standardwert: 'Entwurf'. |
| annotContents | String | Der Inhalt der Annotation. |
| color | Color | Die Farbe der Annotation. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Erstellt eine Gummistempel-Annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Nummer der Originalseite, auf der die Annotation erstellt wird. |
| annotRect | Rectangle | Das Annotationsrechteck, das den Standort der Annotation auf der Seite definiert. |
| annotContents | String | Der Inhalt der Annotation. |
| color | Color | Die Farbe der Annotation. |
| appearanceFile | String | Der Pfad zur Erscheinungsdatei. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Erstellt eine Gummistempel-Annotation.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | Int32 | Die Nummer der Originalseite, auf der die Annotation erstellt wird. |
| annotRect | Rectangle | Das Annotationsrechteck, das den Standort der Annotation auf der Seite definiert. |
| annotContents | String | Der Inhalt der Annotation. |
| color | Color | Die Farbe der Annotation. |
| appearanceStream | Stream | Der Stream der Erscheinungsdatei. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)