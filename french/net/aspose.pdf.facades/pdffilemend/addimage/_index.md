---
title: PdfFileMend.AddImage
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfFileMend. Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées
type: docs
weight: 50
url: /fr/net/aspose.pdf.facades/pdffilemend/addimage/
---
## AddImage(Stream, int, float, float, float, float) {#addimage}

Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Flux d'image d'entrée. |
| pageNum | Int32 | Le numéro de la page qui recevra l'image. |
| lowerLeftX | Single | Le coin inférieur gauche x du rectangle de l'image. |
| lowerLeftY | Single | Le coin inférieur gauche y du rectangle de l'image. |
| upperRightX | Single | Le coin supérieur droit x du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit y du rectangle de l'image. |

### Valeur de retour

Vrai si succès, faux sinon.

## Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Voir aussi

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Flux d'image d'entrée. |
| pageNum | Int32 | Le numéro de la page qui recevra l'image. |
| lowerLeftX | Single | Le coin inférieur gauche x du rectangle de l'image. |
| lowerLeftY | Single | Le coin inférieur gauche y du rectangle de l'image. |
| upperRightX | Single | Le coin supérieur droit x du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit y du rectangle de l'image. |
| compositingParameters | CompositingParameters | Les paramètres de composition graphique pour l'image. |

### Valeur de retour

Vrai si succès, faux sinon.

## Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Voir aussi

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Flux d'image d'entrée. |
| pageNums | Int32[] | Les numéros des pages qui recevront l'image. |
| lowerLeftX | Single | Le coin inférieur gauche x du rectangle de l'image. |
| lowerLeftY | Single | Le coin inférieur gauche y du rectangle de l'image. |
| upperRightX | Single | Le coin supérieur droit x du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit y du rectangle de l'image. |

### Valeur de retour

Vrai si succès, faux sinon.

## Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Voir aussi

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageStream | Stream | Flux d'image d'entrée. |
| pageNums | Int32[] | Les numéros des pages qui recevront l'image. |
| lowerLeftX | Single | Le coin inférieur gauche x du rectangle de l'image. |
| lowerLeftY | Single | Le coin inférieur gauche y du rectangle de l'image. |
| upperRightX | Single | Le coin supérieur droit x du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit y du rectangle de l'image. |
| compositingParameters | CompositingParameters | Les paramètres de composition graphique pour les images. |

### Valeur de retour

Vrai si succès, faux sinon.

## Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Voir aussi

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageName | String | Le chemin du fichier image d'entrée. |
| pageNum | Int32 | Le numéro de la page qui recevra l'image. |
| lowerLeftX | Single | Le coin inférieur gauche x du rectangle de l'image. |
| lowerLeftY | Single | Le coin inférieur gauche y du rectangle de l'image. |
| upperRightX | Single | Le coin supérieur droit x du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit y du rectangle de l'image. |

### Valeur de retour

Vrai si succès, faux sinon.

## Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Voir aussi

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageName | String | Le chemin du fichier image d'entrée. |
| pageNum | Int32 | Le numéro de la page qui recevra l'image. |
| lowerLeftX | Single | Le coin inférieur gauche x du rectangle de l'image. |
| lowerLeftY | Single | Le coin inférieur gauche y du rectangle de l'image. |
| upperRightX | Single | Le coin supérieur droit x du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit y du rectangle de l'image. |
| compositingParameters | CompositingParameters | Les paramètres de composition graphique pour les images. |

### Valeur de retour

Vrai si succès, faux sinon.

## Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Voir aussi

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageName | String | Le chemin du fichier image d'entrée. |
| pageNums | Int32[] | Les numéros des pages qui recevront l'image. |
| lowerLeftX | Single | Le coin inférieur gauche x du rectangle de l'image. |
| lowerLeftY | Single | Le coin inférieur gauche y du rectangle de l'image. |
| upperRightX | Single | Le coin supérieur droit x du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit y du rectangle de l'image. |

### Valeur de retour

Vrai si succès, faux sinon.

## Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Voir aussi

* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| imageName | String | Le chemin du fichier image d'entrée. |
| pageNums | Int32[] | Les numéros des pages qui recevront l'image. |
| lowerLeftX | Single | Le coin inférieur gauche x du rectangle de l'image. |
| lowerLeftY | Single | Le coin inférieur gauche y du rectangle de l'image. |
| upperRightX | Single | Le coin supérieur droit x du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit y du rectangle de l'image. |
| compositingParameters | CompositingParameters | Les paramètres de composition graphique pour les images. |

### Valeur de retour

Vrai si succès, faux sinon.

## Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Voir aussi

* class [CompositingParameters](../../../aspose.pdf/compositingparameters/)
* class [PdfFileMend](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)