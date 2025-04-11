---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor metodo. Crea annotazione testo in PDF documento.
type: docs
weight: 290
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## Metodo PdfContentEditor.CreateText

Crea annotazione di testo nel documento PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| title | String | Il titolo dell'annotazione. |
| contents | String | I contenuti dell'annotazione. |
| open | Boolean | Un flag che specifica se l'annotazione deve essere inizialmente visualizzata aperta. |
| icon | String | Il nome di un'icona che verrà utilizzata per visualizzare l'annotazione. Questo valore può essere: "Commento", "Chiave", "Nota", "Aiuto", "NuovoParagrafo", "Paragrafo", "Inserisci" |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione di testo. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)