---
title: AddHeader
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajoute un en-tête à la page.
type: docs
weight: 160
url: /fr/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Ajoute un en-tête à la page.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formattedText | FormattedText | Texte pour l'en-tête et propriétés du texte. |
| topMargin | Single | Marge en haut de page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Voir également

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Ajoute un en-tête aux pages du fichier.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| formattedText | FormattedText | Objet texte formaté qui contient le texte de la page et ses propriétés. |
| topMargin | Single | Marge en haut de la page. |
| leftMargin | Single | Marge à gauche de la page. |
| rightMargin | Single | Marge à droite de la page. |

### Exemples

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Voir également

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Ajoute une image comme en-tête aux pages du fichier.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageFile | String | Chemin d'accès au fichier image. |
| topMargin | Single | Marge en haut de la page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Ajoute une image comme en-tête sur les pages.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageFile | String | Chemin d'accès au fichier image. |
| topMargin | Single | Marge en haut de la page. |
| leftMargin | Single | Marge à gauche de la page. |
| rightMargin | Single | Marge à droite de la page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Ajoute une image comme en-tête sur les pages.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageStream | Stream | Flux de l'image. |
| topMargin | Single | Marge en haut de la page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Ajoute une image en haut de la page.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| inputStream | Stream | Flux qui contient des données d'image. |
| topMargin | Single | Marge en haut de la page. |
| leftMargin | Single | Marge à gauche de la page. |
| rightMargin | Single | Marge à droite de la page. |

### Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Voir également

* class [PdfFileStamp](../../pdffilestamp)
* espace de noms [Aspose.Pdf.Facades](../../pdffilestamp)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
