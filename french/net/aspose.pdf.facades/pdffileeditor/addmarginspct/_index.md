---
title: "PdfFileEditor.AddMarginsPct"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfFileEditor. Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentage de la taille initiale de la page"
type: docs
weight: 230
url: /fr/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentage de la taille initiale de la page.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux contenant le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, alors toutes les pages du document seront traitées. |
| leftMargin | Double | Marge gauche en pourcentage de la taille initiale de la page. |
| rightMargin | Double | Marge droite en pourcentage de la taille initiale de la page. |
| topMargin | Double | Marge supérieure en pourcentage de la taille initiale de la page. |
| bottomMargin | Double | Marge inférieure en pourcentage de la taille initiale de la page. |

### Valeur de retour

Vrai si l'action a été exécutée avec succès.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //traiter les pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //la marge gauche est de 15 % de la largeur de la page
    15, 
    //la marge droite est de 10 % de la largeur de la page
    10, 
    //la marge supérieure est de 20 % de la largeur de la page
    20, 
    //la marge inférieure est de 5 % de la largeur de la page
    5);
    dest.Close();
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentage de la taille initiale de la page.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | String | Chemin vers le document source. |
| destination | String | Chemin où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, alors toutes les pages du document seront traitées. |
| leftMargin | Double | Marge gauche en pourcentage de la taille initiale de la page. |
| rightMargin | Double | Marge droite en pourcentage de la taille initiale de la page. |
| topMargin | Double | Marge supérieure en pourcentage de la taille initiale de la page. |
| bottomMargin | Double | Marge inférieure en pourcentage de la taille initiale de la page. |

### Valeur de retour

Vrai si le redimensionnement a réussi

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //traiter les pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //la marge gauche est de 15 % de la largeur de la page
    15, 
    //la marge droite est de 10 % de la largeur de la page
    10, 
    //la marge supérieure est de 20 % de la largeur de la page
    20, 
    //la marge inférieure est de 5 % de la largeur de la page
    5);
```

### Voir aussi

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


