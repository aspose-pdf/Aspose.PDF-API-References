---
title: AddImage
second_title: Référence de l'API Aspose.PDF pour .NET
description: Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées.
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

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageStream | Stream | Flux d'images d'entrée. |
| pageNum | Int32 | Le nombre de page qui recevra l'image. |
| lowerLeftX | Single | Le x inférieur gauche du rectangle de l'image. |
| lowerLeftY | Single | Le y inférieur gauche du rectangle de l'image. |
| upperRightX | Single | Le x supérieur droit du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit du rectangle de l'image. |

### Return_Value

Vrai si succès faux sinon.

### Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100);
}
mendor.Close();
```

### Voir également

* class [PdfFileMend](../../pdffilemend)
* espace de noms [Aspose.Pdf.Facades](../../pdffilemend)
* Assemblée [Aspose.PDF](../../../)

---

## AddImage(Stream, int, float, float, float, float, CompositingParameters) {#addimage_1}

Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(Stream imageStream, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageStream | Stream | Flux d'images d'entrée. |
| pageNum | Int32 | Le nombre de page qui recevra l'image. |
| lowerLeftX | Single | Le x inférieur gauche du rectangle de l'image. |
| lowerLeftY | Single | Le y inférieur gauche du rectangle de l'image. |
| upperRightX | Single | Le x supérieur droit du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit du rectangle de l'image. |
| compositingParameters | CompositingParameters | Les paramètres de composition graphique pour l'image. |

### Return_Value

Vrai si succès faux sinon.

### Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Voir également

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* espace de noms [Aspose.Pdf.Facades](../../pdffilemend)
* Assemblée [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float) {#addimage_2}

Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageStream | Stream | Flux d'images d'entrée. |
| pageNums | Int32[] | Le nombre de pages qui recevront l'image. |
| lowerLeftX | Single | Le x inférieur gauche du rectangle de l'image. |
| lowerLeftY | Single | Le y inférieur gauche du rectangle de l'image. |
| upperRightX | Single | Le x supérieur droit du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit du rectangle de l'image. |

### Return_Value

Vrai si succès faux sinon.

### Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100);
}
mendor.Close();
```

### Voir également

* class [PdfFileMend](../../pdffilemend)
* espace de noms [Aspose.Pdf.Facades](../../pdffilemend)
* Assemblée [Aspose.PDF](../../../)

---

## AddImage(Stream, int[], float, float, float, float, CompositingParameters) {#addimage_3}

Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(Stream imageStream, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageStream | Stream | Flux d'images d'entrée. |
| pageNums | Int32[] | Le nombre de pages qui recevront l'image. |
| lowerLeftX | Single | Le x inférieur gauche du rectangle de l'image. |
| lowerLeftY | Single | Le y inférieur gauche du rectangle de l'image. |
| upperRightX | Single | Le x supérieur droit du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit du rectangle de l'image. |
| compositingParameters | CompositingParameters | Les paramètres de composition graphique des images. |

### Return_Value

Vrai si succès faux sinon.

### Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
using (Stream stream = File.OpenRead("picture.jpg"))
{
    mendor.AddImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply);
}
mendor.Close();
```

### Voir également

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* espace de noms [Aspose.Pdf.Facades](../../pdffilemend)
* Assemblée [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float) {#addimage_4}

Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageName | String | Le chemin du fichier image d'entrée. |
| pageNum | Int32 | Le nombre de page qui recevra l'image. |
| lowerLeftX | Single | Le x inférieur gauche du rectangle de l'image. |
| lowerLeftY | Single | Le y inférieur gauche du rectangle de l'image. |
| upperRightX | Single | Le x supérieur droit du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit du rectangle de l'image. |

### Return_Value

Vrai si succès faux sinon.

### Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Voir également

* class [PdfFileMend](../../pdffilemend)
* espace de noms [Aspose.Pdf.Facades](../../pdffilemend)
* Assemblée [Aspose.PDF](../../../)

---

## AddImage(string, int, float, float, float, float, CompositingParameters) {#addimage_5}

Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(string imageName, int pageNum, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageName | String | Le chemin du fichier image d'entrée. |
| pageNum | Int32 | Le nombre de page qui recevra l'image. |
| lowerLeftX | Single | Le x inférieur gauche du rectangle de l'image. |
| lowerLeftY | Single | Le y inférieur gauche du rectangle de l'image. |
| upperRightX | Single | Le x supérieur droit du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit du rectangle de l'image. |
| compositingParameters | CompositingParameters | Les paramètres de composition graphique des images. |

### Return_Value

Vrai si succès faux sinon.

### Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Voir également

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* espace de noms [Aspose.Pdf.Facades](../../pdffilemend)
* Assemblée [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float) {#addimage_6}

Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageName | String | Le chemin du fichier image d'entrée. |
| pageNums | Int32[] | Le nombre de pages qui recevront l'image. |
| lowerLeftX | Single | Le x inférieur gauche du rectangle de l'image. |
| lowerLeftY | Single | Le y inférieur gauche du rectangle de l'image. |
| upperRightX | Single | Le x supérieur droit du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit du rectangle de l'image. |

### Return_Value

Vrai si succès faux sinon.

### Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100);
mendor.Close();
```

### Voir également

* class [PdfFileMend](../../pdffilemend)
* espace de noms [Aspose.Pdf.Facades](../../pdffilemend)
* Assemblée [Aspose.PDF](../../../)

---

## AddImage(string, int[], float, float, float, float, CompositingParameters) {#addimage_7}

Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées.

```csharp
public bool AddImage(string imageName, int[] pageNums, float lowerLeftX, float lowerLeftY, 
    float upperRightX, float upperRightY, CompositingParameters compositingParameters)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| imageName | String | Le chemin du fichier image d'entrée. |
| pageNums | Int32[] | Le nombre de pages qui recevront l'image. |
| lowerLeftX | Single | Le x inférieur gauche du rectangle de l'image. |
| lowerLeftY | Single | Le y inférieur gauche du rectangle de l'image. |
| upperRightX | Single | Le x supérieur droit du rectangle de l'image. |
| upperRightY | Single | Le coin supérieur droit du rectangle de l'image. |
| compositingParameters | CompositingParameters | Les paramètres de composition graphique des images. |

### Return_Value

Vrai si succès faux sinon.

### Exemples

```csharp
PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf");
mendor.AddImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply));
mendor.Close();
```

### Voir également

* class [CompositingParameters](../../../aspose.pdf/compositingparameters)
* class [PdfFileMend](../../pdffilemend)
* espace de noms [Aspose.Pdf.Facades](../../pdffilemend)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
