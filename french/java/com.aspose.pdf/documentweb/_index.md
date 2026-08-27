---
title: "DocumentWeb"
linktitle: "DocumentWeb"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe DocumentWeb"
type: docs
weight: 1170
url: /fr/java/com.aspose.pdf/documentweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DocumentWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class DocumentWeb extends Object implements IDocument
```

Représente la classe DocumentWeb

## Champs

| Champ | Description |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Cela se produit lorsque la police remplace une autre police dans le document. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DocumentWeb](#DocumentWeb--) | Initialise un DocumentWeb vide. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-) | Initialise un DocumentWeb vide. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Initialise un DocumentWeb vide. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-java.lang.String-) | Initialise un DocumentWeb vide. |
| [DocumentWeb](#DocumentWeb-java.lang.String-) | Initialise un DocumentWeb vide. |
| [DocumentWeb](#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-) | Initialise un DocumentWeb vide. |
| [DocumentWeb](#DocumentWeb-java.lang.String-java.lang.String-) | Initialise un DocumentWeb vide. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [afterImport](#afterImport--) | Énumérer toutes les annotations enregistrées et appeler AfterImport pour chacune d'elles. |
| [bindXml](#bindXml-java.io.InputStream-) | Lier le xml au document |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | Lier le xml/xsl au document |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Lier le xml/xsl au document |
| [bindXml](#bindXml-java.lang.String-) | Lier le xml au document |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Lier le xml/xsl au document |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Modifie les mots de passe du document. |
| [check](#check-boolean-) | Valide le document. |
| [close](#close--) | Ferme toutes les ressources utilisées par ce document. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir le document en document recherchable. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Convertit le document en appliquant le Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Convertit le document en appliquant le Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Convertit le document en appliquant le Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Convertit le document en appliquant le Fixup. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Convertit le flux du format source en flux du format de destination. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Convertit le flux du format source en fichier de destination au format de destination. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convertit le document et enregistre les erreurs dans le flux spécifié. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convertir le document en utilisant les options de conversion spécifiées |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Convertit le fichier source du format source en flux au format de destination. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Convertit le fichier source du format source en fichier de destination au format de destination. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convertit le document et enregistre les erreurs dans le flux spécifié. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Convertit la page en PNG pour le flux d'images DSR, OMR, OCR. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties. |
| [decrypt](#decrypt--) | Déchiffre le document. |
| [dispose](#dispose--) | Obsolète. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Crypte le document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Crypte le document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Crypte le document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Crypte le document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Crypte le document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Crypte le document. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Exporte toutes les annotations du document dans le flux. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporte toutes les annotations du document vers un fichier XFDF |
| [flatten](#flatten--) | Supprime tous les champs (et les annotations) du document et place leurs valeurs à la place. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Supprime tous les champs du document et place leurs valeurs à la place. |
| [flattenTransparency](#flattenTransparency--) | Remplace le contenu transparent par des graphiques raster et vectoriels non transparents. |
| [freeMemory](#freeMemory--) | Efface la mémoire |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Notification concernant les polices manquantes lors du traitement des documents. |
| [getActions](#getActions--) | Obtient les actions du document. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Permet de fusionner le contenu des pages pour optimiser la taille du document. |
| [getBackground](#getBackground--) | Obtient la couleur d'arrière-plan du document. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Renvoie la valeur de l'élément du dictionnaire du catalogue. |
| [getCollection](#getCollection--) | Obtient la collection du document. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Obtient les paramètres de sécurité si le document est chiffré. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Obtient un gestionnaire de sécurité personnalisé. |
| [getDefaultCopier](#getDefaultCopier--) | Renvoie le copieur utilisé pour copier les pages dans ce document. |
| [getDestinations](#getDestinations--) | Obsolète. |
| [getDirection](#getDirection--) | Obtient l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
| [getDuplex](#getDuplex--) | Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Obtient la collection des fichiers incorporés au document. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Propriété qui indique que le document doit incorporer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Obtient ou définit le drapeau pour gérer la désinfection des champs de signature. |
| [getEngineDoc](#getEngineDoc--) | Instance de IPdfDocument utilisée pour accéder à la structure interne du document. |
| [getFileName](#getFileName--) | Nom du fichier PDF à l'origine de ce document |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Obtient et définit la limite de taille de fichier pour charger un fichier complet en mémoire. |
| [getForm](#getForm--) | Obtient le formulaire Acro du document. |
| [getId](#getId--) | Obtient l'ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Obtient ou définit le drapeau d'ignorer les erreurs dans les fichiers source. |
| [getInfo](#getInfo--) | Obtient les informations du document. |
| [getJavaScript](#getJavaScript--) | Collection de JavaScript au niveau du document. |
| [getLogicalStructure](#getLogicalStructure--) | Obtient la structure logique du document. |
| [getMetadata](#getMetadata--) | Métadonnées du document. |
| [getMetadataStream](#getMetadataStream--) | À usage interne uniquement ! |
| [getNamedDestinations](#getNamedDestinations--) | Collection de destinations nommées dans le document. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Obtient le mode de page, spécifiant comment afficher le document en quittant le mode plein écran. |
| [getObjectById](#getObjectById-java.lang.String-) | Obtient un objet avec l'ID spécifié dans le document. |
| [getOpenAction](#getOpenAction--) | Obtient l'action effectuée à l'ouverture du document. |
| [getOptimizeSize](#getOptimizeSize--) | Obtient le drapeau d'optimisation. |
| [getOutlines](#getOutlines--) | Obtient les contours du document. |
| [getOutputIntents](#getOutputIntents--) | Obtient la collection d'intentions de sortie dans le document. |
| [getPageInfo](#getPageInfo--) | Obtient les informations de la page.(pour le générateur uniquement, non rempli lors de la lecture du document) |
| [getPageLabels](#getPageLabels--) | Obtient les étiquettes de page dans le document. |
| [getPageLayout](#getPageLayout--) | Obtient la mise en page qui doit être utilisée lorsque le document est ouvert. |
| [getPageMode](#getPageMode--) | Obtient le mode de page, spécifiant comment le document doit être affiché à l'ouverture. |
| [getPages](#getPages--) | Obtient la collection des pages du document. |
| [getPdfFormat](#getPdfFormat--) | Obtient le format PDF. |
| [getPermissions](#getPermissions--) | Obtient les autorisations du document. |
| [getPrintScaling](#getPrintScaling--) | Obtient l'option de gestion du redimensionnement d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [getTaggedContent](#getTaggedContent--) | Obtient l'accès au contenu TaggedPdf. |
| [getVersion](#getVersion--) | Obtient une version de Pdf à partir de l'en-tête du fichier Pdf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Obtient les métadonnées XMP du document. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Vérifie si le document PDF actuel a été enregistré avec des mises à jour incrémentielles. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Importe les annotations d'un flux vers le document. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importe les annotations du fichier XFDF dans le document. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Drapeau indiquant le remplacement d'une police manquante. |
| [isCenterWindow](#isCenterWindow--) | Obtient le drapeau indiquant si la position de la fenêtre du document sera centrée à l'écran. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Obtient le drapeau spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document. |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Obtient ou définit une valeur indiquant s'il faut activer la journalisation des notifications. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Obtient ou définit le drapeau qui permet de décharger partiellement le document de la mémoire. |
| [isEncrypted](#isEncrypted--) | Obtient le statut chiffré du document. |
| [isFitWindow](#isFitWindow--) | Obtient le drapeau spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Lance une exception si le document est enregistré avec des modifications et possède une signature |
| [isHideMenubar](#isHideMenubar--) | Obtient le drapeau indiquant si la barre de menus doit être masquée lorsque le document est actif. |
| [isHideToolBar](#isHideToolBar--) | Obtient le drapeau indiquant si la barre d'outils doit être masquée lorsque le document est actif. |
| [isHideWindowUI](#isHideWindowUI--) | Obtient ou définit le drapeau indiquant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
| [isLicensed](#isLicensed--) | Obtient l'état de licence du système. |
| [isLinearized](#isLinearized--) | Obtient ou définit une valeur indiquant si le document est linéarisé. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Par défaut, la méthode save ferme les flux internes et libère les ressources mémoire. |
| [isPdfaCompliant](#isPdfaCompliant--) | Obtient si le document est conforme au PDF/A. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Obtient si le document est conforme au pdfua. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Obtient le drapeau indiquant si la taille de la page PDF doit être utilisée pour sélectionner le bac d'alimentation du papier. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Vérifie si le document nécessite un appel à la méthode Repair. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | Par défaut, le processus de validation PDF/A est nécessaire pour mettre à jour ou supprimer les données conformes au PDF/A si certaines règles ont été violées. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Obtient ou définit si le document est conforme au pdfa. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Charge un fichier en le convertissant en PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Fusionne les documents. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Fusionne les documents. |
| [merge](#merge-com.aspose.pdf.Document...-) | Fusionne les documents. |
| [merge](#merge-java.lang.String...-) | Fusionne les fichiers PDF. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Fusionne les documents. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Fusionne les documents. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Fusionne les documents. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | Fusionne les fichiers PDF. |
| [optimize](#optimize--) | Linéariser le document afin de - ouvrir la première page le plus rapidement possible ; - afficher la page suivante ou suivre le lien vers la page suivante le plus rapidement possible ; - afficher la page de façon incrémentielle à mesure qu'elle arrive lorsque les données d'une page sont livrées sur un canal lent (afficher d'abord les données les plus utiles) ; - permettre l'interaction de l'utilisateur, comme suivre un lien, d'être effectuée même avant que la page entière n'ait été reçue et affichée. |
| [optimizeResources](#optimizeResources--) | Optimiser les ressources dans le document : 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimiser les ressources dans le document selon la stratégie d'optimisation définie. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organise les nœuds de l'arbre de pages d'un document en un arbre équilibré. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organise les nœuds de l'arbre de pages d'un document en un arbre équilibré. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Méthode interne |
| [processParagraphs](#processParagraphs--) | Enregistre le document dans le générateur. |
| [removeMetadata](#removeMetadata--) | Supprime les métadonnées du document. |
| [removePdfaCompliance](#removePdfaCompliance--) | Supprimer la conformité pdfa du document |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Supprimer la conformité pdfUa du document |
| [repair](#repair--) | Répare le document endommagé. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Répare le document endommagé. |
| [resumeUpdate](#resumeUpdate--) | reprend la mise à jour du document |
| [save](#save--) | Enregistrer le document de façon incrémentielle (c.-à-d. |
| [save](#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-) | Enregistre le document dans un flux de réponse avec des options d'enregistrement. |
| [save](#save-java.io.OutputStream-) | Enregistre le document dans un flux. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Enregistre le document avec un nouveau nom ainsi qu'un format de fichier. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement. |
| [save](#save-com.aspose.pdf.SaveOptions-) | Enregistre le document avec des options d'enregistrement. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | À usage interne uniquement |
| [save](#save-java.lang.String-) | Enregistre le document dans le fichier spécifié. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | Enregistre le document avec un nouveau nom ainsi qu'un format de fichier. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Enregistre de façon incrémentielle le document PDF dans le flux spécifié. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Enregistre de façon incrémentielle le document PDF dans le flux spécifié. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Enregistre de façon incrémentielle le document PDF dans le flux spécifié. |
| [saveXml](#saveXml-java.lang.String-) | Enregistrer le document au format XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Envoie les pages spécifiques du document à l'appareil de document pour traitement. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Envoie le document complet à l'appareil de document pour traitement. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Envoie le document complet à l'appareil de document pour traitement. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Envoie le document complet à l'appareil de document pour traitement. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Notification concernant les polices manquantes lors du traitement des documents. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Définition du drapeau pour remplacer la police manquante. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Permet de fusionner le contenu des pages pour optimiser la taille du document. |
| [setBackground](#setBackground-java.awt.Color-) | Définit la couleur d'arrière-plan du document. |
| [setCenterWindow](#setCenterWindow-boolean-) | Définit le drapeau indiquant si la position de la fenêtre du document sera centrée à l'écran. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Définit la collection du document. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Obtient le paramètre de conversion pour le convertisseur pdf/ua (Convertit uniquement les métadonnées et le catalogue du document si défini à vrai) |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Définit la limite de taille de fichier pour charger un fichier complet en mémoire à la valeur par défaut de 210 Mo. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Définit le drapeau spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document. |
| [setDuplex](#setDuplex-int-) | Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Propriété qui indique que le document doit incorporer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Obtient ou définit une valeur indiquant s'il faut activer la journalisation des notifications. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Obtient ou définit le drapeau qui permet de décharger partiellement le document de la mémoire. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Obtient ou définit le drapeau pour gérer la désinfection des champs de signature. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Obtient et définit la limite de taille de fichier pour charger un fichier complet en mémoire. |
| [setFitWindow](#setFitWindow-boolean-) | Définit le drapeau spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Lance une exception si le document est enregistré avec des modifications et possède une signature |
| [setHideMenubar](#setHideMenubar-boolean-) | Définit le drapeau spécifiant si la barre de menu doit être masquée lorsque le document est actif. |
| [setHideToolBar](#setHideToolBar-boolean-) | Définit le drapeau spécifiant si la barre d'outils doit être masquée lorsque le document est actif. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Définit le drapeau spécifiant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Obtient ou définit le drapeau d'ignorer les erreurs dans les fichiers source. |
| [setLinearized](#setLinearized-boolean-) | Définit une valeur indiquant si le document est linéarisé. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Par défaut, la méthode save ferme les flux internes et libère les ressources mémoire. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Définit le mode de page, spécifiant comment afficher le document à la sortie du mode plein écran. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Définit l'action effectuée à l'ouverture du document. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Définit le drapeau d'optimisation. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Définit les informations de page (pour le générateur uniquement, non rempli lors de la lecture du document). |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Définit la mise en page qui doit être utilisée lorsque le document est ouvert. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Définit un drapeau spécifiant si la taille de page PDF doit être utilisée pour sélectionner le bac d'entrée du papier. |
| [setPrintScaling](#setPrintScaling-int-) | Définit l'option de gestion du redimensionnement d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | Par défaut, le processus de validation PDF/A est nécessaire pour mettre à jour ou supprimer le PDF/A si certaines règles ont été violées. |
| [setTitle](#setTitle-java.lang.String-) | Définit le titre du document PDF. |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Définit les métadonnées XMP du document. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Obtient ou définit si le document est conforme au pdfa. |
| [suppressUpdate](#suppressUpdate--) | Supprime la mise à jour des données de contenu pour toutes les pages. Le contenu n’est pas mis à jour tant que ResumeUpdate n’est pas appelé. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Valider le document dans le fichier spécifié. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Valider le document dans le fichier spécifié. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Valider le document dans le fichier spécifié. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

Cela se produit lorsque la police remplace une autre police dans le document.

### DocumentWeb {#DocumentWeb--}
```
public DocumentWeb()
```

Initialise un DocumentWeb vide.

### DocumentWeb {#DocumentWeb-java.io.InputStream-}
Initialise un DocumentWeb vide.

### DocumentWeb {#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Initialise un DocumentWeb vide.

### DocumentWeb {#DocumentWeb-java.io.InputStream-java.lang.String-}
Initialise un DocumentWeb vide.

### DocumentWeb {#DocumentWeb-java.lang.String-}
Initialise un DocumentWeb vide.

### DocumentWeb {#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-}
Initialise un DocumentWeb vide.

### DocumentWeb {#DocumentWeb-java.lang.String-java.lang.String-}
Initialise un DocumentWeb vide.

### afterImport {#afterImport--}
```
public void afterImport()
```

Énumérer toutes les annotations enregistrées et appeler AfterImport pour chacune d'elles.

### bindXml {#bindXml-java.io.InputStream-}
Lier le xml au document

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
Lier le xml/xsl au document

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
Lier le xml/xsl au document

### bindXml {#bindXml-java.lang.String-}
Lier le xml au document

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Lier le xml/xsl au document

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Modifie les mots de passe du document.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

Valide le document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| doRepair |  | Si vrai, les problèmes trouvés seront réparés. |

**Returns:**
Valeur booléenne True - si le document est réparé ; sinon, false.

### close {#close--}
```
public void close()
```

Ferme toutes les ressources utilisées par ce document.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir le document en document recherchable.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Convertit le document en appliquant le Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Convertit le document en appliquant le Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Convertit le document en appliquant le Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Convertit le document en appliquant le Fixup.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Convertit le flux du format source en flux du format de destination.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Convertit le flux du format source en fichier de destination au format de destination.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convertit le document et enregistre les erreurs dans le flux spécifié.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Convertir le document en utilisant les options de conversion spécifiées

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Convertit le fichier source du format source en flux au format de destination.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Convertit le fichier source du format source en fichier de destination au format de destination.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convertit le document et enregistre les erreurs dans le flux spécifié.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Convertit la page en PNG pour le flux d'images DSR, OMR, OCR.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties.

### decrypt {#decrypt--}
```
public void decrypt()
```

Déchiffre le document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsolète.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Crypte le document.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Crypte le document.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Crypte le document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Crypte le document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Crypte le document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Crypte le document.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Exporte toutes les annotations du document dans le flux.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exporte toutes les annotations du document vers un fichier XFDF

### flatten {#flatten--}
```
public void flatten()
```

Supprime tous les champs (et les annotations) du document et place leurs valeurs à la place.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Supprime tous les champs du document et place leurs valeurs à la place.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Remplace le contenu transparent par des graphiques raster et vectoriels non transparents.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Efface la mémoire

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Notification concernant les polices manquantes lors du traitement des documents.

**Returns:**
instance de ADocument.AbsentFontHandler

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

Obtient les actions du document.

**Returns:**
objet DocumentActionCollection

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Permet de fusionner le contenu des pages pour optimiser la taille du document.

**Returns:**
valeur booléenne

### getBackground {#getBackground--}
```
public Color getBackground()
```

Obtient la couleur d'arrière-plan du document.

**Returns:**
objet java.awt.Color

### getCatalogValue {#getCatalogValue-java.lang.String-}
Renvoie la valeur de l'élément du dictionnaire du catalogue.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Obtient la collection du document.

**Returns:**
objet Collection

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Obtient les paramètres de sécurité si le document est chiffré.

**Returns:**
élément CryptoAlgorithm ou null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Obtient un gestionnaire de sécurité personnalisé.

**Returns:**
instance ICustomSecurityHandler

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Renvoie le copieur utilisé pour copier les pages dans ce document.

**Returns:**
objet Copier

### getDestinations {#getDestinations--}
```
@Deprecated public DestinationCollection getDestinations()
```

Obsolète.

**Returns:**
objet DestinationCollection

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Obtient l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche).

**Returns:**
élément Direction

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression.

**Returns:**
élément PrintDuplex

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Obtient la collection des fichiers incorporés au document.

**Returns:**
objet EmbeddedFileCollection

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Propriété qui indique que le document doit incorporer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai.

**Returns:**
valeur booléenne

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

Obtient ou définit le drapeau pour gérer la désinfection des champs de signature.

**Returns:**
valeur booléenne

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instance de IPdfDocument utilisée pour accéder à la structure interne du document.

**Returns:**
objet IPdfDocument

### getFileName {#getFileName--}
```
public String getFileName()
```

Nom du fichier PDF à l'origine de ce document

**Returns:**
valeur String

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Obtient et définit la limite de taille de fichier pour charger un fichier complet en mémoire.

**Returns:**
valeur int

### getForm {#getForm--}
```
public Form getForm()
```

Obtient le formulaire Acro du document.

**Returns:**
objet Form

### getId {#getId--}
```
public Id getId()
```

Obtient l'ID.

**Returns:**
objet Id

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Obtient ou définit le drapeau d'ignorer les erreurs dans les fichiers source.

**Returns:**
valeurs booléennes

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Obtient les informations du document.

**Returns:**
objet DocumentInfo

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Collection de JavaScript au niveau du document.

**Returns:**
Objet JavaScriptCollection

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Obtient la structure logique du document.

**Returns:**
objet RootElement

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Métadonnées du document.

**Returns:**
objet Metadata

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

À usage interne uniquement !

**Returns:**
objet IPdfStreamAccessor

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Collection de destinations nommées dans le document.

**Returns:**
instance NamedDestinationCollection

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Obtient le mode de page, spécifiant comment afficher le document en quittant le mode plein écran.

**Returns:**
élément PageMode

### getObjectById {#getObjectById-java.lang.String-}
Obtient un objet avec l'ID spécifié dans le document.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

Obtient l'action effectuée à l'ouverture du document.

**Returns:**
objet IAppointment

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtient le drapeau d'optimisation.

**Returns:**
valeur booléenne

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Obtient les contours du document.

**Returns:**
Objet OutlineCollection

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Obtient la collection d'intentions de sortie dans le document.

**Returns:**
Instance OutputIntents

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Obtient les informations de la page.(pour le générateur uniquement, non rempli lors de la lecture du document)

**Returns:**
Les informations de la page.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Obtient les étiquettes de page dans le document.

**Returns:**
Objet PageLabelCollection

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Obtient la mise en page qui doit être utilisée lorsque le document est ouvert.

**Returns:**
Élément PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Obtient le mode de page, spécifiant comment le document doit être affiché à l'ouverture.

**Returns:**
élément PageMode

### getPages {#getPages--}
```
public PageCollection getPages()
```

Obtient la collection des pages du document.

**Returns:**
valeur booléenne

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Obtient le format PDF.

**Returns:**
PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Obtient les autorisations du document.

**Returns:**
valeur int

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Obtient l'option de gestion du redimensionnement d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression.

**Returns:**
Élément PrintScaling

### getTaggedContent {#getTaggedContent--}
```
public ITaggedContent getTaggedContent()
```

Obtient l'accès au contenu TaggedPdf.

**Returns:**
Instance ITaggedContent

### getVersion {#getVersion--}
```
public String getVersion()
```

Obtient une version de Pdf à partir de l'en-tête du fichier Pdf.

**Returns:**
Objet String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Obtient les métadonnées XMP du document.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Vérifie si le document PDF actuel a été enregistré avec des mises à jour incrémentielles.

**Returns:**
true si le document PDF a des mises à jour incrémentielles ; sinon, false.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Importe les annotations d'un flux vers le document.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importe les annotations du fichier XFDF dans le document.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Drapeau indiquant le remplacement d'une police manquante.

**Returns:**
valeur booléenne

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

Obtient le drapeau indiquant si la position de la fenêtre du document sera centrée à l'écran.

**Returns:**
valeur booléenne

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police.

**Returns:**
Valeur booléenne par défaut false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

Obtient le drapeau spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document.

**Returns:**
valeur booléenne

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Obtient ou définit une valeur indiquant s'il faut activer la journalisation des notifications.

**Returns:**
valeur booléenne

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Obtient ou définit le drapeau qui permet de décharger partiellement le document de la mémoire.

**Returns:**
valeur booléenne

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Obtient le statut chiffré du document.

**Returns:**
valeur booléenne

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

Obtient le drapeau spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée.

**Returns:**
valeur booléenne

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Lance une exception si le document est enregistré avec des modifications et possède une signature

**Returns:**
valeur booléenne

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

Obtient le drapeau indiquant si la barre de menus doit être masquée lorsque le document est actif.

**Returns:**
valeur booléenne

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

Obtient le drapeau indiquant si la barre d'outils doit être masquée lorsque le document est actif.

**Returns:**
valeur booléenne

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

Obtient ou définit le drapeau indiquant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif.

**Returns:**
valeur booléenne

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Obtient l'état de licence du système.

**Returns:**
valeur booléenne

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Obtient ou définit une valeur indiquant si le document est linéarisé.

**Returns:**
valeur booléenne

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Par défaut, la méthode save ferme les flux internes et libère les ressources mémoire.

**Returns:**
Valeur booléenne. (Valeur par défaut == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Obtient si le document est conforme au PDF/A.

**Returns:**
valeur booléenne

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Obtient si le document est conforme au pdfua.

**Returns:**
valeur booléenne

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

Obtient le drapeau indiquant si la taille de la page PDF doit être utilisée pour sélectionner le bac d'alimentation du papier.

**Returns:**
valeur booléenne

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Vérifie si le document nécessite un appel à la méthode Repair.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

Par défaut, le processus de validation PDF/A est nécessaire pour mettre à jour ou supprimer les données conformes au PDF/A si certaines règles ont été violées.

**Returns:**
valeur booléenne

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Obtient ou définit si le document est conforme au pdfa.

**Returns:**
valeur booléenne

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Charge un fichier en le convertissant en PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Fusionne les documents.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Fusionne les documents.

### merge {#merge-com.aspose.pdf.Document...-}
Fusionne les documents.

### merge {#merge-java.lang.String...-}
Fusionne les fichiers PDF.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Fusionne les documents.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Fusionne les documents.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Fusionne les documents.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
Fusionne les fichiers PDF.

### optimize {#optimize--}
```
public void optimize()
```

Linéariser le document afin de - ouvrir la première page le plus rapidement possible ; - afficher la page suivante ou suivre le lien vers la page suivante le plus rapidement possible ; - afficher la page de façon incrémentielle à mesure qu'elle arrive lorsque les données d'une page sont livrées sur un canal lent (afficher d'abord les données les plus utiles) ; - permettre l'interaction de l'utilisateur, comme suivre un lien, d'être effectuée même avant que la page entière n'ait été reçue et affichée.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Optimiser les ressources dans le document : 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimiser les ressources dans le document selon la stratégie d'optimisation définie.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organise les nœuds de l'arbre de pages d'un document en un arbre équilibré.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organise les nœuds de l'arbre de pages d'un document en un arbre équilibré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nodesNumInSubtrees |  | Nombre souhaité de sous-nœuds. La valeur par défaut est dix. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Méthode interne

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Enregistre le document dans le générateur.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Supprime les métadonnées du document.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Supprimer la conformité pdfa du document

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Supprimer la conformité pdfUa du document

### repair {#repair--}
```
public void repair()
```

Répare le document endommagé.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Répare le document endommagé.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

reprend la mise à jour du document

### save {#save--}
```
public void save()
```

Enregistrer le document de façon incrémentielle (c.-à-d.

### save {#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-}
Enregistre le document dans un flux de réponse avec des options d'enregistrement.

### save {#save-java.io.OutputStream-}
Enregistre le document dans un flux.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Enregistre le document avec un nouveau nom ainsi qu'un format de fichier.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement.

### save {#save-com.aspose.pdf.SaveOptions-}
Enregistre le document avec des options d'enregistrement.

### save {#save-com.aspose.ms.System.IO.Stream-}
À usage interne uniquement

### save {#save-java.lang.String-}
Enregistre le document dans le fichier spécifié.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
Enregistre le document avec un nouveau nom ainsi qu'un format de fichier.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Enregistre de façon incrémentielle le document PDF dans le flux spécifié.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Enregistre de façon incrémentielle le document PDF dans le flux spécifié.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Enregistre de façon incrémentielle le document PDF dans le flux spécifié.

### saveXml {#saveXml-java.lang.String-}
Enregistrer le document au format XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Envoie les pages spécifiques du document à l'appareil de document pour traitement.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Envoie le document complet à l'appareil de document pour traitement.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Envoie le document complet à l'appareil de document pour traitement.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Envoie le document complet à l'appareil de document pour traitement.

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Notification concernant les polices manquantes lors du traitement des documents.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean substitute)
```

