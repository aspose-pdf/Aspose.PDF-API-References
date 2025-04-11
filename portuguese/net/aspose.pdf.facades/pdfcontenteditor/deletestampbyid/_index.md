---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Exclui o carimbo na página especificada pelo ID do carimbo
type: docs
weight: 340
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Exclui o carimbo na página especificada pelo ID do carimbo.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | Número da página onde o carimbo será excluído. |
| stampId | Int32 | Identificador do carimbo que deve ser excluído. |

## Exemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Exclui o carimbo pelo ID de todas as páginas do documento.

```csharp
public void DeleteStampById(int stampId)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stampId | Int32 | Identificador do carimbo que deve ser excluído. |

## Exemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)