---
title: PdfContentEditor.DeleteStampByIds
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Exclui carimbos com IDs especificados de todas as páginas do documento
type: docs
weight: 350
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Exclui carimbos com IDs especificados de todas as páginas do documento.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stampIds | Int32[] | Array de IDs de carimbos. |

## Exemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Exclui carimbos na página especificada por múltiplos IDs de carimbos.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pageNumber | Int32 | Número da página onde os carimbos serão excluídos. |
| stampIds | Int32[] | Array de IDs de carimbos. |

## Exemplos

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)