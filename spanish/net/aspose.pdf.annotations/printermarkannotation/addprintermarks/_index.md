---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: Método PrinterMarkAnnotation. Agrega marcas de impresora a todas las páginas en el documento especificado
type: docs
weight: 10
url: /es/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Agrega marcas de impresora a todas las páginas en el documento especificado.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document | Document | El documento al que se agregarán las marcas de impresora. |
| marksKind | PrinterMarksKind | El tipo de marcas de impresora a agregar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando el *document* es nulo. |

## Observaciones

Este método agrega varios tipos de marcas de impresora según las banderas proporcionadas [`PrinterMarksKind`](../../printermarkskind/). Si se proporciona None, no se agregan marcas.

### Véase también

* clase [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* clase [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Agrega marcas de impresora a la página especificada.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | Page | La página a la que se agregarán las marcas de impresora. |
| marksKind | PrinterMarksKind | El tipo de marcas de impresora a agregar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando el *page* es nulo. |

## Observaciones

Este método agrega varios tipos de marcas de impresora según las banderas proporcionadas [`PrinterMarksKind`](../../printermarkskind/). Si se proporciona None, no se agregan marcas.

### Véase también

* clase [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* clase [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)