---
title: "PdfContentEditor.DeleteStampByIds"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Elimina i timbri con ID specificati da tutte le pagine del documento"
type: docs
weight: 350
url: /it/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyids/
---
## DeleteStampByIds(int[]) {#deletestampbyids_1}

Elimina i timbri con gli ID specificati da tutte le pagine del documento.

```csharp
public void DeleteStampByIds(int[] stampIds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stampIds | Int32[] | Array di ID dei timbri. |

## Esempi

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(new int[] { 102, 103 } );
contentEditor.Save("outfile.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampByIds(int, int[]) {#deletestampbyids}

Elimina i timbri nella pagina specificata per più ID timbro.

```csharp
public void DeleteStampByIds(int pageNumber, int[] stampIds)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Numero di pagina in cui i timbri verranno eliminati. |
| stampIds | Int32[] | Array di ID dei timbri. |

## Esempi

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampByIds(1, new int[] { 100, 101 } );
contentEditor.Save("outfile.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


