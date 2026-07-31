---
title: "PrinterMarkAnnotation.AddPrinterMarks"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PrinterMarkAnnotation. Aggiunge i segni della stampante a tutte le pagine del documento specificato"
type: docs
weight: 10
url: /it/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Aggiunge i segni della stampante a tutte le pagine del documento specificato.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Document | Il documento a cui verranno aggiunti i segni della stampante. |
| marksKind | PrinterMarksKind | Il tipo di segni della stampante da aggiungere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando il *document* è nullo. |

## Osservazioni

Questo metodo aggiunge vari tipi di segni della stampante in base alle flag [`PrinterMarksKind`](../../printermarkskind/) fornite. Se viene fornito None, non vengono aggiunti segni.

### Vedi anche

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Aggiunge i segni della stampante alla pagina specificata.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina | Page | La pagina a cui verranno aggiunti i segni della stampante. |
| marksKind | PrinterMarksKind | Il tipo di segni della stampante da aggiungere. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando il *page* è nullo. |

## Osservazioni

Questo metodo aggiunge vari tipi di segni della stampante in base alle flag [`PrinterMarksKind`](../../printermarkskind/) fornite. Se viene fornito None, non vengono aggiunti segni.

### Vedi anche

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


