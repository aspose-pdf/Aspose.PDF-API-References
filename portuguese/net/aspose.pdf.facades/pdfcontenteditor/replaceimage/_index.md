---
title: PdfContentEditor.ReplaceImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Substitui a imagem especificada na página especificada do documento PDF por outra imagem
type: docs
weight: 440
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/replaceimage/
---
## Método PdfContentEditor.ReplaceImage

Substitui a imagem especificada na página especificada do documento PDF por outra imagem.

```csharp
public void ReplaceImage(int pageNumber, int index, string imageFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | O número da página na qual a imagem é substituída. |
| index | Int32 | O índice do objeto de imagem que deve ser substituído. |
| imageFile | String | O arquivo de imagem que será usado para a substituição. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.ReplaceImage(1, 1, "image.jpg");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)