---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: Metodo PrinterMarkAnnotation. Aggiunge i segni del stampatore a tutte le pagine nel documento specificato
type: docs
weight: 10
url: /it/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Aggiunge i segni del stampatore a tutte le pagine nel documento specificato.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Document | Il documento a cui verranno aggiunti i segni del stampatore. |
| marksKind | PrinterMarksKind | Il tipo di segni del stampatore da aggiungere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Sollevato quando il *document* è nullo. |

## Osservazioni

Questo metodo aggiunge vari tipi di segni del stampatore in base ai flag forniti [`PrinterMarksKind`](../../printermarkskind/). Se None è fornito, non vengono aggiunti segni.

### Vedi Anche

* classe [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* classe [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Aggiunge i segni del stampatore alla pagina specificata.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Page | La pagina a cui verranno aggiunti i segni del stampatore. |
| marksKind | PrinterMarksKind | Il tipo di segni del stampatore da aggiungere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Sollevato quando la *page* è nulla. |

## Osservazioni

Questo metodo aggiunge vari tipi di segni del stampatore in base ai flag forniti [`PrinterMarksKind`](../../printermarkskind/). Se None è fornito, non vengono aggiunti segni.

### Vedi Anche

* classe [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* classe [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)