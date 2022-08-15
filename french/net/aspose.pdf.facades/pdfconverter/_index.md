---
title: PdfConverter
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente une classe pour convertir chaque page dun fichier pdf en images prenant en charge BMP JPEG PNG et TIFF maintenant. Contenu pris en charge dans les pdf  images formulaire commentaire.
type: docs
weight: 2450
url: /fr/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter class

Représente une classe pour convertir chaque page d'un fichier pdf en images, prenant en charge BMP, JPEG, PNG et TIFF maintenant. Contenu pris en charge dans les pdf : images, formulaire, commentaire.

```csharp
public sealed class PdfConverter : Facade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfConverter](pdfconverter#constructor)() | Initialise nouveau[`PdfConverter`](../pdfconverter) objet. |
| [PdfConverter](pdfconverter#constructor_1)(Document) | Initialise nouveau[`PdfConverter`](../pdfconverter) objet sur la base de la*document* . |

## Propriétés

| Nom | La description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype) { get; set; } | Obtient ou définit le type de coordonnées de la page (zones Media/Crop). La valeur CropBox est utilisée par défaut. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage) { get; set; } | Obtient ou définit la position finale que vous souhaitez convertir. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode) { get; set; } | Obtient ou définit le mode de présentation du formulaire. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount) { get; } | Obtient le nombre de pages. |
| [Password](../../aspose.pdf.facades/pdfconverter/password) { get; set; } | Obtient ou définit le document OwnerPassword. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution) { get; set; } | Obtient ou définit la résolution lors de la conversion. Plus la résolution est élevée, plus la vitesse de conversion est lente. La valeur par défaut est 150. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage) { get; set; } | Obtient ou définit la position de départ que vous souhaitez convertir. La valeur minimale est 1. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword) { get; set; } | Obtient ou définit le document UserPassword. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_1)(Stream) | Lie un flux Pdf pour convert. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf#bindpdf_2)(string) | Lie un fichier Pdf pour la conversion. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close)() | Fermez l'instance de PdfConverter et libérez les ressources. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert)() | Effectuez quelques travaux initiaux pour convertir un document pdf en images. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage)(Stream) | Enregistre l'image à diffuser avec le format d'image par défaut - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_9)(string) | Enregistre l'image dans un fichier avec le format d'image par défaut - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_4)(Stream, ImageFormat) | Enregistre l'image à diffuser avec le format d'image donné. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_1)(Stream, PageSize) | Enregistre l'image à diffuser avec une taille de page donnée. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_13)(string, ImageFormat) | Enregistre l'image dans un fichier au format d'image givin. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_10)(string, PageSize) | Enregistre l'image dans un fichier avec la taille de page donnée et le format d'image par défaut - jpeg. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_6)(Stream, ImageFormat, int) | Enregistre l'image à diffuser avec un format et une qualité d'image donnés. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_2)(Stream, PageSize, ImageFormat) | Enregistre l'image à diffuser avec une taille de page donnée. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_15)(string, ImageFormat, int) | Enregistre l'image dans un fichier avec un format et une qualité d'image donnés. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_11)(string, PageSize, ImageFormat) | Enregistre l'image dans un fichier avec une taille de page et un format d'image donnés. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_7)(Stream, ImageFormat, int, int) | Enregistre l'image à diffuser avec le format, la taille et la qualité de l'image donnée. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_3)(Stream, PageSize, ImageFormat, int) | Enregistre l'image à diffuser avec une taille de page, un format d'image et une qualité donnés. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_16)(string, ImageFormat, int, int) | Enregistre l'image dans un fichier avec le format et les dimensions d'image donnés. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_12)(string, PageSize, ImageFormat, int) | Enregistre l'image dans un fichier avec une taille de page, un format d'image et une qualité donnés. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_5)(Stream, ImageFormat, double, double, int) | Enregistre l'image à diffuser avec le format, la taille et la qualité de l'image donnée. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_8)(Stream, ImageFormat, int, int, int) | Enregistre l'image à diffuser avec le format, les dimensions et la qualité de l'image donnée. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_14)(string, ImageFormat, double, double, int) | Enregistre l'image dans un fichier avec le format d'image, la taille et la qualité de l'image. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage#getnextimage_17)(string, ImageFormat, int, int, int) | Enregistre l'image dans un fichier avec le format d'image, les dimensions et la qualité donnés. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage)() | Indique si le fichier pdf contient plus d'images ou non. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff)(Stream) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_10)(string) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_1)(Stream, CompressionType) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_4)(Stream, PageSize) | Convertit chaque page d'un document pdf en images avec une taille de page et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_2)(Stream, TiffSettings) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_11)(string, CompressionType) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_14)(string, PageSize) | Convertit chaque page d'un document pdf en images avec une taille de page et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_12)(string, TiffSettings) | Convertit chaque page d'un document pdf en images avec et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_6)(Stream, int, int) | Convertit chaque page d'un document pdf en images avec dimensions et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_5)(Stream, PageSize, TiffSettings) | Convertit chaque page d'un document pdf en images avec une taille de page et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_16)(string, int, int) | Convertit chaque page d'un document pdf en images avec dimensions et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_15)(string, PageSize, TiffSettings) | Convertit chaque page d'un document pdf en images avec une taille de page et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | Convertit chaque page d'un document pdf en images avec et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_7)(Stream, int, int, CompressionType) | Convertit chaque page d'un document pdf en images avec dimensions et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_8)(Stream, int, int, TiffSettings) | Convertit chaque page d'un document pdf en images avec dimensions et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_17)(string, int, int, CompressionType) | Convertit chaque page d'un document pdf en images avec dimensions et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_18)(string, int, int, TiffSettings) | Convertit chaque page d'un document pdf en images avec dimensions et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | Convertit chaque page d'un document pdf en images avec dimensions et enregistre les images dans un seul flux TIFF. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | Convertit chaque page d'un document pdf en images avec dimensions et enregistre les images dans un seul fichier TIFF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf)(Stream) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_3)(string) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_1)(Stream, PageSize) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_4)(string, PageSize) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_2)(Stream, int, int) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul flux TIFF ClassF. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf#saveastiffclassf_5)(string, int, int) | Convertit chaque page d'un document pdf en images et enregistre les images dans un seul fichier TIFF ClassF. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | Fusionne la liste des flux d'images en un seul flux d'images. Les formats de sortie Png/jpg/tiff sont pris en charge, en cas d'utilisation d'un flux de sortie de format non pris en charge encodé en Jpeg par défaut. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff)(List&lt;Stream&gt;) | Fusionne la liste des flux tiff en un flux tiff à plusieurs images. |

### Voir également

* class [Facade](../facade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
