---
title: PdfContentEditor.CreateSquareCircle
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação quadrado-círculo
type: docs
weight: 280
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## Método PdfContentEditor.CreateSquareCircle

Cria anotação quadrado-círculo.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| clr | Color | A cor do quadrado ou círculo. |
| square | Boolean | Verdadeiro (quadrado), falso (círculo). |
| page | Int32 | O número da página original onde a anotação será criada. |
| borderWidth | Int32 | A largura da borda do quadrado ou círculo. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)