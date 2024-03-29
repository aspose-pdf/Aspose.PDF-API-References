---
title: DrawCurve
second_title: Aspose.PDF per .NET API Reference
description: Crea annotazione curva.
type: docs
weight: 360
url: /it/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## PdfContentEditor.DrawCurve method

Crea annotazione curva.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lineInfo | LineInfo | L'istanza della classe LineInfo. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| annotContents | String | Il contenuto dell'annotazione. |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  // funziona con l'istanza Link
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Guarda anche

* class [LineInfo](../../lineinfo)
* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
