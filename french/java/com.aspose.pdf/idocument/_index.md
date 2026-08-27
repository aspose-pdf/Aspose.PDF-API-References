---
title: "IDocument"
linktitle: "IDocument"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "interface représentant un document PDF"
type: docs
weight: 2230
url: /fr/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

interface représentant un document PDF

## Méthodes

| Méthode | Description |
| --- | --- |
| [afterImport](#afterImport--) | Énumérer toutes les annotations enregistrées et appeler AfterImport pour chacune d'elles. |
| [bindXml](#bindXml-java.io.InputStream-) | Lier le xml au document |
| [bindXml](#bindXml-java.lang.String-) | Lier le xml au document |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Lier le xml/xsl au document |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Modifie les mots de passe du document. |
| [check](#check-boolean-) | Valide le document. |
| [close](#close--) | Ferme toutes les ressources utilisées par ce document. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir le document en document recherchable. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. <p> Cela permet d'afficher/masquer le texte recherchable sur la page. La valeur par défaut est FALSE. Cela permet d'obtenir l'image originale du pdf. La valeur par défaut est FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. <p> Cela permet d'afficher/masquer le texte recherchable sur la page. La valeur par défaut est FALSE. Cela permet d'obtenir l'image originale du pdf. La valeur par défaut est FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Convertir le document en utilisant les options de conversion spécifiées |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Méthode interne |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties. |
| [decrypt](#decrypt--) | Déchiffre le document. |
| [dispose](#dispose--) | Obsolète. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Crypte le document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Crypte le document. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Crypte le document. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Exporte toutes les annotations du document vers un fichier XFDF |
| [flatten](#flatten--) | Supprime tous les champs (et les annotations) du document et place leurs valeurs à la place. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Supprime tous les champs du document et place leurs valeurs à la place. |
| [flattenTransparency](#flattenTransparency--) | Remplace le contenu transparent par des graphiques raster et vectoriels non transparents. |
| [freeMemory](#freeMemory--) | Efface la mémoire |
| [getActions](#getActions--) | Obtient les actions du document. |
| [getBackground](#getBackground--) | Obtient la couleur d'arrière-plan du document. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Renvoie la valeur de l'élément du dictionnaire du catalogue. |
| [getCollection](#getCollection--) | Obtient la collection du document. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Obtient les paramètres de sécurité si le document est chiffré. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Obtient un gestionnaire de sécurité personnalisé. |
| [getDefaultCopier](#getDefaultCopier--) | Renvoie le copieur utilisé pour copier les pages dans ce document. |
| [getDestinations](#getDestinations--) | Obtient la collection des destinations. |
| [getDirection](#getDirection--) | Obtient l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
| [getDuplex](#getDuplex--) | Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Obtient la collection des fichiers incorporés au document. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Propriété qui indique que le document doit incorporer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Obtient ou définit le drapeau pour gérer la désinfection des champs de signature. |
| [getEngineDoc](#getEngineDoc--) | Instance de IPdfDocument utilisée pour accéder à la structure interne du document. |
| [getFileName](#getFileName--) | Nom du fichier PDF à l'origine de ce document |
| [getForm](#getForm--) | Obtient le formulaire Acro du document. |
| [getId](#getId--) | Obtient l'ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Obtient ou définit le drapeau d'ignorer les erreurs dans les fichiers source. |
| [getInfo](#getInfo--) | Obtient les informations du document. |
| [getLogicalStructure](#getLogicalStructure--) | Obtient la structure logique du document. |
| [getMetadata](#getMetadata--) | Métadonnées du document. |
| [getMetadataStream](#getMetadataStream--) | Renvoie le flux brut des métadonnées |
| [getNamedDestinations](#getNamedDestinations--) | Collection de destinations nommées dans le document. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Obtient le mode de page, spécifiant comment afficher le document en quittant le mode plein écran. |
| [getObjectById](#getObjectById-java.lang.String-) | Obtient un objet avec l'ID spécifié dans le document. |
| [getOpenAction](#getOpenAction--) | Obtient l'action effectuée à l'ouverture du document. |
| [getOptimizeSize](#getOptimizeSize--) | Obtient le drapeau d'optimisation. |
| [getOutlines](#getOutlines--) | Obtient les contours du document. |
| [getPageInfo](#getPageInfo--) | Obtient les informations de la page.(pour le générateur uniquement, non rempli lors de la lecture du document) |
| [getPageLabels](#getPageLabels--) | Obtient les étiquettes de page dans le document. |
| [getPageLayout](#getPageLayout--) | Obtient la mise en page qui doit être utilisée lorsque le document est ouvert. |
| [getPageMode](#getPageMode--) | Obtient le mode de page, spécifiant comment le document doit être affiché à l'ouverture. |
| [getPages](#getPages--) | Obtient la collection des pages du document. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Obtient les autorisations du document. |
| [getPrintScaling](#getPrintScaling--) | Obtient l'option de gestion du redimensionnement d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [getTaggedContent](#getTaggedContent--) | Obtient l'accès au contenu TaggedPdf. |
| [getVersion](#getVersion--) | Obtient une version de Pdf à partir de l'en-tête du fichier Pdf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Obtient les métadonnées XMP du document. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importe les annotations du fichier XFDF dans le document. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Notification concernant les polices manquantes lors du traitement des documents |
| [isCenterWindow](#isCenterWindow--) | Obtient le drapeau spécifiant si la position de la fenêtre du document sera centrée à l'écran. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Obtient le drapeau spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document. |
| [isEncrypted](#isEncrypted--) | Obtient le statut chiffré du document. |
| [isFitWindow](#isFitWindow--) | Obtient le drapeau spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
| [isHideMenubar](#isHideMenubar--) | Obtient le drapeau indiquant si la barre de menus doit être masquée lorsque le document est actif. |
| [isHideToolBar](#isHideToolBar--) | Obtient le drapeau indiquant si la barre d'outils doit être masquée lorsque le document est actif. |
| [isHideWindowUI](#isHideWindowUI--) | Obtient ou définit le drapeau indiquant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
| [isLinearized](#isLinearized--) | Obtient ou définit une valeur indiquant si le document est linéarisé. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Par défaut, la méthode save ferme les flux internes et libère les ressources mémoire. Nous pouvons effectuer certaines opérations et continuer à travailler avec le document après la méthode save si ce paramètre ManualDispose est activé. |
| [isPdfaCompliant](#isPdfaCompliant--) | Obtient si le document est conforme au pdf/a. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Obtient si le document est conforme au pdfua. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Obtient le drapeau indiquant si la taille de la page PDF doit être utilisée pour sélectionner le bac d'alimentation du papier. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Obtient ou définit si le document est conforme au pdfa. |
| [optimize](#optimize--) | Linéarisé le document afin de - ouvrir la première page le plus rapidement possible ; - afficher la page suivante ou suivre le lien vers la page suivante le plus rapidement possible ; - afficher la page de façon incrémentielle à mesure qu'elle arrive lorsque les données d'une page sont transmises sur un canal lent (afficher d'abord les données les plus utiles) ; - permettre l'interaction de l'utilisateur, comme suivre un lien, d'être effectuée même avant que la page entière n'ait été reçue et affichée. |
| [optimizeResources](#optimizeResources--) | Optimiser les ressources dans le document : 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Optimiser les ressources dans le document selon la stratégie d'optimisation définie. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organise les nœuds de l'arbre de pages d'un document en un arbre équilibré. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organise les nœuds de l'arbre de pages d'un document en un arbre équilibré. |
| [processParagraphs](#processParagraphs--) | Enregistre le document dans un flux. |
| [removeMetadata](#removeMetadata--) | Supprime les métadonnées du document. |
| [removePdfaCompliance](#removePdfaCompliance--) | Supprimer la conformité pdfa du document |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Supprimer la conformité pdfUa du document |
| [repair](#repair--) | Répare le document endommagé. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Enregistrer le document de façon incrémentielle (c.-à-d. |
| [save](#save-java.io.OutputStream-) | Enregistre le document dans un flux. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Enregistrer le document |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement. |
| [save](#save-java.lang.String-) | Enregistre le document dans le fichier spécifié. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Enregistre de façon incrémentielle le document PDF dans le flux spécifié. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Enregistre de façon incrémentielle le document PDF dans le flux spécifié. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Enregistre de façon incrémentielle le document PDF dans le flux spécifié. |
| [saveXml](#saveXml-java.lang.String-) | Enregistrer le document au format XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Envoie les pages spécifiques du document à l'appareil de document pour traitement. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Envoie le document complet à l'appareil de document pour traitement. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Envoie le document complet à l'appareil de document pour traitement. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Envoie le document complet à l'appareil de document pour traitement. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Définit le drapeau pour définir la police déterminée par le programme en cas d'absence de police. |
| [setBackground](#setBackground-java.awt.Color-) | Définit la couleur d'arrière-plan du document. |
| [setCenterWindow](#setCenterWindow-boolean-) | Définit le drapeau spécifiant si la position de la fenêtre du document sera centrée à l'écran. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Définit la collection du document. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Obtient le paramètre de conversion pour le convertisseur pdf/ua (Convertit uniquement les métadonnées et le catalogue du document si défini à vrai) |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Définit le drapeau spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document. |
| [setDuplex](#setDuplex-int-) | Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Propriété qui indique que le document doit incorporer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Obtient ou définit le drapeau pour gérer la désinfection des champs de signature. |
| [setFitWindow](#setFitWindow-boolean-) | Définit le drapeau spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
| [setHideMenubar](#setHideMenubar-boolean-) | Définit le drapeau spécifiant si la barre de menu doit être masquée lorsque le document est actif. |
| [setHideToolBar](#setHideToolBar-boolean-) | Définit le drapeau spécifiant si la barre d'outils doit être masquée lorsque le document est actif. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Définit le drapeau spécifiant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Définit une valeur indiquant si le document est linéarisé. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Par défaut, la méthode save ferme les flux internes et libère les ressources mémoire. Nous pouvons effectuer certaines opérations et continuer à travailler avec le document après l'appel de la méthode save si ce paramètre ManualDispose est activé. Mais il est fortement recommandé d'appeler la méthode dispose lorsque l'instance Document n'est plus nécessaire. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Définit le mode de page, spécifiant comment afficher le document à la sortie du mode plein écran. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Définit l'action effectuée à l'ouverture du document. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Définit le drapeau d'optimisation. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Définit les informations de page (pour le générateur uniquement, non rempli lors de la lecture du document). |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Définit la mise en page qui doit être utilisée lorsque le document est ouvert. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Définit un drapeau spécifiant si la taille de page PDF doit être utilisée pour sélectionner le bac d'entrée du papier. |
| [setPrintScaling](#setPrintScaling-int-) | Définit l'option de gestion du redimensionnement d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [setTitle](#setTitle-java.lang.String-) | Définit le titre du document PDF. |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Définit les métadonnées XMP du document. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Obtient ou définit si le document est conforme au pdfa. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Valider le document dans le fichier spécifié. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Valider le document dans le fichier spécifié. |

### afterImport {#afterImport--}
```
void afterImport()
```

Énumérer toutes les annotations enregistrées et appeler AfterImport pour chacune d'elles.

### bindXml {#bindXml-java.io.InputStream-}
Lier le xml au document

### bindXml {#bindXml-java.lang.String-}
Lier le xml au document

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Lier le xml/xsl au document

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Modifie les mots de passe du document.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
```

Valide le document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| doRepair |  | Si vrai, les problèmes trouvés seront réparés. |

**Returns:**
valeur booléenne

### close {#close--}
```
void close()
```

Ferme toutes les ressources utilisées par ce document.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir le document en document recherchable.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié. <p> Cela permet d'afficher/masquer le texte recherchable sur la page. La valeur par défaut est FALSE. Cela permet d'obtenir l'image originale du pdf. La valeur par défaut est FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié. <p> Cela permet d'afficher/masquer le texte recherchable sur la page. La valeur par défaut est FALSE. Cela permet d'obtenir l'image originale du pdf. La valeur par défaut est FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Convertir le document en utilisant les options de conversion spécifiées

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Convertir le document et enregistrer les erreurs dans le fichier spécifié.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Méthode interne

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Convertir le document en document recherchable et ignorer les erreurs de hochr qui ne peuvent pas être converties.

### decrypt {#decrypt--}
```
void decrypt()
```

Déchiffre le document.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Obsolète.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Crypte le document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Crypte le document.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Crypte le document.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Exporte toutes les annotations du document vers un fichier XFDF

### flatten {#flatten--}
```
void flatten()
```

Supprime tous les champs (et les annotations) du document et place leurs valeurs à la place.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Supprime tous les champs du document et place leurs valeurs à la place.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Remplace le contenu transparent par des graphiques raster et vectoriels non transparents.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Efface la mémoire

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Obtient les actions du document.

**Returns:**
objet DocumentActionCollection

### getBackground {#getBackground--}
```
Color getBackground()
```

Obtient la couleur d'arrière-plan du document.

**Returns:**
objet java.awt.Color

### getCatalogValue {#getCatalogValue-java.lang.String-}
Renvoie la valeur de l'élément du dictionnaire du catalogue.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Obtient la collection du document.

**Returns:**
objet Collection

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Obtient les paramètres de sécurité si le document est chiffré.

**Returns:**
élément CryptoAlgorithm ou null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Obtient un gestionnaire de sécurité personnalisé.

**Returns:**
instance ICustomSecurityHandler

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Renvoie le copieur utilisé pour copier les pages dans ce document.

**Returns:**
objet Copier

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Obtient la collection des destinations.

**Returns:**
objet DestinationCollection

### getDirection {#getDirection--}
```
Direction getDirection()
```

Obtient l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche).

**Returns:**
élément Direction

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression.

**Returns:**
élément PrintDuplex

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Obtient la collection des fichiers incorporés au document.

**Returns:**
objet EmbeddedFileCollection

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Propriété qui indique que le document doit incorporer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai.

**Returns:**
valeur booléenne

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

Obtient ou définit le drapeau pour gérer la désinfection des champs de signature.

**Returns:**
valeur booléenne

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Instance de IPdfDocument utilisée pour accéder à la structure interne du document.

**Returns:**
objet IPdfDocument

### getFileName {#getFileName--}
```
String getFileName()
```

Nom du fichier PDF à l'origine de ce document

**Returns:**
Objet String

### getForm {#getForm--}
```
Form getForm()
```

Obtient le formulaire Acro du document.

**Returns:**
objet Form

### getId {#getId--}
```
Id getId()
```

Obtient l'ID.

**Returns:**
objet Id

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Obtient ou définit le drapeau d'ignorer les erreurs dans les fichiers source.

**Returns:**
valeur booléenne

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Obtient les informations du document.

**Returns:**
objet DocumentInfo

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Obtient la structure logique du document.

**Returns:**
objet RootElement

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Métadonnées du document.

**Returns:**
objet Metadata

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Renvoie le flux brut des métadonnées

**Returns:**
objet IPdfStreamAccessor

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Collection de destinations nommées dans le document.

**Returns:**
instance NamedDestinationCollection

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Obtient le mode de page, spécifiant comment afficher le document en quittant le mode plein écran.

**Returns:**
élément PageMode

### getObjectById {#getObjectById-java.lang.String-}
Obtient un objet avec l'ID spécifié dans le document.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Obtient l'action effectuée à l'ouverture du document.

**Returns:**
objet IAppointment

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Obtient le drapeau d'optimisation.

**Returns:**
valeur booléenne

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Obtient les contours du document.

**Returns:**
Objet OutlineCollection

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Obtient les informations de la page.(pour le générateur uniquement, non rempli lors de la lecture du document)

**Returns:**
Les informations de la page.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Obtient les étiquettes de page dans le document.

**Returns:**
Objet PageLabelCollection

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Obtient la mise en page qui doit être utilisée lorsque le document est ouvert.

**Returns:**
Élément PageLayout

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Obtient le mode de page, spécifiant comment le document doit être affiché à l'ouverture.

**Returns:**
élément PageMode

### getPages {#getPages--}
```
PageCollection getPages()
```

Obtient la collection des pages du document.

**Returns:**
valeur booléenne

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
Élément PdfFormat

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Obtient les autorisations du document.

**Returns:**
valeur int

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Obtient l'option de gestion du redimensionnement d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression.

**Returns:**
Élément PrintScaling

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

Obtient l'accès au contenu TaggedPdf.

**Returns:**
Instance ITaggedContent

### getVersion {#getVersion--}
```
String getVersion()
```

Obtient une version de Pdf à partir de l'en-tête du fichier Pdf.

**Returns:**
Objet String

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Obtient les métadonnées XMP du document.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importe les annotations du fichier XFDF dans le document.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Notification concernant les polices manquantes lors du traitement des documents

**Returns:**
valeur booléenne

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Obtient le drapeau spécifiant si la position de la fenêtre du document sera centrée à l'écran.

**Returns:**
valeur booléenne

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police.

**Returns:**
Valeur booléenne par défaut false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Obtient le drapeau spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document.

**Returns:**
valeur booléenne

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Obtient le statut chiffré du document.

**Returns:**
valeur booléenne

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Obtient le drapeau spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée.

**Returns:**
valeur booléenne

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Obtient le drapeau indiquant si la barre de menus doit être masquée lorsque le document est actif.

**Returns:**
valeur booléenne

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Obtient le drapeau indiquant si la barre d'outils doit être masquée lorsque le document est actif.

**Returns:**
valeur booléenne

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Obtient ou définit le drapeau indiquant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif.

**Returns:**
valeur booléenne

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Obtient ou définit une valeur indiquant si le document est linéarisé.

**Returns:**
valeur booléenne

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

Par défaut, la méthode save ferme les flux internes et libère les ressources mémoire. Nous pouvons effectuer certaines opérations et continuer à travailler avec le document après la méthode save si ce paramètre ManualDispose est activé.

**Returns:**
Valeur booléenne. (Valeur par défaut == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Obtient si le document est conforme au pdf/a.

**Returns:**
valeur booléenne

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Obtient si le document est conforme au pdfua.

**Returns:**
valeur booléenne

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

Obtient le drapeau indiquant si la taille de la page PDF doit être utilisée pour sélectionner le bac d'alimentation du papier.

**Returns:**
valeur booléenne

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Obtient ou définit si le document est conforme au pdfa.

**Returns:**
valeur booléenne

### optimize {#optimize--}
```
void optimize()
```

Linéarisé le document afin de - ouvrir la première page le plus rapidement possible ; - afficher la page suivante ou suivre le lien vers la page suivante le plus rapidement possible ; - afficher la page de façon incrémentielle à mesure qu'elle arrive lorsque les données d'une page sont transmises sur un canal lent (afficher d'abord les données les plus utiles) ; - permettre l'interaction de l'utilisateur, comme suivre un lien, d'être effectuée même avant que la page entière n'ait été reçue et affichée.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Optimiser les ressources dans le document : 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Optimiser les ressources dans le document selon la stratégie d'optimisation définie.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Organise les nœuds de l'arbre de pages d'un document en un arbre équilibré.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organise les nœuds de l'arbre de pages d'un document en un arbre équilibré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nodesNumInSubtrees |  | Nombre souhaité de sous-nœuds. La valeur par défaut est dix. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Enregistre le document dans un flux.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Supprime les métadonnées du document.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Supprimer la conformité pdfa du document

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Supprimer la conformité pdfUa du document

### repair {#repair--}
```
void repair()
```

Répare le document endommagé.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Enregistrer le document de façon incrémentielle (c.-à-d.

### save {#save-java.io.OutputStream-}
Enregistre le document dans un flux.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Enregistrer le document

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement.

### save {#save-java.lang.String-}
Enregistre le document dans le fichier spécifié.

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

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Définit le drapeau pour définir la police déterminée par le programme en cas d'absence de police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | valeur booléenne |

### setBackground {#setBackground-java.awt.Color-}
Définit la couleur d'arrière-plan du document.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

Définit le drapeau spécifiant si la position de la fenêtre du document sera centrée à l'écran.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Définit la collection du document.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

Obtient le paramètre de conversion pour le convertisseur pdf/ua (Convertit uniquement les métadonnées et le catalogue du document si défini à vrai)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur booléenne par défaut false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Définit le drapeau spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Obtient ou définit l'option de gestion du mode duplex d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | élément PrintDuplex |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Propriété qui indique que le document doit incorporer toutes les polices Type1 standard dont le drapeau IsEmbedded est défini sur vrai.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

Obtient ou définit le drapeau pour gérer la désinfection des champs de signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Définit le drapeau spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Définit le drapeau spécifiant si la barre de menu doit être masquée lorsque le document est actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Définit le drapeau spécifiant si la barre d'outils doit être masquée lorsque le document est actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Définit le drapeau spécifiant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Définit une valeur indiquant si le document est linéarisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Par défaut, la méthode save ferme les flux internes et libère les ressources mémoire. Nous pouvons effectuer certaines opérations et continuer à travailler avec le document après l'appel de la méthode save si ce paramètre ManualDispose est activé. Mais il est fortement recommandé d'appeler la méthode dispose lorsque l'instance Document n'est plus nécessaire.

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
void setOptimizeSize(boolean value)
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
void setPickTrayByPdfSize(boolean value)
```

Définit un drapeau spécifiant si la taille de page PDF doit être utilisée pour sélectionner le bac d'entrée du papier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Définit l'option de gestion du redimensionnement d'impression à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | élément PrintDuplex |

### setTitle {#setTitle-java.lang.String-}
Définit le titre du document PDF.

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Définit les métadonnées XMP du document.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Obtient ou définit si le document est conforme au pdfa.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Valider le document dans le fichier spécifié.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Valider le document dans le fichier spécifié.
