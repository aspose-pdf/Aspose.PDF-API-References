---
title: AddFooter
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajoute un pied de page aux pages du document.
type: docs
weight: 150
url: /fr/net/aspose.pdf.facades/pdffilestamp/addfooter/
---
## AddFooter(FormattedText, float) {#addfooter}

Ajoute un pied de page aux pages du document.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formattedText | FormattedText | Objet FormattedText qui contient le texte du pied de page et les propriétés de texte. |
| bottomMargin | Single | Marge en haut de page. |

### Exemples

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10);
```

### Voir également

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddFooter(FormattedText, float, float, float) {#addfooter_1}

Ajoute un pied de page aux pages du document.

```csharp
public void AddFooter(FormattedText formattedText, float bottomMargin, float leftMargin, 
    float rightMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formattedText | FormattedText | Objet FormattedText qui contient le texte du pied de page et les propriétés du texte. |
| bottomMargin | Single | Marge en bas de page. |
| leftMargin | Single | Marge sur le côté gauche de la page. |
| rightMargin | Single | Marge sur le côté droit de la page. |

### Exemples

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddFooter(new FormattedText("Foot of the page"), 10, 50, 50);
```

### Voir également

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddFooter(string, float) {#addfooter_4}

Ajoute une image comme pied de page aux pages du document.

```csharp
public void AddFooter(string imageFile, float bottomMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageFile | String | Nom et chemin du fichier image. |
| bottomMargin | Single | Marge en bas de page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddFooter(string, float, float, float) {#addfooter_5}

Ajoute une image en pied de page des pages.

```csharp
public void AddFooter(string imageFile, float bottomMargin, float leftMargin, float rightMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageFile | String | Iamge nom de fichier et chemin. |
| bottomMargin | Single | Marge en bas de page. |
| leftMargin | Single | Marge sur le côté gauche de la page. |
| rightMargin | Single | Marge sur le côté droit de la page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddFooter(Stream, float) {#addfooter_2}

Ajoute une image en pied de page.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageStream | Stream | Le flux contient des données d'image. |
| bottomMargin | Single | Marge en bas de page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddFooter(Stream, float, float, float) {#addfooter_3}

Ajoute une image en pied de page.

```csharp
public void AddFooter(Stream imageStream, float bottomMargin, float leftMargin, float rightMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageStream | Stream | Le flux contient des données d'image. |
| bottomMargin | Single | Marge en bas de page. |
| leftMargin | Single | Marge sur le côté gauche de la page. |
| rightMargin | Single | Marge sur le côté droit de la page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddFooter(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 50, 50);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
