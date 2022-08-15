---
title: PdfContentEditor
second_title: Référence de l'API Aspose.PDF pour .NET
description: Représente une classe pour modifier le contenu du fichier PDF.
type: docs
weight: 2440
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class

Représente une classe pour modifier le contenu du fichier PDF.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor#constructor)() | Le constructeur de l'objet PdfContentEditor. |
| [PdfContentEditor](pdfcontenteditor#constructor_1)(Document) | Initialise nouveau[`PdfContentEditor`](../pdfcontenteditor) objet sur la base de la*document* . |

## Propriétés

| Nom | La description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy) { get; set; } | Un ensemble de paramètres pour l'opération de remplacement de texte |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions) { get; set; } | Obtient ou définit les options d'édition de texte. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions) { get; set; } | Obtient ou définit les options de remplacement de texte. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions) { get; set; } | Obtient ou définit les options de recherche de texte. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction)(string, string) | Ajoute une action supplémentaire pour l'événement de document. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment_1)(string, string) | Ajoute une pièce jointe au document sans annotation. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment#adddocumentattachment)(Stream, string, string) | Ajoute une pièce jointe au document sans annotation. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_1)(Stream) | Lie un flux PDF pour modification. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf#bindpdf_2)(string) | Lie un fichier PDF pour modification. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference)(int) | Modifie la préférence d'affichage. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close)() | Ferme le document ouvert. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink)(Rectangle, string, int) | Crée un lien pour lancer une application dans un document PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_1)(Rectangle, string, int, Color) | Crée un lien pour lancer une application dans un document PDF. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | Crée un lien pour lancer une application dans un document PDF. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction)(string, Color, bool, bool, string, string, string) | Crée un signet avec l'action spécifiée. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret)(int, Rectangle, Rectangle, string, string, Color) | Crée une annotation caret. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink)(Rectangle, int, Color, Enum[]) | Crée un lien vers des actions personnalisées dans le document PDF. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_2)(Rectangle, string, string, int, string) | Crée une annotation de pièce jointe. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment)(Rectangle, string, Stream, string, int, string) | Crée une annotation de pièce jointe. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_3)(Rectangle, string, string, int, string, double) | Crée une annotation de pièce jointe. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | Crée une annotation de pièce jointe. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext)(Rectangle, string, int) | Crée une annotation de texte libre dans le document PDF |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink)(string, Rectangle, int, Color) | Crée un lien vers JavaScript dans le document PDF. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | Crée une annotation de ligne. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink)(Rectangle, int, int) | Crée un lien local dans le document PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_1)(Rectangle, int, int, Color) | Crée un lien local dans le document PDF. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | Crée un lien local dans le document PDF. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup)(Rectangle, string, int, int, Color) | Crée une annotation de balisage dans le document PDF. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie)(Rectangle, string, int) | Crée des annotations de film. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink)(Rectangle, string, int, int) | Crée un lien vers une autre page de document PDF. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | Crée un lien vers une autre page de document PDF. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | Crée un lien vers une autre page de document PDF. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon)(LineInfo, int, Rectangle, string) | Crée une annotation de polygone. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline)(LineInfo, int, Rectangle, string) | Crée une annotation polyligne. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup)(Rectangle, string, bool, int) | Crée une annotation contextuelle dans le document PDF. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp)(int, Rectangle, string, Color, Stream) | Crée une annotation de tampon en caoutchouc. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_1)(int, Rectangle, string, Color, string) | Crée une annotation de tampon en caoutchouc. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp#createrubberstamp_2)(int, Rectangle, string, string, Color) | Crée une annotation de tampon en caoutchouc. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound)(Rectangle, string, string, int, string) | Crée des annotations sonores. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle)(Rectangle, string, Color, bool, int, int) | Crée une annotation en cercle carré. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext)(Rectangle, string, string, bool, string, int) | Crée une annotation de texte dans un document PDF |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink)(Rectangle, string, int) | Crée un lien Web dans le document PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_1)(Rectangle, string, int, Color) | Crée un lien Web dans le document PDF. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink#createweblink_2)(Rectangle, string, int, Color, Enum[]) | Crée un lien Web dans le document PDF. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments)() | Supprime toutes les pièces jointes du document PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage)() | Supprime toutes les images du document PDF. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage#deleteimage_1)(int, int[]) | Supprime les images spécifiées sur la page spécifiée. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp)(int, int[]) | Supprime plusieurs tampons sur la page spécifiée par des index de tampon. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid)(int) | Supprimer le tampon par ID de toutes les pages du document. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid#deletestampbyid_1)(int, int) | Supprime le tampon sur la page spécifiée par ID de tampon. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids_1)(int[]) | Supprime les tampons avec les ID spécifiés de toutes les pages du document. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids#deletestampbyids)(int, int[]) | Supprime les tampons de la page spécifiée par plusieurs ID de tampon. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve)(LineInfo, int, Rectangle, string) | Crée une annotation de courbe. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink)() | Extrait la collection d'instances Link contenues dans le document PDF. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps)(int) | Renvoie un tableau de tampons sur la page. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference)() | Renvoie la préférence d'affichage. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid)(int, int) | Masque le tampon. Après le masquage, la visibilité du tampon peut être restaurée avec la méthode ShowStampById. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp)(int, int, double, double) | Modifie la position du tampon sur la page. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid)(int, int, double, double) | Modifie la position du tampon sur la page. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction)() | Supprime l'action d'ouverture du document. Cette opération est utile lors de la concaténation de plusieurs documents qui utilisent l'action explicite 'GoTo' au démarrage. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage)(int, int, string) | Remplace l'image spécifiée sur la page spécifiée du document PDF par une autre image. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_2)(string, string) | Remplace le texte dans le fichier PDF. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext)(string, int, string) | Remplace le texte du fichier PDF sur la page spécifiée. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_4)(string, string, int) | Remplace le texte dans le fichier PDF et définit la taille de la police. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_3)(string, string, TextState) | Remplace le texte dans le fichier PDF en utilisant le[`TextState`](../../aspose.pdf.text/textstate) objet. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext#replacetext_1)(string, int, string, TextState) | Remplace le texte du fichier PDF sur la page spécifiée.[`TextState`](../../aspose.pdf.text/textstate) objet (famille de polices, couleur) peut être spécifié pour remplacer le texte. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Enregistre le document PDF dans le fichier spécifié. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid)(int, int) | Affiche le tampon qui a été caché par HiddenStampById. |

## Des champs

| Nom | La description |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose) | Un type d'événement de document. Ferme un document. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen) | Un type d'événement de document. Ouvre un document. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted) | Un type d'événement de document. Exécuter une action après l'impression. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved) | Un type d'événement de document. Exécuter une action après avoir enregistré. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint) | Un type d'événement de document. Exécuter une action avant d'imprimer. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave) | Un type d'événement de document. Exécuter une action avant d'enregistrer. |

### Voir également

* class [SaveableFacade](../saveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
