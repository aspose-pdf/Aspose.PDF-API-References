---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor method. Creates popup annotation in PDF document
type: docs
weight: 250
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## Metodo PdfContentEditor.CreatePopup

Crea annotazione popup nel documento PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | I contenuti dell'annotazione. |
| open | Boolean | Un flag che specifica se l'annotazione popup deve essere inizialmente visualizzata aperta. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)