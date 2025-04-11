---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées en pourcentages de la taille initiale de la page.
type: docs
weight: 230
url: /fr/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées en pourcentages de la taille initiale de la page.

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux qui contient le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau des index de page. Si null, toutes les pages du document seront traitées. |
| leftMargin | Double | Marge gauche en pourcentages de la taille initiale de la page. |
| rightMargin | Double | Marge droite en pourcentages de la taille initiale de la page. |
| topMargin | Double | Marge supérieure en pourcentages de la taille initiale de la page. |
| bottomMargin | Double | Marge inférieure en pourcentages de la taille initiale de la page. |

### Valeur de retour

true si l'action a été effectuée avec succès.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées en pourcentages de la taille initiale de la page.

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | String | Chemin vers le document source. |
| destination | String | Chemin où le document résultant sera enregistré. |
| pages | Int32[] | Tableau des index de page. Si null, toutes les pages du document seront traitées. |
| leftMargin | Double | Marge gauche en pourcentages de la taille initiale de la page. |
| rightMargin | Double | Marge droite en pourcentages de la taille initiale de la page. |
| topMargin | Double | Marge supérieure en pourcentages de la taille initiale de la page. |
| bottomMargin | Double | Marge inférieure en pourcentages de la taille initiale de la page. |

### Valeur de retour

true si le redimensionnement a réussi

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)