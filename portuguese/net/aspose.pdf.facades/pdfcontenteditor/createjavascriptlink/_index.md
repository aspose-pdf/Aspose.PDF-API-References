---
title: PdfContentEditor.CreateJavaScriptLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria um link para JavaScript no documento PDF
type: docs
weight: 170
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/
---
## Método PdfContentEditor.CreateJavaScriptLink

Cria um link para JavaScript no documento PDF.

```csharp
public void CreateJavaScriptLink(string code, Rectangle rect, int originalPage, Color color)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| code | String | O código JavaScript. |
| rect | Rectangle | O retângulo para clique ativo. |
| originalPage | Int32 | O número da página original onde o retângulo vinculado ao link será criado. |
| color | Color | A cor do retângulo para clique ativo. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateJavaScriptLink("app.alert('welcome to aspose!');",
    new System.Drawing.Rectangle(0, 0, 100, 100), 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)