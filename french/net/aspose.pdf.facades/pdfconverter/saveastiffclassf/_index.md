---
title: PdfConverter.SaveAsTIFFClassF
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfConverter. Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/pdfconverter/saveastiffclassf/
---
## SaveAsTIFFClassF(string, int, int) {#saveastiffclassf_5}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, int imageWidth, int imageHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le flux pour enregistrer l'image TIFF. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |

## Exemples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196);	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff",204,196)
```

### Voir aussi

* classe [PdfConverter](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string, PageSize) {#saveastiffclassf_4}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le flux pour enregistrer l'image TIFF. |
| pageSize | PageSize | La taille de la page de l'image. |

### Voir aussi

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, int, int) {#saveastiffclassf_2}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, int imageWidth, int imageHeight)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| imageWidth | Int32 | La largeur de l'image, l'unité est le pixel. |
| imageHeight | Int32 | La hauteur de l'image, l'unité est le pixel. |

### Voir aussi

* classe [PdfConverter](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream, PageSize) {#saveastiffclassf_1}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream, PageSize pageSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |
| pageSize | PageSize | La taille de la page de l'image. |

### Voir aussi

* classe [PageSize](../../../aspose.pdf/pagesize/)
* classe [PdfConverter](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(string) {#saveastiffclassf_3}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(string outputFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFile | String | Le flux pour enregistrer l'image TIFF. |

## Exemples

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFFClassF(@"D:\Test\test.tiff")
```

### Voir aussi

* classe [PdfConverter](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFFClassF(Stream) {#saveastiffclassf}

Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF.

```csharp
public void SaveAsTIFFClassF(Stream outputStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Le flux pour enregistrer l'image TIFF. |

### Voir aussi

* classe [PdfConverter](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)