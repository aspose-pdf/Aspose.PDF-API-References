---
title: "PrinterMarkAnnotation.AddPrinterMarks"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PrinterMarkAnnotation. Ajoute des marques d'imprimante à toutes les pages du document spécifié"
type: docs
weight: 10
url: /fr/net/aspose.pdf.annotations/printermarkannotation/addprintermarks/
---
## AddPrinterMarks(Document, PrinterMarksKind) {#addprintermarks}

Ajoute les repères d'imprimante à toutes les pages du document spécifié.

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
| ArgumentNullException | Lancée lorsque le *document* est nul. |

## Remarques

Cette méthode ajoute différents types de marques d'imprimante en fonction des indicateurs [`PrinterMarksKind`](../../printermarkskind/) fournis. Si None est fourni, aucune marque n'est ajoutée.

### Voir aussi

* class [Document](../../../aspose.pdf/document/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## AddPrinterMarks(Page, PrinterMarksKind) {#addprintermarks_1}

Ajoute les repères d'imprimante à la page spécifiée.

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
| ArgumentNullException | Lancée lorsque la *page* est nulle. |

## Remarques

Cette méthode ajoute différents types de marques d'imprimante en fonction des indicateurs [`PrinterMarksKind`](../../printermarkskind/) fournis. Si None est fourni, aucune marque n'est ajoutée.

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* enum [PrinterMarksKind](../../printermarkskind/)
* class [PrinterMarkAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