Définition du drapeau pour remplacer la police manquante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| substituer |  | valeur booléenne |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Permet de fusionner le contenu des pages pour optimiser la taille du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBackground {#setBackground-java.awt.Color-}
Définit la couleur d'arrière-plan du document.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
```

Définit le drapeau indiquant si la position de la fenêtre du document sera centrée à l'écran.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Définit la collection du document.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

Obtient le paramètre de conversion pour le convertisseur pdf/ua (Convertit uniquement les métadonnées et le catalogue du document si défini à vrai)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Définit la limite de taille de fichier pour charger un fichier complet en mémoire à la valeur par défaut de 210 Mo.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur booléenne par défaut false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Définit le drapeau spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | élément PrintDuplex |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Propriété qui indique que le document doit incorporer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Obtient ou définit une valeur indiquant s'il faut activer la journalisation des notifications.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Obtient ou définit le drapeau qui permet de décharger partiellement le document de la mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

Obtient ou définit le drapeau pour gérer la désinfection des champs de signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Obtient et définit la limite de taille de fichier pour charger un fichier complet en mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Définit le drapeau spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Lance une exception si le document est enregistré avec des modifications et possède une signature

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Définit le drapeau spécifiant si la barre de menu doit être masquée lorsque le document est actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Définit le drapeau spécifiant si la barre d'outils doit être masquée lorsque le document est actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Définit le drapeau spécifiant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Obtient ou définit le drapeau d'ignorer les erreurs dans les fichiers source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeurs booléennes |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Définit une valeur indiquant si le document est linéarisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Par défaut, la méthode save ferme les flux internes et libère les ressources mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| manualDisposeEnabled |  | Valeur booléenne. (Valeur par défaut == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Définit le mode de page, spécifiant comment afficher le document à la sortie du mode plein écran.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Définit l'action effectuée à l'ouverture du document.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Définit le drapeau d'optimisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Définit les informations de page (pour le générateur uniquement, non rempli lors de la lecture du document).

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Définit la mise en page qui doit être utilisée lorsque le document est ouvert.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
public final void setPickTrayByPdfSize(boolean value)
```

Définit un drapeau spécifiant si la taille de page PDF doit être utilisée pour sélectionner le bac d'entrée du papier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Définit l'option de gestion du redimensionnement d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | élément PrintDuplex |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

Par défaut, le processus de validation PDF/A est nécessaire pour mettre à jour ou supprimer le PDF/A si certaines règles ont été violées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | valeur booléenne |

### setTitle {#setTitle-java.lang.String-}
Définit le titre du document PDF.

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Définit les métadonnées XMP du document.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Obtient ou définit si le document est conforme au pdfa.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Supprime la mise à jour des données de contenu pour toutes les pages. Le contenu n’est pas mis à jour tant que ResumeUpdate n’est pas appelé.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Valider le document dans le fichier spécifié.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Valider le document dans le fichier spécifié.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Valider le document dans le fichier spécifié.
