---
title: PdfContentEditor.CreateMarkup
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação de marcação em documento PDF
type: docs
weight: 200
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createmarkup/
---
## Método PdfContentEditor.CreateMarkup

Cria anotação de marcação em documento PDF.

```csharp
public void CreateMarkup(Rectangle rect, string contents, int type, int page, Color clr)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| type | Int32 | O tipo de anotação de marcação. Pode ser 0 (Destaque), 1 (Sublinhado), 2 (Riscado), 3 (Ziguezague). |
| page | Int32 | O número da página original onde a anotação será criada. |
| clr | Color | A cor da marcação. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateMarkup(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", 0, 1, System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)