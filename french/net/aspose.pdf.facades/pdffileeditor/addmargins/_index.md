---
title: AddMargins
second_title: Référence de l'API Aspose.PDF pour .NET
description: Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées dans les unités despace par défaut.
type: docs
weight: 250
url: /fr/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées dans les unités d'espace par défaut.

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | String | Chemin d'accès au document source. |
| destination | String | Chemin où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, toutes les pages du document seront traitées. |
| leftMargin | Double | Marge de gauche. |
| rightMargin | Double | Marge droite. |
| topMargin | Double | Marge supérieure. |
| bottomMargin | Double | Marge inférieure. |

### Return_Value

true si le redimensionnement a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //traite les pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //la marge de gauche est de 10 unités
    10, 
    //la marge droite est de 5 unités
    5, 
    //la marge supérieure est de 5 unités
    5, 
    //la marge inférieure est de 5 unités
    5);
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

---

## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées dans les unités d'espace par défaut.

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| source | Stream | Flux qui contient le document source. |
| destination | Stream | Flux où le document résultant sera enregistré. |
| pages | Int32[] | Tableau d'index de pages. Si null, toutes les pages du document seront traitées. |
| leftMargin | Double | Marge de gauche. |
| rightMargin | Double | Marge droite. |
| topMargin | Double | Marge supérieure. |
| bottomMargin | Double | Marge inférieure. |

### Return_Value

true si l'opération a réussi.

### Exemples

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //traite les pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //la marge de gauche est de 10 unités
    10, 
    //la marge droite est de 5 unités
    5, 
    //la marge supérieure est de 5 unités
    5, 
    //la marge inférieure est de 5 unités
    5);
    dest.Close();
```

### Voir également

* class [PdfFileEditor](../../pdffileeditor)
* espace de noms [Aspose.Pdf.Facades](../../pdffileeditor)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->