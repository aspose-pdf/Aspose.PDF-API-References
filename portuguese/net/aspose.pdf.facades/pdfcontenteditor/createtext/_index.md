---
title: PdfContentEditor.CreateText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação de texto em documento PDF
type: docs
weight: 290
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createtext/
---
## Método PdfContentEditor.CreateText

Cria anotação de texto em documento PDF

```csharp
public void CreateText(Rectangle rect, string title, string contents, bool open, string icon, 
    int page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| title | String | O título da anotação. |
| contents | String | O conteúdo da anotação. |
| open | Boolean | Uma flag que especifica se a anotação deve ser exibida inicialmente aberta. |
| icon | String | O nome de um ícone que será usado na exibição da anotação. Este valor pode ser: "Comment", "Key", "Note", "Help", "NewParagraph", "Paragraph", "Insert" |
| page | Int32 | O número da página original onde a anotação de texto será criada. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateText(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "You are welcome to Aspose!", true, "Key", 1);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)