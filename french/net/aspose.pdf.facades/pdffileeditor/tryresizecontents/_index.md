---
title: TryResizeContents
second_title: Référence de l'API Aspose.PDF pour .NET
description: Redimensionne le contenu des pages du document. Si la page est réduite des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans lobjet HttpResponse.
type: docs
weight: 480
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents_3}

Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | String | Chemin d'accès au fichier source. |
| pages | Int32[] | Tableau de pages à redimensionner. |
| parameters | ContentsResizeParameters | Redimensionner les paramètres. |
| response | HttpResponse | Objet HttpResponse où le résultat est enregistré. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lève pas d'exception si l'opération échoue.

### Voir également

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | Stream | Flux du fichier source. |
| pages | Int32[] | Tableau de pages à redimensionner. |
| parameters | ContentsResizeParameters | Redimensionner les paramètres. |
| response | HttpResponse | Objet HttpResponse où le résultat est enregistré. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lève pas d'exception si l'opération échoue.

### Voir également

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Redimensionne le contenu des pages du document.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | Stream | Diffusez avec le document source. |
| destination | Stream | Diffusez avec le document de destination. |
| pages | Int32[] | Tableau d'index de pages. |
| parameters | ContentsResizeParameters | Redimensionner les paramètres. |

### Return_Value

Renvoie vrai en cas de succès.

### Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //marge gauche = 10% de la largeur de la page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nouvelle largeur du contenu calculée automatiquement comme largeur - marge gauche - marge droite (100% - 10% - 10% = 80%)
    null,
    //la marge droite est de 10% de la page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //marge supérieure = 10% de la hauteur
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // la nouvelle hauteur du contenu est calculée automatiquement (similaire à la largeur)
    null,
    //la marge inférieure est de 10 %
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Voir également

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_2}

Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | Stream | Flux qui contient le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page dans les unités d'espace par défaut. |
| newHeight | Double | Nouvelle hauteur du contenu de la page dans les unités d'espace par défaut. |

### Return_Value

true si l'opération s'est terminée avec succès ; sinon, faux.

### Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
// redimensionner toutes les pages du document
null, 
//largeur du nouveau contenu = 200
200, 
// hauteur du nouveau contenu = 300
300);
// la zone de repos de la page sera vide
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_4}

Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | String | Chemin du document source. |
| destination | String | Chemin du document de destination. |
| pages | Int32[] | Tableau d'index de page (l'index de page commence à 1). |
| parameters | ContentsResizeParameters | Paramètres de redimensionnement de la page. |

### Return_Value

true si le redimensionnement a réussi.

### Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lève pas d'exception si l'opération échoue.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //marge gauche = 10% de la largeur de la page
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //nouvelle largeur du contenu calculée automatiquement comme largeur - marge gauche - marge droite (100% - 10% - 10% = 80%)
    null,
    //la marge droite est de 10% de la page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //marge supérieure = 10% de la hauteur
    PdfFileEditor.ContentsResizeValue.Percents(10),
    // la nouvelle hauteur du contenu est calculée automatiquement (similaire à la largeur)
    null,
    //la marge inférieure est de 10 %
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Voir également

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
