---
title: ResizeContentsPct
second_title: Référence de l'API Aspose.PDF pour .NET
description: Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages.
type: docs
weight: 360
url: /fr/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | String | Chemin d'accès au document source. |
| destination | String | Chemin où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page en pourcentage. |
| newHeight | Double | Nouvelle hauteur du contenu de la page en pourcentages. |

### Return_Value

true si le redimensionnement a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
// redimensionner toutes les pages du document
null, 
//largeur du nouveau contenu = 60% de la taille initiale
60, 
//hauteur du nouveau contenu = 60% de la taille initiale
60);
// La zone de repos de la page sera vide (marges de la page). La taille des marges gauche et droite est (100% - 60%) / 2 = 20%
// Idem pour les marges supérieure et inférieure.
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | Stream | Flux qui contient le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page en pourcentage. |
| newHeight | Double | Nouvelle hauteur du contenu de la page en pourcentages. |

### Return_Value

true si redimensionné avec succès.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
// redimensionner toutes les pages du document
null, 
//largeur du nouveau contenu = 60% de la taille initiale
60, 
//hauteur du nouveau contenu = 60% de la taille initiale
60);
// La zone de repos de la page sera vide (marges de la page). La taille des marges gauche et droite est (100% - 60%) / 2 = 20%
// Idem pour les marges supérieure et inférieure.
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->