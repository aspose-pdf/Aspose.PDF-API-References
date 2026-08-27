---
title: "PdfContentEditor.DeleteStampById"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Elimina lo stamp nella Page specificata per ID stamp"
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
| pageNumber | Int32 | Numero della Page dove lo stamp sarà eliminato. |
| stampId | Int32 | Identificatore di stanp che dovrebbe essere eliminato. |

## Esempi

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(1, 100);
contentEditor.Save("outfile.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
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
| stampId | Int32 | Identificatore di stamp che dovrebbe essere eliminato. |

## Esempi

```csharp
PdfContentEditor contentEditor = new PdfContentEditor();
contentEditor.BindPdf("file.pdf");
contentEditor.DeleteStampById(100);
contentEditor.Save("outfile.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


