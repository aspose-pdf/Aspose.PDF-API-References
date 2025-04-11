---
title: PdfContentEditor.DeleteStamp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Exclui múltiplos carimbos na página especificada pelos índices dos carimbos
type: docs
weight: 330
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/deletestamp/
---
## Método PdfContentEditor.DeleteStamp

Exclui múltiplos carimbos na página especificada pelos índices dos carimbos.

```csharp
public void DeleteStamp(int pageNumber, int[] index)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | Número da página onde o carimbo será excluído. |
| index | Int32[] | Índices dos carimbos. |

## Exemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStamp(1, new int[] { 2, 3, 5} );
contentEditor.Save("outfile.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)