---
title: PdfContentEditor.CreateCaret
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação de caret
type: docs
weight: 130
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createcaret/
---
## Método PdfContentEditor.CreateCaret

Cria anotação de caret.

```csharp
public void CreateCaret(int page, Rectangle annotRect, Rectangle caretRect, string symbol, 
    string annotContents, Color color)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | O número da página original onde a anotação será criada. |
| annotRect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| caretRect | Rectangle | Os limites reais do caret subjacente. |
| symbol | String | Um símbolo será associado ao caret. O valor pode ser: "P" (Parágrafo), "Nenhum". |
| annotContents | String | O conteúdo da anotação. |
| color | Color | A cor da anotação. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCaret(1,
    new System.Drawing.Rectangle(50, 50, 100, 100),
    new System.Drawing.Rectangle(60, 60, 70, 70),
    "None", "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)