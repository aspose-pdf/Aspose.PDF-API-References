---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Redimensionne le contenu des pages du document
type: docs
weight: 450
url: /fr/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

Redimensionne le contenu des pages dans le document. Si la page est réduite, des marges blanches sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse.

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | String | Chemin vers le fichier source. |
| pages | Int32[] | Tableau des pages à redimensionner. |
| parameters | ContentsResizeParameters | Paramètres de redimensionnement. |
| response | HttpResponse | Objet HttpResponse où le résultat est enregistré. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lance pas d'exception si l'opération échoue.

### Voir aussi

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

Redimensionne le contenu des pages dans le document. Si la page est réduite, des marges blanches sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse.

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux du fichier source. |
| pages | Int32[] | Tableau des pages à redimensionner. |
| parameters | ContentsResizeParameters | Paramètres de redimensionnement. |
| response | HttpResponse | Objet HttpResponse où le résultat est enregistré. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lance pas d'exception si l'opération échoue.

### Voir aussi

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

Redimensionne le contenu des pages du document.

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux avec le document source. |
| destination | Stream | Flux avec le document de destination. |
| pages | Int32[] | Tableau des index de pages. |
| parameters | ContentsResizeParameters | Paramètres de redimensionnement. |

### Valeur de retour

Retourne true si succès.

## Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
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
| source | Stream | Flux qui contient le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau des index de pages. Si null, toutes les pages du document seront traitées. |
| newWidth | Double | Nouvelle largeur du contenu de la page en unités d'espace par défaut. |
| newHeight | Double | Nouvelle hauteur du contenu de la page en unités d'espace par défaut. |

### Valeur de retour

true si l'opération s'est terminée avec succès ; sinon, false.

## Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

Redimensionne le contenu des pages dans le document. Si la page est réduite, des marges blanches sont ajoutées autour de la page.

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | String | Chemin du document source. |
| destination | String | Chemin du document de destination. |
| pages | Int32[] | Tableau des index de pages (l'index de page commence à 1). |
| parameters | ContentsResizeParameters | Paramètres de redimensionnement de la page. |

### Valeur de retour

true si le redimensionnement a réussi.

## Remarques

La méthode TryResizeContents est similaire à la méthode ResizeContents, sauf que la méthode TryResizeContents ne lance pas d'exception si l'opération échoue.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### Voir aussi

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)