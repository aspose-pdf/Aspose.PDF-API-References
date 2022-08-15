---
title: GetNextImage
second_title: Référence de l'API Aspose.PDF pour .NET
description: Enregistre limage dans un fichier avec le format dimage par défaut - jpeg.
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Enregistre l'image dans un fichier avec le format d'image par défaut - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Enregistre l'image dans un fichier avec la taille de page donnée et le format d'image par défaut - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Enregistre l'image dans un fichier au format d'image givin.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |

### Exemples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".png";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".png" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Png)
	imageCount = imageCount + 1
End While
```

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Enregistre l'image dans un fichier avec une taille de page et un format d'image donnés.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |
| format | ImageFormat | Le format de l'image. |

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Enregistre l'image à diffuser avec le format d'image par défaut - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Enregistre l'image à diffuser avec une taille de page donnée.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Enregistre l'image à diffuser avec le format d'image donné.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Enregistre l'image à diffuser avec une taille de page donnée.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |
| format | ImageFormat | Le format de l'image. |

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Enregistre l'image dans un fichier avec le format d'image, les dimensions et la qualité donnés.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est le plus bas et 100 est le plus élevé |

### Exemples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50)
	imageCount = imageCount + 1
End While
```

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Enregistre l'image à diffuser avec le format, les dimensions et la qualité de l'image donnée.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est le plus bas et 100 est le plus élevé |

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Enregistre l'image dans un fichier avec le format d'image, la taille et la qualité de l'image.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Double | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Double | La hauteur de l'image, l'unité est le pixel. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est le plus bas et 100 est le plus élevé |

### Exemples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
float pixelX=800f;
float pixelY=600f;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim pixelX As float =800
Dim pixelY As float=600
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50)
	imageCount = imageCount + 1
End While
```

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Enregistre l'image à diffuser avec le format, la taille et la qualité de l'image donnée.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Double | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Double | La hauteur de l'image, l'unité est le pixel. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est le plus bas et 100 est le plus élevé |

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Enregistre l'image dans un fichier avec le format et les dimensions d'image donnés.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |

### Exemples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
String prefix = @"D:\Test\";
String suffix = ".jpg";
int imageCount = 1;
while (converter.HasNextImage())
{
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000);
	imageCount++;
}

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
Dim prefix As String =  "D:\Test\" 
Dim suffix As String =  ".jpg" 
Dim imageCount As Integer =  1 
While converter.HasNextImage()
	converter.GetNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000)
	imageCount = imageCount + 1
End While
```

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Enregistre l'image à diffuser avec le format, la taille et la qualité de l'image donnée.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Enregistre l'image à diffuser avec un format et une qualité d'image donnés.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est le plus bas et 100 est le plus élevé |

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Enregistre l'image à diffuser avec une taille de page, un format d'image et une qualité donnés.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |
| format | ImageFormat | Le format de l'image. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est le plus bas et 100 est le plus élevé |

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Enregistre l'image dans un fichier avec un format et une qualité d'image donnés.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est le plus bas et 100 est le plus élevé |

### Voir également

* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Enregistre l'image dans un fichier avec une taille de page, un format d'image et une qualité donnés.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| outputFile | String | Le chemin et le nom du fichier pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |
| format | ImageFormat | Le format de l'image. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est le plus bas et 100 est le plus élevé |

### Voir également

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* espace de noms [Aspose.Pdf.Facades](../../pdfconverter)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
