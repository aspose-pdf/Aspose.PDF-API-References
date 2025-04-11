---
title: PrinterMarkAnnotation.AddPrinterMarks
second_title: Aspose.PDF for .NET API Reference
description: Méthode PrinterMarkAnnotation. Ajoute des marques d'imprimante à toutes les pages du document spécifié
type: docs
weight: 10
url: /fr/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Ajoute des marques d'imprimante à toutes les pages du document spécifié.

```csharp
public static void AddPrinterMarks(Document document, PrinterMarksKind marksKind)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| document | Document | Le document auquel les marques d'imprimante seront ajoutées. |
| marksKind | PrinterMarksKind | Le type de marques d'imprimante à ajouter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque le *document* est nul. |

## Remarques

Cette méthode ajoute divers types de marques d'imprimante en fonction des drapeaux [`PrinterMarksKind`](../../printermarkskind/) fournis. Si None est fourni, aucune marque n'est ajoutée.

### Voir aussi

* classe [Document](../../../aspose.pdf/document/)
* énum [PrinterMarksKind](../../printermarkskind/)
* classe [PrinterMarkAnnotation](../)
* espace de noms [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Ajoute des marques d'imprimante à la page spécifiée.

```csharp
public static void AddPrinterMarks(Page page, PrinterMarksKind marksKind)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | La page à laquelle les marques d'imprimante seront ajoutées. |
| marksKind | PrinterMarksKind | Le type de marques d'imprimante à ajouter. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancé lorsque la *page* est nulle. |

## Remarques

Cette méthode ajoute divers types de marques d'imprimante en fonction des drapeaux [`PrinterMarksKind`](../../printermarkskind/) fournis. Si None est fourni, aucune marque n'est ajoutée.

### Voir aussi

* classe [Page](../../../aspose.pdf/page/)
* énum [PrinterMarksKind](../../printermarkskind/)
* classe [PrinterMarkAnnotation](../)
* espace de noms [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)