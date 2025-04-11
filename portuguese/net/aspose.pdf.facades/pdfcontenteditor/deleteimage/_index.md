---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Exclui as imagens especificadas na página especificada
type: docs
weight: 320
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

Exclui as imagens especificadas na página especificada.

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | O número da página na qual as imagens devem ser excluídas. |
| index | Int32[] | Um array que representa os índices das imagens. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

Exclui todas as imagens do documento PDF.

```csharp
public void DeleteImage()
```

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)