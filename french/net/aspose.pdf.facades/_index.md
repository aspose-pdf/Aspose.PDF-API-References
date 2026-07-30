---
title: "Aspose.Pdf.Facades"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "L'espace de noms Aspose.Pdf.Facades fournit des classes provenant à l'origine d'Aspose.Pdf.Kit. Ces classes sont utilisées pour manipuler des documents en effectuant des opérations telles que la concaténation, le tamponnage, la signature, l'annotation, etc., mais à un niveau élevé sans accès à la structure interne d'un document."
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/
---
L’espace de noms **Aspose.Pdf.Facades** fournit des classes provenant à l’origine d’Aspose.Pdf.Kit. Ces classes sont utilisées pour manipuler des documents en effectuant des opérations telles que la concaténation, le tamponnage, la signature, l’annotation, etc., mais à un niveau élevé sans accéder à la structure interne d’un document.

## Classes

| Classe | Description |
| --- | --- |
| [AutoFiller](./autofiller/) | Représente une classe permettant de recevoir des données d'une base de données ou d'une autre source de données, de les placer dans les champs conçus du modèle PDF et, enfin, de générer un nouveau fichier ou flux PDF. Elle possède deux modes d'entrée de fichier modèle : entrée sous forme de flux ou fichier PDF. Elle propose quatre types de modes de sortie : un flux fusionné, un fichier fusionné, de nombreux petits flux, de nombreux petits fichiers. Elle peut recevoir des données littérales contenues dans un System.Data.DataTable. |
| [BDCProperties](./bdcproperties/) | Propriétés de l'opérateur BDC. |
| [Bookmark](./bookmark/) | Représente un signet. |
| [Bookmarks](./bookmarks/) | Représente une collection d'objets [`Bookmark`](../aspose.pdf.facades/bookmark/). |
| [DocumentPrivilege](./documentprivilege/) | Représente les privilèges d'accès au fichier Pdf. Référez-vous à[`PdfFileSecurity`](../aspose.pdf.facades/pdffilesecurity/). Il existe 4 manières d'utiliser cette classe : 1. Utiliser directement le privilège prédéfini. 2. Se baser sur un privilège prédéfini et modifier certaines permissions spécifiques. 3. Se baser sur un privilège prédéfini et modifier une combinaison spécifique de permissions Adobe Professional. 4. Mélanger la façon 2 et la façon 3. |
| [Facade](./facade/) | Classe de façade de base. |
| [FontColor](./fontcolor/) | Classe représentant la couleur du texte. |
| [Form](./form/) | Classe représentant l'objet de formulaire Acro. |
| [FormattedText](./formattedtext/) | Classe qui représente le texte formaté. Contient des informations sur le texte ainsi que sa couleur, sa taille, son style. |
| [FormDataConverter](./formdataconverter/) | Représente une classe permettant de convertir des données d'un format à un autre. Elle peut convertir les données au format fdf/xml/pdf/xfdf vers OLEDB/OdbcDB. Elle peut également convertir les données d'OLEDB/OdbcDB vers le format fdf/xml/xfdf. Elle peut convertir le fdf en xml avec la balise "hard-named". |
| [FormEditor](./formeditor/) | Classe pour éditer les formulaires (ajout/suppression de champs, etc.). |
| [FormFieldFacade](./formfieldfacade/) | Classe représentant les propriétés du champ. |
| [LineInfo](./lineinfo/) | Représente les informations de la ligne. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Représente une classe pour travailler avec les annotations (commentaires) du PDF Document. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Représente une classe pour travailler avec les signets du fichier PDF, incluant la création, la modification, l'exportation, l'importation et la suppression. |
| [PdfContentEditor](./pdfcontenteditor/) | Représente une classe pour modifier le contenu du fichier PDF. |
| [PdfConverter](./pdfconverter/) | Représente une classe pour convertir chaque Page d'un fichier pdf en images, prenant désormais en charge BMP, JPEG, PNG et TIFF. Contenu pris en charge dans les pdf : images, formulaire, commentaire. |
| [PdfExtractor](./pdfextractor/) | Classe pour extraire les images et le texte d'un PDF Document. |
| [PdfFileEditor](./pdffileeditor/) | Implémente des opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc. |
| [PdfFileInfo](./pdffileinfo/) | Représente une classe pour accéder aux métadonnées d'un PDF Document. |
| [PdfFileMend](./pdffilemend/) | Représente une classe pour ajouter du texte et des images sur les pages d'un PDF Document existant. |
| [PdfFileSanitization](./pdffilesanitization/) | Représente l'API de désinfection et de récupération. Utilisez-la si vous ne pouvez pas créer/ouvrir des documents d'une autre manière. |
| [PdfFileSecurity](./pdffilesecurity/) | Représente le chiffrement ou le déchiffrement d'un fichier Pdf avec le mot de passe propriétaire ou utilisateur, ainsi que la modification des paramètres de sécurité et du mot de passe. |
| [PdfFileSignature](./pdffilesignature/) | Représente une classe pour signer un fichier pdf avec un certificat. |
| [PdfFileStamp](./pdffilestamp/) | Classe pour ajouter des tampons (filigrane ou arrière-plan) aux fichiers PDF. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Classe pour supprimer tout le code Java Script. |
| [PdfPageEditor](./pdfpageeditor/) | Représente une classe pour modifier la Page du fichier PDF, incluant la rotation de la Page, le zoom de la Page, le déplacement et le changement de taille de la Page. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Représente un objet contenant les informations de la Page d'impression actuelle. |
| [PdfProducer](./pdfproducer/) | Représente une classe permettant de produire du PDF à partir d'autres formats. Cet exemple montre comment produire un fichier Pdf à partir d'un fichier CGM. |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Représente la méthode qui gère l'événement [`PdfQueryPageSettings`](../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) d'un [`PdfViewer`](../aspose.pdf.facades/pdfviewer/). |
| [PdfViewer](./pdfviewer/) | Représente une classe permettant de visualiser ou d'imprimer un pdf. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Classe pour la manipulation des métadonnées XMP. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Cette classe contient des paramètres qui définissent le comportement de PdfContentEditor lorsqu'une opération ReplaceText est effectuée. |
| [SaveableFacade](./saveablefacade/) | Classe de base pour toutes les façades sauvegardables. |
| [SignatureName](./signaturename/) | Représente une classe pour un nom de signature. |
| [Stamp](./stamp/) | Classe représentant un tampon. |
| [StampInfo](./stampinfo/) | Classe représentant les informations du tampon. |
| [TextProperties](./textproperties/) | Représente les propriétés du texte telles que : taille du texte, couleur, style, etc. |
| [ViewerPreference](./viewerpreference/) | Décrit les préférences du visualiseur (mode page, mode page non plein écran, disposition de la page). |
## Interfaces

