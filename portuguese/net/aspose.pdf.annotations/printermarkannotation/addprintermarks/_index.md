---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: Método PrinterMarkAnnotation. Adiciona marcas de impressão a todas as páginas no documento especificado
type: docs
weight: 10
url: /pt/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Adiciona marcas de impressão a todas as páginas no documento especificado.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| document | Document | O documento ao qual as marcas de impressão serão adicionadas. |
| marksKind | PrinterMarksKind | O tipo de marcas de impressão a serem adicionadas. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentNullException | Lançado quando o *document* é nulo. |

## Observações

Este método adiciona vários tipos de marcas de impressão com base nas flags fornecidas [`PrinterMarksKind`](../../printermarkskind/). Se None for fornecido, nenhuma marca é adicionada.

### Veja Também

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Adiciona marcas de impressão à página especificada.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Page | A página à qual as marcas de impressão serão adicionadas. |
| marksKind | PrinterMarksKind | O tipo de marcas de impressão a serem adicionadas. |

### Exceções

| exceção | condição |
| --- | --- |
| ArgumentNullException | Lançado quando o *page* é nulo. |

## Observações

Este método adiciona vários tipos de marcas de impressão com base nas flags fornecidas [`PrinterMarksKind`](../../printermarkskind/). Se None for fornecido, nenhuma marca é adicionada.

### Veja Também

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)