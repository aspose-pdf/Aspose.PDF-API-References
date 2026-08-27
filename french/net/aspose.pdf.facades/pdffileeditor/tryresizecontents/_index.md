---
title: "PdfFileEditor.TryResizeContents"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Redimensionne le contenu des pages du document"
type: docs
weight: 450
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Redimensionne le contenu des pages du document.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux contenant le document source. |
| destination | Stream | Flux contenant le document de destination. |
| pages | Int32[] | Tableau d'index de pages. |
| paramètres | ContentsResizeParameters | Paramètres de redimensionnement. |

### Valeur de retour

Renvoie true si succès.

## Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lève pas d'exception si l'opération échoue.

## Exemples

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
    //la hauteur du nouveau contenu est calculée automatiquement (similaire à la largeur)
    null,
    //la marge inférieure est de 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### Voir aussi

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en unités d'espace par défaut.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux contenant le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, alors toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page en unités d'espace par défaut. |
| newHeight | Double | Nouvelle hauteur du contenu de la page en unités d'espace par défaut. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lève pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//redimensionner toutes les pages du document
null, 
//largeur du nouveau contenu = 200
200, 
//hauteur du nouveau contenu = 300
300);
// la zone restante de la page sera vide
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Redimensionne le contenu des pages du document. Si la page est réduite, des marges blanches sont ajoutées autour de la page.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | String | Chemin du document source. |
| destination | String | Chemin du document de destination. |
| pages | Int32[] | Tableau d'index de pages (l'index de page commence à 1). |
| paramètres | ContentsResizeParameters | Paramètres du redimensionnement de page. |

### Valeur de retour

true si le redimensionnement a réussi.

## Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lève pas d'exception si l'opération échoue.

## Exemples

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
    //la hauteur du nouveau contenu est calculée automatiquement (similaire à la largeur)
    null,
    //la marge inférieure est de 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Voir aussi

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