| Interface | Description |
| --- | --- |
| [IFacade](./ifacade/) | Interface de façade générale qui définit les méthodes communes des façades. |
| [ISaveableFacade](./isaveablefacade/) | Interface de façade qui définit les méthodes communes à toutes les façades sauvegardables. |
## Énumération

| Énumération | Description |
| --- | --- |
| [Algorithm](./algorithm/) | Représente les algorithmes pouvant être utilisés pour chiffrer un document pdf. |
| [AutoRotateMode](./autorotatemode/) | Direction de la rotation lors de l'impression du document. |
| [BlendingColorSpace](./blendingcolorspace/) | Classe représentant l'espace colorimétrique de fusion. |
| [DataType](./datatype/) | Énumère les définitions des types de champ. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Énumération des propriétés XMP standard. |
| [EncodingType](./encodingtype/) | Énumère les types d'encodage du texte utilisés. |
| [FieldType](./fieldtype/) | Énumération des types de champ possibles. |
| [FontStyle](./fontstyle/) | Énumère 14 types de police. |
| [ImageMergeMode](./imagemergemode/) | Représente les modes de fusion d'images. |
| [KeySize](./keysize/) | Définit différentes tailles de clé pouvant être utilisées pour chiffrer des documents pdf. |
| [PositioningMode](./positioningmode/) | Définit le mode de positionnement. Les valeurs possibles incluent Legacy (compatibilité descendante) et Current (méthode mise à jour de calcul de la position du texte). |
| [PropertyFlag](./propertyflag/) | Énumération des indicateurs de champ possibles. |
| [StampType](./stamptype/) | Décrit les types de tampons. |
| [SubmitFormFlag](./submitformflag/) | Énumération des indicateurs possibles de soumission de formulaire. |
| [WordWrapMode](./wordwrapmode/) | Définit les stratégies d'habillage de texte |


