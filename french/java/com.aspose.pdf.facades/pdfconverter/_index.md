---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant de convertir chaque page d'un fichier pdf en images, prenant désormais en charge BMP, JPEG, PNG et TIFF. Contenu pris en charge dans les pdf : images, formulaires, commentaires."
type: docs
weight: 390
url: /fr/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

Représente une classe pour convertir chaque page d'un fichier PDF en images, prenant actuellement en charge BMP, JPEG, PNG et TIFF. Contenu pris en charge dans les PDF : images, formulaires, commentaires.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Initialise un nouvel objet {@code PdfConverter}. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Initialise un nouvel objet {@code PdfConverter}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Lie un document PDF à l'instance {@link PdfConverter} pour un traitement ultérieur. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Lie un flux Pdf pour la conversion. |
| [bindPdf](#bindPdf-java.lang.String-) | Lie un fichier Pdf pour la conversion. |
| [close](#close--) | Ferme l'instance de PdfConverter et libère les ressources. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | À usage interne uniquement |
| [dispose](#dispose--) | Ferme l'instance de PdfConverter et libère les ressources. Cette méthode est obsolète, utilisez close() à la place. |
| [doConvert](#doConvert--) | <p> Effectuez quelques travaux initiaux pour convertir un document pdf en images. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Obtient le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [getEndPage](#getEndPage--) | Obtient la position de fin que vous souhaitez convertir. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtient le mode de présentation du formulaire. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Enregistre l'image dans le flux avec le format d'image par défaut - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Enregistre l'image dans le flux avec le format d'image spécifié. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Enregistre l'image dans le flux avec le format d'image donné, la taille et la qualité. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Enregistre l'image dans le flux avec le format d'image et la qualité spécifiés. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Enregistre l'image dans le flux avec le format d'image donné, la taille et la qualité. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Enregistre l'image dans le flux avec le format d'image donné, les dimensions et la qualité. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Enregistre l'image dans le flux avec la taille de page spécifiée. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Enregistre l'image dans le flux avec la taille de page spécifiée. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Enregistre l'image dans le flux avec la taille de page, le format d'image et la qualité spécifiés. |
| [getNextImage](#getNextImage-java.lang.String-) | Enregistre l'image dans le fichier avec le format d'image par défaut - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Enregistre l'image dans le fichier avec le format d'image donné. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Enregistre l'image dans un fichier avec le format d'image donné, la taille de l'image et la qualité. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Enregistre l'image dans un fichier avec le format d'image donné et la qualité. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Enregistre l'image dans un fichier avec le format d'image donné et les dimensions. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Enregistre l'image dans un fichier avec le format d'image donné, les dimensions et la qualité. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Enregistre l'image dans un fichier avec la taille de page donnée et le format d'image par défaut - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Enregistre l'image dans un fichier avec la taille de page donnée et le format d'image. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Enregistre l'image dans un fichier avec la taille de page donnée, le format d'image et la qualité. |
| [getPageCount](#getPageCount--) | Obtient le nombre de pages. |
| [getPassword](#getPassword--) | Obtient le OwnerPassword du document. |
| [getRenderingOptions](#getRenderingOptions--) | Obtient les options de rendu. |
| [getResolution](#getResolution--) | Obtient la résolution pendant la conversion. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 150. |
| [getStartPage](#getStartPage--) | Obtient la position de départ que vous souhaitez convertir. La valeur minimale est 1. |
| [getUserPassword](#getUserPassword--) | Obtient le UserPassword du document. |
| [hasNextImage](#hasNextImage--) | Indique si le fichier pdf possède d'autres images ou non. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Obtient le drapeau qui contrôle la visibilité des zones cachées sur la page. La méthode est obsolète. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Fusionne la liste des flux d'images en un seul flux d'images. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Fusionne la liste des flux tiff en un seul flux tiff à plusieurs images. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Convertit chaque page d'un document pdf en images avec la taille de page, et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Convertit chaque page d'un document pdf en images avec la taille de page, et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Convertit chaque page d'un document pdf en images avec et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Convertit chaque page d'un document pdf en images avec et enregistre les images dans un seul fichier TIFF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [setEndPage](#setEndPage-int-) | Définit la position de fin que vous souhaitez convertir. utilisez setEndPage(int) avant setStartPage(int) |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Définit le mode de présentation du formulaire. |
| [setPassword](#setPassword-java.lang.String-) | Définit le OwnerPassword du document. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Définit la plage de pages entre lesquelles vous souhaitez convertir. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Définit les options de rendu. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Définit la résolution pendant la conversion. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Obsolète. |
| [setStartPage](#setStartPage-int-) | Définit la position de départ que vous souhaitez convertir. La valeur minimale est 1. utilisez setEndPage(int) avant setStartPage(int) |
| [setUserPassword](#setUserPassword-java.lang.String-) | Définit le UserPassword du document. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Initialise un nouvel objet {@code PdfConverter}.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Initialise un nouvel objet {@code PdfConverter}.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Lie un document PDF à l'instance {@link PdfConverter} pour un traitement ultérieur.

### bindPdf {#bindPdf-java.io.InputStream-}
Lie un flux Pdf pour la conversion.

### bindPdf {#bindPdf-java.lang.String-}
Lie un fichier Pdf pour la conversion.

### close {#close--}
```
public void close()
```

Ferme l'instance de PdfConverter et libère les ressources.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
À usage interne uniquement

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Ferme l'instance de PdfConverter et libère les ressources. Cette méthode est obsolète, utilisez close() à la place.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Effectuez quelques travaux initiaux pour convertir un document pdf en images. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtient le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut.

**Returns:**
PageCoordinateType élément @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Obtient la position de fin que vous souhaitez convertir.

**Returns:**
valeur int

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtient le mode de présentation du formulaire.

**Returns:**
mode de présentation du formulaire. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Enregistre l'image dans le flux avec le format d'image par défaut - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Enregistre l'image dans le flux avec le format d'image spécifié.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Enregistre l'image dans le flux avec le format d'image donné, la taille et la qualité.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Enregistre l'image dans le flux avec le format d'image et la qualité spécifiés.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Enregistre l'image dans le flux avec le format d'image donné, la taille et la qualité.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Enregistre l'image dans le flux avec le format d'image donné, les dimensions et la qualité.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Enregistre l'image dans le flux avec la taille de page spécifiée.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Enregistre l'image dans le flux avec la taille de page spécifiée.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Enregistre l'image dans le flux avec la taille de page, le format d'image et la qualité spécifiés.

### getNextImage {#getNextImage-java.lang.String-}
Enregistre l'image dans le fichier avec le format d'image par défaut - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Enregistre l'image dans un fichier avec le format d'image donné. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Enregistre l'image dans un fichier avec le format d'image donné, la taille de l'image et la qualité. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Enregistre l'image dans un fichier avec le format d'image donné et la qualité.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Enregistre l'image dans un fichier avec le format d'image donné et les dimensions. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Enregistre l'image dans un fichier avec le format d'image donné, les dimensions et la qualité. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Enregistre l'image dans un fichier avec la taille de page donnée et le format d'image par défaut - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Enregistre l'image dans un fichier avec la taille de page donnée et le format d'image.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Enregistre l'image dans un fichier avec la taille de page donnée, le format d'image et la qualité.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Obtient le nombre de pages.

**Returns:**
valeur int

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtient le OwnerPassword du document.

**Returns:**
valeur String

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Obtient les options de rendu.

**Returns:**
options de rendu.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtient la résolution pendant la conversion. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 150.

**Returns:**
Élément de résolution

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Obtient la position de départ que vous souhaitez convertir. La valeur minimale est 1.

**Returns:**
valeur int

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Obtient le UserPassword du document.

**Returns:**
valeur String

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

Indique si le fichier pdf possède d'autres images ou non.

**Returns:**
Peut obtenir plus d'images ou non, vrai si possible, sinon faux.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Obtient le drapeau qui contrôle la visibilité des zones cachées sur la page. La méthode est obsolète.

**Returns:**
valeur booléenne

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Fusionne la liste des flux d'images en un seul flux d'images.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Fusionne la liste des flux tiff en un seul flux tiff à plusieurs images.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Convertit chaque page d'un document pdf en images avec la taille de page, et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Convertit chaque page d'un document pdf en images avec la taille de page, et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul fichier TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul fichier TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul fichier TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Convertit chaque page d'un document pdf en images avec dimensions, et enregistre les images dans un seul fichier TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Convertit chaque page d'un document pdf en images avec la taille de page et enregistre les images dans un seul fichier TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
Convertit chaque page d'un document pdf en images avec et enregistre les images dans un seul fichier TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Convertit chaque page d'un document pdf en images avec et enregistre les images dans un seul fichier TIFF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\Test\\test.tiff\",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Définit la position de fin que vous souhaitez convertir. utilisez setEndPage(int) avant setStartPage(int)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Définit le mode de présentation du formulaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | mode de présentation du formulaire. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Définit le OwnerPassword du document.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Définit la plage de pages entre lesquelles vous souhaitez convertir.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| startPage |  | valeur int |
| EndPage |  | valeur int |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Définit les options de rendu.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Définit la résolution pendant la conversion. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Obsolète.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Définit la position de départ que vous souhaitez convertir. La valeur minimale est 1. utilisez setEndPage(int) avant setStartPage(int)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setUserPassword {#setUserPassword-java.lang.String-}
Définit le UserPassword du document.
