---
title: Aspose.Pdf.Facades
second_title: Référence de l'API Aspose.PDF pour .NET
description: Le Aspose.Pdf.FaçadesLespace de noms fournit des classes provenant à lorigine de Aspose.Pdf.Kit. Ces classes sont utilisées pour manipuler des documents en effectuant des opérations telles que la concaténation lestampillage la signature lannotation etc. mais à un niveau élevé sans accès à la structure interne dun document.
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/
---
Le **Aspose.Pdf.Façades**L'espace de noms fournit des classes provenant à l'origine de Aspose.Pdf.Kit. Ces classes sont utilisées pour manipuler des documents en effectuant des opérations telles que la concaténation, l'estampillage, la signature, l'annotation, etc., mais à un niveau élevé sans accès à la structure interne d'un document.

## Des classes

| Classer | La description |
| --- | --- |
| [AutoFiller](./autofiller) | Représente une classe pour recevoir des données de la base de données ou d'une autre source de données, les remplit dans les champs conçus du modèle pdf et génère enfin un nouveau fichier pdf ou flux. Il a deux modes d'entrée de fichier modèle : entrée sous forme de flux ou de fichier pdf . Il dispose de quatre types de modes de sortie : un flux fusionné, un fichier fusionné, de nombreux petits flux, de nombreux petits fichiers. Il peut recevoir des données littérales contenues dans un System.Data.DataTable. |
| [Bookmark](./bookmark) | Représente un signet. |
| [Bookmarks](./bookmarks) | Représente une collection de[`Bookmark`](../aspose.pdf.facades/bookmark) objets. |
| [DocumentPrivilege](./documentprivilege) | Représente les privilèges d'accès au fichier Pdf. Faire référence à[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity) . Il existe 4 façons d'utiliser cette classe : 1.Utilisation directe d'un privilège prédéfini. 2.Basé sur un privilège prédéfini et modification de certaines autorisations spécifiques. 3.Basé sur un privilège prédéfini et modification d'une combinaison d'autorisations Adobe Professional spécifique. 4. Mélange la voie2 et la voie3. |
| [Facade](./facade) | Classe façade de base. |
| [FontColor](./fontcolor) | Classe représentant la couleur du texte. |
| [Form](./form) | Classe représentant l'objet de formulaire Acro. |
| [FormattedText](./formattedtext) | Classe qui représente du texte formaté. Contient des informations sur le texte et sa couleur, sa taille, son style. |
| [FormDataConverter](./formdataconverter) | Représente une classe pour convertir des données d'un format à un autre format. Il peut convertir les données de fdf/xml/pdf/xfdf en OLEDB/OdbcDB. Il peut également convertir les données de OLEDB/OdbcDB en données de fdf/xml/xfdf. Il peut convertir le fdf en xml avec la balise "hard-named". |
| [FormEditor](./formeditor) | Classe pour l'édition de formulaires (ajout/suppression de champs, etc.) |
| [FormFieldFacade](./formfieldfacade) | Classe de représentation des propriétés de champ. |
| [LineInfo](./lineinfo) | Représente les informations de ligne. |
| [PdfAnnotationEditor](./pdfannotationeditor) | Représente une classe pour travailler avec des annotations de document PDF (commentaires). |
| [PdfBookmarkEditor](./pdfbookmarkeditor) | Représente une classe pour travailler avec les signets du fichier PDF, y compris créer, modifier, exporter, importer et supprimer. |
| [PdfContentEditor](./pdfcontenteditor) | Représente une classe pour modifier le contenu du fichier PDF. |
| [PdfConverter](./pdfconverter) | Représente une classe pour convertir chaque page d'un fichier pdf en images, prenant en charge BMP, JPEG, PNG et TIFF maintenant. Contenu pris en charge dans les pdf : images, formulaire, commentaire. |
| [PdfExtractor](./pdfextractor) | Classe pour extraire des images et du texte d'un document PDF. |
| [PdfFileEditor](./pdffileeditor) | Met en œuvre des opérations avec un fichier PDF : concaténation, fractionnement, extraction de pages, création de livret, etc. |
| [PdfFileInfo](./pdffileinfo) | Représente une classe pour accéder aux méta-informations du document PDF. |
| [PdfFileMend](./pdffilemend) | Représente une classe pour ajouter des textes et des images sur les pages d'un document PDF existant. |
| [PdfFileSanitization](./pdffilesanitization) | Représente l'API de nettoyage et de récupération. Utilisez-le si vous ne pouvez pas créer/ouvrir des documents d'une autre manière. |
| [PdfFileSecurity](./pdffilesecurity) | Représente le cryptage ou le décryptage d'un fichier PDF avec le mot de passe du propriétaire ou de l'utilisateur, en modifiant le paramètre de sécurité et le mot de passe. |
| [PdfFileSignature](./pdffilesignature) | Représente une classe pour signer un fichier pdf avec un certificat. |
| [PdfFileStamp](./pdffilestamp) | Classe pour ajouter des tampons (filigrane ou arrière-plan) aux fichiers PDF. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper) | Classe pour supprimer tout le code Java Script. |
| [PdfPageEditor](./pdfpageeditor) | Représente une classe pour modifier la page du fichier PDF, y compris la rotation de la page, le zoom de la page, le déplacement de la position et la modification de la taille de la page. |
| [PdfPrintPageInfo](./pdfprintpageinfo) | Représente un objet qui contient des informations sur la page d'impression actuelle. |
| [PdfProducer](./pdfproducer) | Représente une classe pour produire des PDF à partir d'autres formats.  Cet exemple montre comment produire un fichier PDF à partir d'un fichier CGM. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler) | Représente la méthode qui gère l'événement QueryPageSettings d'un PrintDocument. |
| [PdfViewer](./pdfviewer) | Représente une classe pour afficher ou imprimer un pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata) | Classe pour la manipulation avec les métadonnées XMP. |
| [ReplaceTextStrategy](./replacetextstrategy) | Cette classe contient des paramètres qui définissent le comportement de PdfContentEditor lorsque l'opération ReplaceText est effectuée. |
| [SaveableFacade](./saveablefacade) | Classe de base pour toutes les façades enregistrables. |
| [Stamp](./stamp) | Tampon représentant la classe. |
| [StampInfo](./stampinfo) | Classe représentant les informations de tampon. |
| [TextProperties](./textproperties) | Représente les propriétés du texte telles que : taille du texte, couleur, style, etc. |
| [ViewerPreference](./viewerpreference) | Décrit les préférences du visualiseur (mode page, mode page non plein écran, mise en page). |
## Interfaces

