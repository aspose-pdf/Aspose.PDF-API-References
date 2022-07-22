---
title: AddPageNumber
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajouter le numéro de page au fichier. Le texte du numéro de page peut contenir le signe  qui sera remplacé par le numéro de la page. Le numéro de page est placé en bas de la page centré horizontalement.
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Ajouter le numéro de page au fichier. Le texte du numéro de page peut contenir le signe # qui sera remplacé par le numéro de la page. Le numéro de page est placé en bas de la page centré horizontalement.

```csharp
public void AddPageNumber(string formatString)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formatString | String | Texte du numéro de page |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Ajoute un numéro de page à la page. Le numéro de page peut contenir le signe # qui sera remplacé par le numéro de page. Le numéro de page est placé en bas de la page centré horizontalement.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formattedText | FormattedText | Chaîne de format pour le numéro de page représenté comme FormattedText. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Voir également

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Ajoute un numéro de page aux pages du document.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formatString | String | Chaîne de format pour le numéro de page. |
| position | Int32 | Position où le numéro de page sera placé sur la page. 0-bas milieu, 1-bas droite, 2-haut droite, 3 - côtés droit, 4 - haut milieu,5 - bas gauche,6 - côtés gauche,7 - haut gauche. Vous pouvez utiliser les constantes suivantes : PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Marge sur le bord gauche de la page. |
| rightMargin | Single | Marge sur le bord droit de la page. |
| topMargin | Single | Marge sur le bord supérieur de la page. |
| bottomMargin | Single | Marge sur le bord inférieur de la page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Ajoute un numéro de page à la position spécifiée sur la page.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formatString | String | Formater la chaîne. La chaîne de format peut contenir le signe # qui sera remplacé par le numéro de page. |
| x | Single | Coordonnée X du numéro de page. |
| y | Single | Coordonnée Y du numéro de page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Ajoute un numéro de page aux pages du document.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formattedText | FormattedText | Objet FormattedText qui représente le format du numéro de page et les propriétés du texte. |
| position | Int32 | Position où le numéro de page sera placé sur la page. 0-bas milieu, 1-bas droite, 2-haut droite, 3 - côtés droit, 4 - haut milieu,5 - bas gauche,6 - côtés gauche,7 - haut gauche. Vous pouvez utiliser les constantes suivantes : PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Marge sur le bord gauche de la page. |
| rightMargin | Single | Marge sur le bord droit de la page. |
| topMargin | Single | Marge sur le bord supérieur de la page. |
| bottomMargin | Single | Marge sur le bord inférieur de la page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Voir également

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Ajoute un numéro de page à la position spécifiée sur la page.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formattedText | FormattedText | Texte formaté qui représente le format du numéro de page et les propriétés du texte. La chaîne de format peut contenir le signe # qui sera remplacé par le numéro de page. |
| x | Single | Coordonnée X du numéro de page. |
| y | Single | Coordonnée Y du numéro de page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Voir également

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Ajoute un numéro de page aux pages.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formatString | String | Format du numéro de page. Ce texte peut contenir # qui sera remplacé par le numéro de page. |
| position | Int32 | Position où le numéro de page sera placé sur la page. 0-bas milieu, 1-bas droite, 2-haut droite, 3 - côtés droit, 4 - haut milieu,5 - bas gauche,6 - côtés gauche,7 - haut gauche. Vous pouvez utiliser les constantes suivantes : PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Ajoute un numéro de page aux pages.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formattedText | FormattedText | Objet FormattedText qui contient le format du numéro de page et les propriétés du texte. Ce texte peut contenir # qui sera remplacé par le numéro de page. |
| position | Int32 | Position où le numéro de page sera placé sur la page. 0-bas milieu, 1-bas droite, 2-haut droite, 3 - côtés droit, 4 - haut milieu,5 - bas gauche,6 - côtés gauche,7 - haut gauche. Vous pouvez utiliser les constantes suivantes : PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Voir également

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
