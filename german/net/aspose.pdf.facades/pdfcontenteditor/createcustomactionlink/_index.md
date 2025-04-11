---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor-Methode. Erstellt einen Link zu benutzerdefinierten Aktionen im PDF-Dokument
type: docs
weight: 140
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink-Methode

Erstellt einen Link zu benutzerdefinierten Aktionen im PDF-Dokument.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rechteck | Das Rechteck für den aktiven Klick. |
| originalPage | Int32 | Die Nummer der Originalseite, auf der das Rechteck mit dem Link erstellt wird. |
| color | Farbe | Die Farbe des Rechtecks für den aktiven Klick. |
| actionName | Enum[] | Das Array von Aktionen (Mitglieder des PredefinedAction-Enums), die den auszuführenden Menüelementen im Acrobat-Viewer entsprechen. |

## Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Siehe auch

* Klasse [PdfContentEditor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)