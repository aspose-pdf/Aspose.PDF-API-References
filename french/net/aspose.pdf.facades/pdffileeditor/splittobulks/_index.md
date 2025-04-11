---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Divise le fichier Pdf en plusieurs documents. Les documents peuvent être à une page ou à plusieurs pages.
type: docs
weight: 350
url: /fr/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Divise le fichier Pdf en plusieurs documents. Les documents peuvent être à une page ou à plusieurs pages.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier PDF d'entrée. |
| numberOfPage | Int32[][] | Tableau contenant un tableau d'éléments doubles, qui sont les pages de début et de fin du document. |

### Valeur de retour

Flux PDF de sortie, chaque flux met en mémoire tampon un document PDF.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Divise le fichier Pdf en plusieurs documents. Les documents peuvent être à une page ou à plusieurs pages.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux PDF d'entrée. |
| numberOfPage | Int32[][] | La page de début et la page de fin de chaque document. |

### Valeur de retour

Flux PDF de sortie, chaque flux met en mémoire tampon un document PDF.

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)