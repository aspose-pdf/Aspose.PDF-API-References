---
title: ResizeContents
second_title: Référence de l'API Aspose.PDF pour .NET
description: Redimensionne le contenu des pages du document. Si la page est réduite des marges vierges sont ajoutées autour de la page.
type: docs
weight: 350
url: /fr/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_4}

Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
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
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### Voir également

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_7}

Redimensionne les pages du document. Des marges vierges sont ajoutées autour de la page réduite.

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | Document | Documents sources. |
| pages | Int32[] | Liste des index de pages. |
| parameters | ContentsResizeParameters | Redimensionner les paramètres. |

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### Voir également

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_6}

Redimensionne les pages du document. Des marges vierges sont ajoutées autour de la page réduite.

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | Document | Documents sources. |
| parameters | ContentsResizeParameters | Redimensionner les paramètres. |

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### Voir également

* class [Document](../../../aspose.pdf/document)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents_1}

Redimensionne le contenu des pages du document.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
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
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### Voir également

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_2}

Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut.

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

Vrai si le redimensionnement a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
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

## ResizeContents(string, string, int[], double, double) {#resizecontents_5}

Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut.

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | String | Chemin d'accès au document source. |
| destination | String | Chemin où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page dans les unités d'espace par défaut. |
| newHeight | Double | Nouvelle hauteur du contenu de la page dans les unités d'espace par défaut. |

### Return_Value

true si le redimensionnement a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
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

## ResizeContents(string, int[], ContentsResizeParameters, HttpResponse) {#resizecontents_3}

Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse.

```csharp
public bool ResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | String | Chemin d'accès au fichier source. |
| pages | Int32[] | Tableau de pages à redimensionner. |
| parameters | ContentsResizeParameters | Redimensionner les paramètres. |
| response | HttpResponse | Objet HttpResponse où le résultat est enregistré. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## ResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#resizecontents}

Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse.

```csharp
public bool ResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | Stream | Flux du fichier source. |
| pages | Int32[] | Tableau de pages à redimensionner. |
| parameters | ContentsResizeParameters | Redimensionner les paramètres. |
| response | HttpResponse | Objet HttpResponse où le résultat est enregistré. |

### Return_Value

Vrai si l'opération a réussi.

### Voir également

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters)
* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
