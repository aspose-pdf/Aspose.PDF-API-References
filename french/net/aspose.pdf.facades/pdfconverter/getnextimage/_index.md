---
title: "PdfConverter.GetNextImage"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PdfConverter. Enregistre l'image dans un fichier avec le format d'image par défaut jpeg"
type: docs
weight: 140
url: /fr/net/aspose.pdf.facades/pdfconverter/getnextimage/
---
## GetNextImage(string) {#getnextimage_9}

Enregistre l'image dans le fichier avec le format d'image par défaut - jpeg.

```csharp
public void GetNextImage(string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize) {#getnextimage_10}

Enregistre l'image dans le fichier avec la taille de page donnée et le format d'image par défaut - jpeg.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_13}

Enregistre l'image dans le fichier avec le format d'image fourni.

```csharp
public void GetNextImage(string outputFile, ImageFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |

## Exemples

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

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat) {#getnextimage_11}

Enregistre l'image dans le fichier avec la taille de page donnée et le format d'image.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |
| format | ImageFormat | Le format de l'image. |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Enregistre l'image dans le flux avec le format d'image par défaut - jpeg.

```csharp
public void GetNextImage(Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize) {#getnextimage_1}

Enregistre l'image dans le flux avec la taille de page spécifiée.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_4}

Enregistre l'image dans le flux avec le format d'image spécifié.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat) {#getnextimage_2}

Enregistre l'image dans le flux avec la taille de page spécifiée.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |
| format | ImageFormat | Le format de l'image. |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int, int) {#getnextimage_17}

Enregistre l'image dans le fichier avec le format d'image donné, les dimensions et la qualité.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Int32 | La largeur de l'image, l'unité est pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est pixel. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est la plus basse et 100 est la plus élevée |

## Exemples

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

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int, int) {#getnextimage_8}

Enregistre l'image dans le flux avec le format d'image donné, les dimensions et la qualité.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight, 
    int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Int32 | La largeur de l'image, l'unité est pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est pixel. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est la plus basse et 100 est la plus élevée |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, double, double, int) {#getnextimage_14}

Enregistre l'image dans le fichier avec le format d'image donné, la taille de l'image et la qualité.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Double | La largeur de l'image, l'unité est pixels. |
| imageHeight | Double | La hauteur de l'image, l'unité est pixels.. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est la plus basse et 100 est la plus élevée |

## Exemples

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

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, double, double, int) {#getnextimage_5}

Enregistre l'image dans le flux avec le format d'image donné, la taille et la qualité.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, double imageWidth, 
    double imageHeight, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Double | La largeur de l'image, l'unité est pixel. |
| imageHeight | Double | La hauteur de l'image, l'unité est pixel. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est la plus basse et 100 est la plus élevée |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int, int) {#getnextimage_16}

Enregistre l'image dans le fichier avec le format d'image donné et les dimensions.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int imageWidth, int imageHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Int32 | La largeur de l'image, l'unité est pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est pixel. |

## Exemples

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

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int, int) {#getnextimage_7}

Enregistre l'image dans le flux avec le format d'image donné, la taille et la qualité.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int imageWidth, int imageHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| imageWidth | Int32 | La largeur de l'image, l'unité est pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est pixel. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat, int) {#getnextimage_6}

Enregistre l'image dans le flux avec le format d'image donné et la qualité.

```csharp
public void GetNextImage(Stream outputStream, ImageFormat format, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est la plus basse et 100 est la plus élevée |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, PageSize, ImageFormat, int) {#getnextimage_3}

Enregistre l'image dans le flux avec la taille de page donnée, le format d'image et la qualité.

```csharp
public void GetNextImage(Stream outputStream, PageSize pageSize, ImageFormat format, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |
| format | ImageFormat | Le format de l'image. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est la plus basse et 100 est la plus élevée |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat, int) {#getnextimage_15}

Enregistre l'image dans le fichier avec le format d'image donné et la qualité.

```csharp
public void GetNextImage(string outputFile, ImageFormat format, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |
| format | ImageFormat | Le format de l'image. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est la plus basse et 100 est la plus élevée |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, PageSize, ImageFormat, int) {#getnextimage_12}

Enregistre l'image dans le fichier avec la taille de page donnée, le format d'image et la qualité.

```csharp
public void GetNextImage(string outputFile, PageSize pageSize, ImageFormat format, int quality)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le chemin d'accès et le nom du fichier pour enregistrer l'image. |
| pageSize | PageSize | La taille de page de l'image. |
| format | ImageFormat | Le format de l'image. |
| quality | Int32 | La qualité du fichier Jpeg (0~100), 0 est la plus basse et 100 est la plus élevée |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


