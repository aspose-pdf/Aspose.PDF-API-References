---
title: "com.aspose.pdf.facades"
linktitle: "com.aspose.pdf.facades"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le package com.aspose.pdf.facades fournit des classes provenant à l'origine d'Aspose.Pdf.Kit."
type: docs
weight: 180
url: /fr/java/com.aspose.pdf.facades/
---
Le package com.aspose.pdf.facades fournit des classes provenant à l'origine d'Aspose.Pdf.Kit.

## Interfaces

| Interface | Description |
| --- | --- |
| [IFacade](./ifacade/) | Interface de façade générale qui définit les méthodes communes aux façades. |
| [IForm](./iform/) | Classe représentant l'objet de formulaire Acro. |
| [IFormEditor](./iformeditor/) | Classe pour éditer les formulaires (ajout/suppression de champs, etc.) |
| [IPdfFileEditor](./ipdffileeditor/) | Implémente les opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc. |
| [IPdfFileStamp](./ipdffilestamp/) | Interface pour ajouter des tampons (filigrane ou arrière‑plan) aux fichiers PDF. |
| [ISaveableFacade](./isaveablefacade/) | Interface de façade qui définit les méthodes communes à toutes les façades sauvegardables. |
## Classes

| Classe | Description |
| --- | --- |
| [AlignmentType](./alignmenttype/) | La classe contient éventuellement des types d'alignement. Utilisez HorizontalAlignment à la place. |
| [AutoRotateMode](./autorotatemode/) | Direction de la rotation lors de l'impression du document. |
| [BDCProperties](./bdcproperties/) | Propriétés de l'opérateur BDC. |
| [Bookmark](./bookmark/) | Représente un signet. |
| [Bookmarks](./bookmarks/) | Représente une collection d'objets {@code Bookmark}. |
| [CgmPdfProducer](./cgmpdfproducer/) | Représente une classe permettant de produire des PDF à partir du format Computer Graphics Metafile (CGM). |
| [DataType](./datatype/) | Énumère les définitions des types de champs. |
| [DefaultMetadataProperties](./defaultmetadataproperties/) | Énumération des propriétés XMP standard. |
| [DocumentPrivilege](./documentprivilege/) | Représente les privilèges d'accès au fichier PDF. Référez-vous à {@code PdfFileSecurity}. Il existe 4 manières d'utiliser cette classe : 1. Utiliser directement un privilège prédéfini. 2. Partir d'un privilège prédéfini et modifier certaines permissions spécifiques. 3. Partir d'un privilège prédéfini et modifier une combinaison spécifique de permissions Adobe Professional. 4. Mélanger les méthodes 2 et 3. //Way1 : Utilisation directe d'un privilège prédéfini. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2 : À partir d'un privilège prédéfini et modification de certaines permissions spécifiques. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3 : À partir d'un privilège prédéfini et modification d'une combinaison spécifique de permissions Adobe Professional. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4 : Mélange des méthodes 2 et 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true); |
| [EncodingType](./encodingtype/) | Énumère les types d'encodage du texte utilisé. |
| [Facade](./facade/) | Classe façade de base. |
| [FontColor](./fontcolor/) | Classe représentant la couleur du texte. |
| [Form](./form/) | Classe représentant l'objet de formulaire Acro. |
| [Form.ImportStatus](./form.importstatus/) | Statut du champ importé |
| [FormattedText](./formattedtext/) | Classe qui représente le texte formaté. Contient des informations sur le texte ainsi que sa couleur, sa taille, son style. |
| [FormEditor](./formeditor/) | Classe pour éditer les formulaires (ajout/suppression de champs, etc.) |
| [FormEditorWeb](./formeditorweb/) | Classe pour l'édition des formulaires (ajout/suppression de champs, etc.) |
| [FormFieldFacade](./formfieldfacade/) | Classe représentant les propriétés du champ. |
| [FormWeb](./formweb/) | Représentation de l'interface du formulaire Acro. |
| [InternalHelper](./internalhelper/) | Classe d'aide |
| [IPdfFileEditor.ContentsResizeParameters](./ipdffileeditor.contentsresizeparameters/) | Classe permettant de spécifier les paramètres de redimensionnement de page. Autorise la définition des paramètres suivants : taille de la page résultante (largeur, hauteur) en unités d'espace par défaut ou en pourcentage de la taille de la page initiale ; marges gauche, haut, bas et droite en unités d'espace par défaut ou en pourcentage de la taille de la page initiale ; certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après le calcul des valeurs explicitement spécifiées. Par exemple : si la largeur de la page = 100 et que la nouvelle largeur de page spécifiée est 60 unités, alors les marges gauche et droite sont calculées automatiquement : (100 - 60) / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents. |
| [IPdfFileEditor.ContentsResizeValue](./ipdffileeditor.contentsresizevalue/) | Valeur de la marge ou de la taille du contenu spécifiée en pourcentage des unités d'espace par défaut. Cette classe est utilisée dans ContentsResizeParameters. |
| [LineInfo](./lineinfo/) | Représente les informations de la ligne. |
| [PdfAnnotationEditor](./pdfannotationeditor/) | Représente une classe pour travailler avec les annotations (commentaires) de documents PDF. |
| [PdfBookmarkEditor](./pdfbookmarkeditor/) | Représente une classe pour gérer les signets d'un fichier PDF, y compris la création, la modification, l'exportation, l'importation et la suppression. |
| [PdfContentEditor](./pdfcontenteditor/) | Représente une classe pour modifier le contenu d'un fichier PDF. |
| [PdfConverter](./pdfconverter/) | Représente une classe pour convertir chaque page d'un fichier PDF en images, prenant actuellement en charge BMP, JPEG, PNG et TIFF. Contenu pris en charge dans les PDF : images, formulaires, commentaires. |
| [PdfExtractor](./pdfextractor/) | Classe pour extraire les images et le texte d'un document PDF. |
| [PdfFileEditor](./pdffileeditor/) | Implémente les opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc. |
| [PdfFileEditor.ConcatenateCorruptedFileAction](./pdffileeditor.concatenatecorruptedfileaction/) | Action effectuée lorsqu'un fichier corrompu est rencontré lors du processus de concaténation. |
| [PdfFileEditor.ConcatenationProgressHandler](./pdffileeditor.concatenationprogresshandler/) | Représente une classe avec une méthode abstraite généralement fournie par le côté appelant et qui gère les événements de progression provenant de la concaténation. Ce gestionnaire fourni par le client peut généralement être utilisé pour afficher la progression totale de la concaténation sur la console ou dans une barre de progression. représente les informations sur l'événement de progression survenu |
| [PdfFileEditor.CorruptedItem](./pdffileeditor.corrupteditem/) | Classe qui fournit des informations sur les fichiers corrompus lors de la concaténation. |
| [PdfFileEditor.PageBreak](./pdffileeditor.pagebreak/) | Données de la position du saut de page. |
| [PdfFileEditor.ProgressEventHandlerInfo](./pdffileeditor.progresseventhandlerinfo/) | Cette classe représente des informations sur la progression de la concaténation qui peuvent être utilisées dans une application externe. |
| [PdfFileEditor.ProgressEventType](./pdffileeditor.progresseventtype/) | Cette énumération décrit les types d'événements de progression possibles qui peuvent survenir pendant la concaténation. |
| [PdfFileEditorWeb](./pdffileeditorweb/) | Représente la classe PdfFileEditorWeb qui implémente des opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc. |
| [PdfFileInfo](./pdffileinfo/) | Représente une classe permettant d'accéder aux métadonnées d'un document PDF. |
| [PdfFileMend](./pdffilemend/) | Représente une classe permettant d'ajouter du texte et des images sur les pages d'un document PDF existant. |
| [PdfFileSanitization](./pdffilesanitization/) | Représente l'API de désinfection et de récupération. Utilisez‑la si vous ne pouvez pas créer/ouvrir les documents d'une autre manière. |
| [PdfFileSecurity](./pdffilesecurity/) | Représente le chiffrement ou le déchiffrement d'un fichier PDF avec le mot de passe propriétaire ou utilisateur, ainsi que la modification des paramètres de sécurité et du mot de passe. |
| [PdfFileSignature](./pdffilesignature/) | Représente une classe permettant de signer un fichier PDF avec un certificat. |
| [PdfFileStamp](./pdffilestamp/) | Classe permettant d'ajouter des tampons (filigrane ou arrière‑plan) aux fichiers PDF. |
| [PdfFileStampWeb](./pdffilestampweb/) | Classe permettant d'ajouter des tampons (filigrane ou arrière‑plan) aux fichiers PDF. Activez‑la pour travailler avec HttpServletResponse. |
| [PdfJavaScriptStripper](./pdfjavascriptstripper/) | Classe permettant de supprimer tout le code JavaScript. |
| [PdfPageEditor](./pdfpageeditor/) | Représente une classe permettant de modifier la page d'un fichier PDF, y compris la rotation, le zoom, le déplacement et le changement de taille de la page. |
| [PdfPrintPageInfo](./pdfprintpageinfo/) | Représente un objet contenant les informations de la page d'impression actuelle. |
| [PdfProducer](./pdfproducer/) | <p> Représente une classe permettant de produire un PDF à partir d'autres formats. </p> <hr> <pre>This sample shows how to produce Pdf file from CGM file. String inputFile = "myImage.cgm"; String outputFile = "myPdf.pdf"; try { PdfProducer.produce(inputFile, ImportFormat.Cgm, outputFile); // Success produced pdf file. } catch (Exception e) { // Do something... } </pre> |
| [PdfQueryPageSettingsEventHandler](./pdfquerypagesettingseventhandler/) | Représente la méthode qui gère l'événement QueryPageSettings d'un PrintDocument. |
| [PdfViewer](./pdfviewer/) | Représente une classe permettant de visualiser ou d'imprimer un PDF. |
| [PdfXmpMetadata](./pdfxmpmetadata/) | Classe pour la manipulation des métadonnées XMP. |
| [PositioningMode](./positioningmode/) | Définit le mode de positionnement. Les valeurs possibles incluent Legacy (compatibilité descendante) et Current (méthode mise à jour de calcul de la position du texte). |
| [PropertyFlag](./propertyflag/) | Énumération des indicateurs de champ possibles. |
| [ReplaceTextStrategy](./replacetextstrategy/) | Cette classe contient les paramètres qui définissent le comportement de PdfContentEditor lors de l'exécution de l'opération ReplaceText. |
| [SaveableFacade](./saveablefacade/) | <p> Classe de base pour toutes les façades sauvegardables. |
| [SignatureName](./signaturename/) | Représente une classe pour un nom de signature. Représente un nom de signature plus précis. Utilisé à la place des noms de chaîne. Vous permet de présenter des signatures avec les mêmes noms de chaîne. |
| [Stamp](./stamp/) | Classe représentant un tampon. |
| [StampInfo](./stampinfo/) | Classe représentant les informations du tampon. |
| [TextProperties](./textproperties/) | Représente les propriétés du texte telles que : taille du texte, couleur, style, etc. |
| [VerticalAlignmentType](./verticalalignmenttype/) | Classe représentant les valeurs d'alignement vertical possibles. Utilisez VerticalAlignment à la place |
| [ViewerPreference](./viewerpreference/) | Décrit les préférences du visualiseur (mode page, mode page non plein écran, mise en page). |
| [WordWrapMode](./wordwrapmode/) | Définit les stratégies de retour à la ligne |
## Enums

| Enum | Description |
| --- | --- |
| [Algorithm](./algorithm/) | Représente les algorithmes qui peuvent être utilisés pour chiffrer un document PDF. |
| [BlendingColorSpace](./blendingcolorspace/) | Classe représentant l'espace couleur de mélange. |
| [FieldType](./fieldtype/) | Énumération des types de champ possibles. |
| [FontStyle](./fontstyle/) | Énumère 14 types de police. |
| [ImageMergeMode](./imagemergemode/) | Représente les modes de fusion d'images. |
| [KeySize](./keysize/) | Définit différentes tailles de clé qui peuvent être utilisées pour chiffrer des documents PDF. |
| [ReplaceTextStrategy.NoCharacterAction](./replacetextstrategy.nocharacteraction/) | Action à effectuer si la police ne contient pas le caractère requis |
| [ReplaceTextStrategy.Scope](./replacetextstrategy.scope/) | Portée où l'opération de remplacement de texte est appliquée, REPLACE_FIRST par défaut |
| [StampType](./stamptype/) | Décrit les types de tampon. |
| [SubmitFormFlag](./submitformflag/) | Énumération des indicateurs de soumission de formulaire possibles. |
