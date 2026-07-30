---
title: "PdfFileEditor.SplitToBulks"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Divise le fichier Pdf en plusieurs documents. Les documents peuvent être à page unique ou multipages."
type: docs
weight: 350
url: /fr/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Divise le fichier Pdf en plusieurs documents. Les documents peuvent être d'une seule page ou multi-pages.

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFile | String | Fichier PDF d'entrée. |
| numberOfPage | Int32[][] | Tableau qui contient un tableau d'éléments double, qui représente les pages de début et de fin du document. |

### Valeur de retour

Flux PDF de sortie, chaque flux tamponne un document PDF.

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Divise le fichier Pdf en plusieurs documents. Les documents peuvent être d'une seule page ou multi-pages.

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux PDF d'entrée. |
| numberOfPage | Int32[][] | La page de début et la page de fin de chaque document. |

### Valeur de retour

Flux PDF de sortie, chaque flux tamponne un document PDF.

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


