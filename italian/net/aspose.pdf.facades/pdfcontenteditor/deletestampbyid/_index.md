---
title: PdfContentEditor.DeleteStampById
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Elimina il timbro nella pagina specificata per ID timbro
type: docs
weight: 340
url: /it/net/aspose.pdf.facades/pdfcontenteditor/deletestampbyid/
---
## DeleteStampById(int, int) {#deletestampbyid_1}

Elimina il timbro nella pagina specificata per ID timbro.

```csharp
public void DeleteStampById(int pageNumber, int stampId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pageNumber | Int32 | Numero della pagina in cui il timbro sarà eliminato. |
| stampId | Int32 | Identificatore del timbro che deve essere eliminato. |

## Esempi

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteStampById(int) {#deletestampbyid}

Elimina il timbro per ID da tutte le pagine del documento.

```csharp
public void DeleteStampById(int stampId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stampId | Int32 | Identificatore del timbro che deve essere eliminato. |

## Esempi

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)