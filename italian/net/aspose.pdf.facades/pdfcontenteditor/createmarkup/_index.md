---
title: "PdfContentEditor.CreateMarkup"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Crea un'annotazione markup in PDF Document"
type: docs
weight: 200
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## PdfContentEditor.CreateMarkup method

Crea un'annotazione di markup nel documento PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il **Rectangle** che definisce la posizione dell'annotazione sulla Page. |
| contents | String | Il contenuto dell'annotazione. |
| type | Int32 | Il tipo di annotazione markup. Può essere 0 (Highlight), 1 (Underline), 2 (StrikeOut), 3 (Squiggly). |
| pagina | Int32 | Il numero della pagina originale dove verrà creata l'annotazione. |
| clr | Color | Il **Color** del markup. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


