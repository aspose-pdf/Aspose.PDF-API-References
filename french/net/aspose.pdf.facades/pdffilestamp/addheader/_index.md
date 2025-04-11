---
title: PdfFileStamp.AddHeader
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileStamp. Ajoute un en-tête à la page
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/pdffilestamp/addheader/
---
## AddHeader(FormattedText, float) {#addheader}

Ajoute un en-tête à la page.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Texte pour l'en-tête et propriétés du texte. |
| topMargin | Single | Marge en haut de la page. |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddHeader(new FormattedText("Head of the page"), 50);
fileStamp.Close();
```

### Voir aussi

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(FormattedText, float, float, float) {#addheader_1}

Ajoute un en-tête aux pages du fichier.

```csharp
public void AddHeader(FormattedText formattedText, float topMargin, float leftMargin, 
    float rightMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Objet de texte formaté qui contient le texte de la page et ses propriétés. |
| topMargin | Single | Marge en haut de la page. |
| leftMargin | Single | Marge à gauche de la page. |
| rightMargin | Single | Marge à droite de la page. |

## Exemples

```csharp
PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf");
stamp.AddHeader(new FormattedText("Head of the page"), 10, 50, 50);
```

### Voir aussi

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float) {#addheader_4}

Ajoute une image comme en-tête aux pages du fichier.

```csharp
public void AddHeader(string imageFile, float topMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageFile | String | Chemin vers le fichier image. |
| topMargin | Single | Marge en haut de la page. |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50);
fileStamp.Close();
```

### Voir aussi

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(string, float, float, float) {#addheader_5}

Ajoute une image comme en-tête sur les pages.

```csharp
public void AddHeader(string imageFile, float topMargin, float leftMargin, float rightMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageFile | String | Chemin vers le fichier image. |
| topMargin | Single | Marge en haut de la page. |
| leftMargin | Single | Marge à gauche de la page. |
| rightMargin | Single | Marge à droite de la page. |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader("image.jpg", 50, 100, 100);
fileStamp.Close();
```

### Voir aussi

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float) {#addheader_2}

Ajoute une image comme en-tête sur les pages.

```csharp
public void AddHeader(Stream imageStream, float topMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Flux de l'image. |
| topMargin | Single | Marge en haut de la page. |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50);
fileStamp.Close();
```

### Voir aussi

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddHeader(Stream, float, float, float) {#addheader_3}

Ajoute une image en haut de la page.

```csharp
public void AddHeader(Stream inputStream, float topMargin, float leftMargin, float rightMargin)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputStream | Stream | Flux qui contient les données de l'image. |
| topMargin | Single | Marge en haut de la page. |
| leftMargin | Single | Marge à gauche de la page. |
| rightMargin | Single | Marge à droite de la page. |

## Exemples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf");
Stream input = new FileStream(TestSettings.GetInputFile("test.jpg"), FileMode.Open, FileAccess.Read);
fileStamp.AddHeader(new FileStream("image.jpg", FileMode.Open, FileAccess.Read), 50, 100, 100);
fileStamp.Close();
```

### Voir aussi

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)