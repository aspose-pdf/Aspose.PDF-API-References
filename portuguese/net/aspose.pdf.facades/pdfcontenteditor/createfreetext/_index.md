---
title: PdfContentEditor.CreateFreeText
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação de texto livre no documento PDF
type: docs
weight: 160
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createfreetext/
---
## Método PdfContentEditor.CreateFreeText

Cria anotação de texto livre no documento PDF

```csharp
public void CreateFreeText(Rectangle rect, string contents, int page)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| page | Int32 | O número da página original onde a anotação de texto será criada. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFreeText(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 1);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)