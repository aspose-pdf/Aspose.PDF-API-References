---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea annotazione di testo libero nel documento PDF
type: docs
weight: 160
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## Metodo PdfContentEditor.CreateFreeText

Crea annotazione di testo libero nel documento PDF

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | I contenuti dell'annotazione. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione di testo. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)