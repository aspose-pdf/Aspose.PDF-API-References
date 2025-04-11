---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileEditor. Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont spécifiées en unités d'espace par défaut.
type: docs
weight: 220
url: /fr/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont spécifiées en unités d'espace par défaut.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | Stream | Flux qui contient le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau des index de pages. Si null, toutes les pages du document seront traitées. |
| leftMargin | Double | Marge gauche. |
| rightMargin | Double | Marge droite. |
| topMargin | Double | Marge supérieure. |
| bottomMargin | Double | Marge inférieure. |

### Valeur de retour

true si l'opération a réussi.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont spécifiées en unités d'espace par défaut.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| source | String | Chemin vers le document source. |
| destination | String | Chemin où le document résultant sera enregistré. |
| pages | Int32[] | Tableau des index de pages. Si null, toutes les pages du document seront traitées. |
| leftMargin | Double | Marge gauche. |
| rightMargin | Double | Marge droite. |
| topMargin | Double | Marge supérieure. |
| bottomMargin | Double | Marge inférieure. |

### Valeur de retour

true si le redimensionnement a réussi.

## Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### Voir aussi

* classe [PdfFileEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)