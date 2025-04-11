---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Redimensionne le contenu des pages de document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages.
type: docs
weight: 330
url: /fr/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Redimensionne le contenu des pages de document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux qui contient le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau des index de pages. Si null, toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page en pourcentages. |
| newHeight | Double | Nouvelle hauteur du contenu de la page en pourcentages. |

### Valeur de retour

true si redimensionné avec succès.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Redimensionne le contenu des pages de document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | String | Chemin vers le document source. |
| destination | String | Chemin où le document résultant sera enregistré. |
| pages | Int32[] | Tableau des index de pages. Si null, toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page en pourcentages. |
| newHeight | Double | Nouvelle hauteur du contenu de la page en pourcentages. |

### Valeur de retour

true si le redimensionnement a réussi.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)