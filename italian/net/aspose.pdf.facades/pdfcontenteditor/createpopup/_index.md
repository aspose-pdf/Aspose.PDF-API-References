---
title: "PdfContentEditor.CreatePopup"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Crea un'annotazione popup nel documento PDF"
type: docs
weight: 250
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## PdfContentEditor.CreatePopup method

Crea un'annotazione popup nel documento PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| open | Boolean | Un flag che specifica se l'annotazione pop-up deve essere visualizzata aperta inizialmente. |
| pagina | Int32 | Il numero della pagina originale dove verrà creata l'annotazione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


