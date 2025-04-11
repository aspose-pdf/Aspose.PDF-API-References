---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea annotazione di markup in documento PDF
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## Metodo PdfContentEditor.CreateMarkup

Crea annotazione di markup in documento PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | I contenuti dell'annotazione. |
| type | Int32 | Il tipo di annotazione di markup. Può essere 0 (Evidenziazione), 1 (Sottolineatura), 2 (Barrato), 3 (Ondulato). |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| clr | Color | Il colore del markup. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)