---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentage."
type: docs
weight: 330
url: /fr/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentage.

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux contenant le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, alors toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page en pourcentage. |
| newHeight | Double | Nouvelle hauteur du contenu de la page en pourcentage. |

### Valeur de retour

Vrai si le redimensionnement a réussi.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//redimensionner toutes les pages du document
null, 
//nouvelle largeur du contenu = 60 % de la taille initiale
60, 
//nouvelle hauteur du contenu = 60 % de la taille initiale
60);
// La zone restante de la page sera vide (marges de la page). La taille des marges gauche et droite est (100 % - 60 %) / 2 = 20 %
// Idem pour les marges supérieure et inférieure.
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentage.

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | String | Chemin vers le document source. |
| destination | String | Chemin où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, alors toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page en pourcentage. |
| newHeight | Double | Nouvelle hauteur du contenu de la page en pourcentage. |

### Valeur de retour

true si le redimensionnement a réussi.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//redimensionner toutes les pages du document
null, 
//nouvelle largeur du contenu = 60 % de la taille initiale
60, 
//nouvelle hauteur du contenu = 60 % de la taille initiale
60);
// La zone restante de la page sera vide (marges de la page). La taille des marges gauche et droite est (100 % - 60 %) / 2 = 20 %
// Idem pour les marges supérieure et inférieure.
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


