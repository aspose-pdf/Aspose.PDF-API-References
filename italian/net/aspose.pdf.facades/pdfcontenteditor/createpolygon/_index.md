---
title: PdfContentEditor.CreatePolygon
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Creates polygon annotation
type: docs
weight: 230
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createpolygon/
---
## Metodo PdfContentEditor.CreatePolygon

Crea annotazione poligonale.

```csharp
public void CreatePolygon(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lineInfo | LineInfo | L'istanza della classe LineInfo. |
| page | Int32 | Il numero della pagina originale dove verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| annotContents | String | I contenuti dell'annotazione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100, 100, 50 };
lineInfo.Visibility = true;
editor.CreatePolygon(lineInfo, 1 , new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [LineInfo](../../lineinfo/)
* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)