| Interface | La description |
| --- | --- |
| [IFacade](./ifacade) | Interface de façade générale qui définit les méthodes de façades communes. |
| [ISaveableFacade](./isaveablefacade) | Interface de façade qui définit des méthodes communes à toutes les façades enregistrables. |
## Énumération

| Énumération | La description |
| --- | --- |
| [Algorithm](./algorithm) | Représente des algorithmes qui peuvent être utilisés pour chiffrer un document pdf. |
| [AutoRotateMode](./autorotatemode) | Sens de rotation lors de l'impression du document. |
| [BlendingColorSpace](./blendingcolorspace) | La classe représente le mélange de l'espace colorimétrique. |
| [DataType](./datatype) | Enumère les définitions des types de champs. |
| [DefaultMetadataProperties](./defaultmetadataproperties) | Enumération des propriétés XMP standard. |
| [EncodingType](./encodingtype) | Énumère les types d'encodage du texte à l'aide de. |
| [FieldType](./fieldtype) | Enumération des types de champs possibles. |
| [FontStyle](./fontstyle) | Énumère 14 types de polices. |
| [ImageMergeMode](./imagemergemode) | Représente les modes de fusion d'images. |
| [KeySize](./keysize) | Définit différentes tailles de clé pouvant être utilisées pour chiffrer des documents pdf. |
| [PositioningMode](./positioningmode) | Définit le mode de positionnement. Les valeurs possibles incluent Legacy (rétrocompatibilité) et Current (méthode de calcul de la position du texte mise à jour) |
| [PropertyFlag](./propertyflag) | Enumération des drapeaux de champ possibles. |
| [StampType](./stamptype) | Décrit les types de tampons. |
| [SubmitFormFlag](./submitformflag) | Énumération des drapeaux de formulaire de soumission possibles. |
| [WordWrapMode](./wordwrapmode) | Définit les stratégies de retour à la ligne |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
