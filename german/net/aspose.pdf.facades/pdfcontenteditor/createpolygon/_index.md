---
title: CreatePolygon
second_title: Aspose.PDF für .NET-API-Referenz
description: Erstellt eine Polygonanmerkung.
type: docs
weight: 230
url: /de/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## PdfContentEditor.CreatePolygon method

Erstellt eine Polygonanmerkung.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| lineInfo | LineInfo | Die Instanz der LineInfo-Klasse. |
| page | Int32 | Die Nummer der Originalseite, auf der die Anmerkung erstellt wird. |
| annotRect | Rectangle | Das Anmerkungsrechteck, das die Position der Anmerkung auf der Seite definiert. |
| annotContents | String | Der Inhalt der Anmerkung. |

### Beispiele

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Siehe auch

* class [LineInfo](../../lineinfo)
* class [PdfContentEditor](../../pdfcontenteditor)
* namensraum [Aspose.Pdf.Facades](../../pdfcontenteditor)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
