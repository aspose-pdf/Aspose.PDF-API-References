---
title: "PdfContentEditor.CreateText"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Crea un'annotazione di testo in PDF Document"
type: docs
weight: 290
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## PdfContentEditor.CreateText method

Crea un'annotazione di testo nel documento PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| title | String | Il titolo dell'annotazione. |
| contents | String | Il contenuto dell'annotazione. |
| open | Boolean | Un flag che specifica se l'annotazione deve essere visualizzata aperta inizialmente. |
| icon | String | Il nome di un'icona verrà usato nella visualizzazione dell'annotazione. Questo valore può essere: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| pagina | Int32 | Il numero della Page originale dove verrà creata l'annotazione di testo. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


