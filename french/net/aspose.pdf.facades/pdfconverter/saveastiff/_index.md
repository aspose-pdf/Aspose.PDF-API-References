---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfConverter. Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF
type: docs
weight: 160
url: /fr/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le fichier pour enregistrer l'image TIFF. |

## Exemples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le fichier de sortie. |
| compressionType | CompressionType | Type de compression. |

## Exemples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### Voir aussi

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le nom du fichier pour enregistrer l'image TIFF |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le nom du fichier pour enregistrer l'image TIFF |
| pageSize | PageSize | La taille de page de l'image. |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le nom du fichier pour enregistrer l'image TIFF |
| pageSize | PageSize | La taille de page de l'image. |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le nom du fichier pour enregistrer l'image TIFF |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |
| compressionType | CompressionType | Type de compression. |

### Voir aussi

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le nom du fichier pour enregistrer l'image TIFF |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |

### Voir aussi

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le nom du fichier pour enregistrer l'image TIFF |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |
| converter | IIndexBitmapConverter | Convertisseur externe |

### Voir aussi

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux de sortie. |
| compressionType | CompressionType | Type de compression. |

### Voir aussi

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| pageSize | PageSize | La taille de page de l'image. |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| pageSize | PageSize | La taille de page de l'image. |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |

### Voir aussi

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |

### Voir aussi

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |
| compressionType | CompressionType | Type de compression. |

### Voir aussi

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |

### Voir aussi

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Convertit chaque page d'un document pdf en images avec des dimensions, et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |
| converter | IIndexBitmapConverter | Convertisseur externe |

### Voir aussi

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le nom du fichier pour enregistrer l'image TIFF |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |

### Voir aussi

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le nom du fichier pour enregistrer l'image TIFF |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |
| converter | IIndexBitmapConverter | Convertisseur externe |

### Voir aussi

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |

### Voir aussi

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| settings | TiffSettings | Objet de paramètres qui définit les paramètres TIFF. |
| converter | IIndexBitmapConverter | Convertisseur externe |

### Voir aussi

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)