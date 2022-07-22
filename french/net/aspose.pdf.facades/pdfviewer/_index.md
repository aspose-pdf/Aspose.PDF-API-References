---
title: PdfViewer
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente une classe pour afficher ou imprimer un pdf.
type: docs
weight: 2640
url: /fr/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

Représente une classe pour afficher ou imprimer un pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfViewer](pdfviewer#constructor)() | Initialise nouveau[`PdfViewer`](../pdfviewer) objet. |
| [PdfViewer](pdfviewer#constructor_1)(Document) | Initialise nouveau[`PdfViewer`](../pdfviewer) objet. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le fichier doit être imprimé avec une taille optimisée.  Si fausse page d'impression sans mise à l'échelle de la page. Si vrai, imprimer la page avec mise à l'échelle pour s'adapter à la zone imprimable. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le fichier doit être imprimé avec rotation automatique |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode) { get; set; } | Obtient ou définit une valeur AutoRotateMode qui indique le sens de rotation |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype) { get; set; } | Obtient ou définit le type de coordonnées de la page (zones Media/Crop). La valeur CropBox est utilisée par défaut. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode) { get; set; } | Obtient ou définit le mode de présentation du formulaire. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment) { get; set; } | Obtient ou définit une valeur indiquant l'alignement horizontal |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount) { get; } | Obtient le nombre de pages du fichier PDF actuel. |
| [Password](../../aspose.pdf.facades/pdfviewer/password) { get; set; } | Obtient ou définit le mot de passe du document d'entrée. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale) { get; set; } | Obtient ou définit une valeur booléenne qui indique si la page est imprimée en niveaux de gris. Par défaut est faux. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage) { get; set; } | Définit ou obtient un mode pour PdfViewer à imprimer en tant qu'image. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname) { get; set; } | Obtient ou définit le nom du document dans la file d'attente de l'imprimante lorsque le document est imprimé. La valeur par défaut est le nom du fichier. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog) { get; set; } | Obtient ou définit une valeur booléenne qui indique si la boîte de dialogue de numéro de page est générée lors de l'impression. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus) { get; } | Obtient le résultat du travail d'impression. Si succès que null ; sinon, objet d'exception. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution) { get; set; } | Obtient ou définit la résolution lors de l'affichage et de l'impression. Plus la résolution est élevée, plus la vitesse est lente. La valeur par défaut est 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor) { get; set; } | Obtient ou définit une valeur à virgule flottante qui indique le facteur d'échelle. La valeur par défaut est 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage) { get; set; } | Obtient/définit l'utilisation de la conversion de la page pdf en fichier png intermédiaire lors de l'impression en mode fichier. Utilisez-le lorsque la taille du fichier de sortie est importante. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment) { get; set; } | Obtient ou définit une valeur qui indique l'alignement vertical |

## Méthodes

| Nom | La description |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf)(Document) | Initialise la façade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_1)(Stream) | Initialise la façade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf#bindpdf_2)(string) | Initialise la façade. |
| [Close](../../aspose.pdf.facades/pdfviewer/close)() | Ferme la façade. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages)() | Obtenir les pages du fichier pdf actuel. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage)(int) | Décode une page d'un fichier Pdf. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose)() | Dispose des ressources de façade. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings)() | Obtient les paramètres de page par défaut. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings)() | Obtient les paramètres d'imprimante par défaut. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument)() | Imprime le document PDF en utilisant l'imprimante par défaut. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings_1)(PrinterSettings) | Imprime le document Pdf avec les paramètres de l'imprimante. La taille de la page de sortie correspondra à la taille de la première page du document. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings#printdocumentwithsettings)(PageSettings, PrinterSettings) | Imprime le document Pdf avec les paramètres. Si la taille du document n'est pas compatible avec la taille de la page, pdf.kit l'étendra pour s'adapter à la taille de la page. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup)() | Imprime le document PDF avec une boîte de dialogue de configuration. Choisissez une imprimante à l'aide de la boîte de dialogue. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf)(Stream) | Ouvre et imprime un gros flux Pdf. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_3)(string) | Ouvre et imprime un gros fichier PDF. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_2)(Stream, PrinterSettings) | Ouvre et imprime un grand flux Pdf avec les paramètres d'imprimante spécifiés. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_5)(string, PrinterSettings) | Ouvre et imprime un gros fichier PDF avec les paramètres d'imprimante spécifiés. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Ouvre et imprime un flux Pdf volumineux avec des paramètres de page et des paramètres d'imprimante spécifiés. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf#printlargepdf_4)(string, PageSettings, PrinterSettings) | Ouvre et imprime un gros fichier PDF avec les paramètres de page et les paramètres d'imprimante spécifiés. Si votre fichier PDF contient des centaines de pages ou plus ou si sa taille est supérieure à 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save)(Stream) | Enregistre le document PDF résultant dans le flux. |
| [Save](../../aspose.pdf.facades/pdfviewer/save#save_1)(string) | Enregistre le document PDF résultant dans un fichier. |

### Voir également

* interface [IFacade](../ifacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
