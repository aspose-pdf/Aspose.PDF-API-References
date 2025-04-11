---
title: PdfContentEditor.CreatePopup
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação pop-up no documento PDF
type: docs
weight: 250
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createpopup/
---
## Método PdfContentEditor.CreatePopup

Cria anotação pop-up no documento PDF.

```csharp
public void CreatePopup(Rectangle rect, string contents, bool open, int page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| open | Boolean | Uma flag que especifica se a anotação pop-up deve ser exibida inicialmente aberta. |
| page | Int32 | O número da página original onde a anotação será criada. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePopup(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", true, 1);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)