---
title: Document
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe représentant le document PDF
type: docs
weight: 1870
url: /fr/net/aspose.pdf/document/
---
## Document class

Classe représentant le document PDF

```csharp
public sealed class Document : IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Document](document#constructor)() | Initialise le document vide. |
| [Document](document#constructor_1)(Stream) | Initialiser la nouvelle instance de document à partir du*input* flux. |
| [Document](document#constructor_6)(string) | Just init Document using*filename* . Le même que[`Document`](./document) . |
| [Document](document#constructor_3)(Stream, bool) | Initialiser la nouvelle instance de document à partir du*input* flux. |
| [Document](document#constructor_2)(Stream, LoadOptions) | Ouvre un document existant à partir d'un flux fournissant la conversion nécessaire pour obtenir un document pdf. |
| [Document](document#constructor_4)(Stream, string) | Initialiser la nouvelle instance de document à partir du*input* flux. |
| [Document](document#constructor_7)(string, LoadOptions) | Ouvre un document existant à partir d'un fichier fournissant les options de conversion nécessaires pour obtenir un document pdf. |
| [Document](document#constructor_8)(string, string) | Initialise la nouvelle instance du[`Document`](../document) classe pour travailler avec un document crypté. |
| [Document](document#constructor_5)(Stream, string, bool) | Initialiser la nouvelle instance de document à partir du*input* flux. |
| [Document](document#constructor_9)(string, string, bool) | Initialise la nouvelle instance du[`Document`](../document) classe pour travailler avec un document crypté. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions) { get; } | Obtient les actions de document. Cette propriété est une instance de la classe DocumentActions qui permet d'obtenir/définir les actions BeforClosing, BeforSaving, etc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent) { get; set; } | Permet de fusionner le contenu des pages pour optimiser la taille du document. S'il est utilisé, des pages différentes mais dupliquées peuvent faire référence au même objet de contenu . Veuillez noter que ce mode peut entraîner des effets secondaires tels que la modification du contenu de la page lorsqu'une autre page est modifiée. |
| [Background](../../aspose.pdf/document/background) { get; set; } | Obtient ou définit la couleur d'arrière-plan du document. |
| [CenterWindow](../../aspose.pdf/document/centerwindow) { get; set; } | Obtient ou définit un indicateur spécifiant si la position de la fenêtre du document sera centrée sur l'écran. |
| [Collection](../../aspose.pdf/document/collection) { get; set; } | Obtient la collection de documents. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm) { get; } | Obtient les paramètres de sécurité si le document est crypté. Si le document n'est pas chiffré, l'exception correspondante sera déclenchée dans .net 1.1 ou CryptoAlgorithm sera nul pour les autres versions de .net. |
| [Destinations](../../aspose.pdf/document/destinations) { get; } | Obtient la collection de destinations. Obsolète. Veuillez utiliser NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction) { get; set; } | Obtient ou définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications) { get; set; } | De nombreuses opérations avec la police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police. Par exemple, certaines polices ne peuvent pas être intégrées dans un document PDF si les règles de licence désactivent l'intégration pour cette police. Cet indicateur est utilisé pour désactiver toute restriction de licence pour toutes les polices du document PDF actuel. Soyez prudent lorsque vous utilisez cet indicateur. Lorsqu'il est défini, cela signifie que la personne qui définit ce drapeau, assume toute la responsabilité d'éventuelles violations de licence/loi sur lui-même. Il le prend donc à ses risques et périls. Il est fortement recommandé d'utiliser cet indicateur uniquement lorsque vous êtes pleinement sûr de ne pas enfreindre la loi sur le droit d'auteur. Par défaut faux. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle) { get; set; } | Obtient ou définit un indicateur spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document. |
| [Duplex](../../aspose.pdf/document/duplex) { get; set; } | Obtient ou définit l'option de gestion du mode d'impression recto verso à utiliser lors de l'impression du fichier à partir de la boîte de dialogue d'impression. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles) { get; } | Obtient une collection de fichiers intégrés au document. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts) { get; set; } | Propriété qui déclare que le document doit incorporer toutes les polices Type1 standard dont l'indicateur IsEmbedded est défini sur true. Toutes les polices PDF peuvent être incorporées dans le document simplement via la définition de l'indicateur IsEmbedded sur true, mais les polices PDF standard Type1 sont une exception à cette règle. L'incorporation de polices Standard Type1 nécessite beaucoup de temps, donc pour incorporer ces polices, il est nécessaire non seulement de définir l'indicateur Est intégré dans true pour la police spécifiée mais définit également un indicateur supplémentaire au niveau du document - EmbedStandardFonts = true; Cette propriété ne peut être définie qu'une seule fois pour toutes les polices. Par défaut false. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload) { get; set; } | Obtient ou définit l'indicateur qui permet au document d'être partiellement déchargé de la mémoire. Cela permet de réduire l'utilisation de la mémoire mais peut avoir un effet négatif sur les performances. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization) { get; set; } | Obtient ou définit un indicateur pour gérer le nettoyage des champs de signature. Activé par défaut. |
| [FileName](../../aspose.pdf/document/filename) { get; } | Nom du fichier PDF à l'origine de ce document |
| [FitWindow](../../aspose.pdf/document/fitwindow) { get; set; } | Obtient ou définit un indicateur spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
| [FontUtilities](../../aspose.pdf/document/fontutilities) { get; } | instance IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form) { get; } | Obtient la forme Acro du document. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange) { get; set; } | Lancer une exception si le document sera enregistré avec les modifications et aura la signature |
| [HideMenubar](../../aspose.pdf/document/hidemenubar) { get; set; } | Obtient ou définit un indicateur spécifiant si la barre de menus doit être masquée lorsque le document est actif. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar) { get; set; } | Obtient ou définit un indicateur spécifiant si la barre d'outils doit être masquée lorsque le document est actif. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui) { get; set; } | Obtient ou définit un indicateur spécifiant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
| [Id](../../aspose.pdf/document/id) { get; } | Obtient l'ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects) { get; set; } | Obtient ou définit l'indicateur d'ignorer les erreurs dans les fichiers source. Lorsque les pages du document source sont copiées dans le document de destination, le processus de copie est arrêté avec l'exception si certains objets des fichiers source sont corrompus lorsque cet indicateur est faux. exemple : dest.Pages.Add(src.Pages); Si cet indicateur est défini sur true, les objets corrompus seront remplacés par des valeurs vides. Par défaut : true. |
| [Info](../../aspose.pdf/document/info) { get; } | Obtient les informations sur le document. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted) { get; } | Obtient le statut chiffré du document. Vrai si le document est chiffré. |
| [IsLinearized](../../aspose.pdf/document/islinearized) { get; set; } | Obtient ou définit une valeur indiquant si le document est linéarisé. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant) { get; } | Obtient le document PDFa conforme. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant) { get; } | Obtient le document pdfua conforme. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed) { get; set; } | Obtient ou définit le document est conforme au format pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript) { get; } | Collection de JavaScript de niveau document. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure) { get; } | Obtient la structure logique du document. |
| [Metadata](../../aspose.pdf/document/metadata) { get; } | Métadonnées du document. (Un document PDF peut inclure des informations générales, telles que le titre du document, l'auteur et les dates de création et de modification. Ces informations globales sur le document (par opposition à son contenu ou sa structure) sont appelées metadata et sont destiné à aider au catalogage et à la recherche de documents dans des bases de données externes.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations) { get; } | Collection de destination nommée dans le document. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode) { get; set; } | Obtient ou définit le mode de page, en spécifiant comment afficher le document en quittant le mode plein écran. |
| [OpenAction](../../aspose.pdf/document/openaction) { get; set; } | Obtient ou définit l'action effectuée à l'ouverture du document. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize) { get; set; } | Obtient ou définit l'indicateur d'optimisation. Lorsque des pages sont ajoutées au document, des flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si cet indicateur est activé. Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des besoins en mémoire plus importants. Valeur par défaut : false. |
| [Outlines](../../aspose.pdf/document/outlines) { get; } | Obtient les plans du document. |
| [PageInfo](../../aspose.pdf/document/pageinfo) { get; set; } | Obtient ou définit les informations de la page. (pour le générateur uniquement) |
| [PageLabels](../../aspose.pdf/document/pagelabels) { get; } | Récupère les étiquettes de page dans le document. |
| [PageLayout](../../aspose.pdf/document/pagelayout) { get; set; } | Obtient ou définit la mise en page qui doit être utilisée lors de l'ouverture du document. |
| [PageMode](../../aspose.pdf/document/pagemode) { get; set; } | Obtient ou définit le mode de page, en spécifiant comment le document doit être affiché lorsqu'il est ouvert. |
| [Pages](../../aspose.pdf/document/pages) { get; } | Obtient ou définit une collection de pages de document. Notez que les pages sont numérotées à partir de 1 dans la collection. |
| [PdfFormat](../../aspose.pdf/document/pdfformat) { get; } | Obtient le format PDF |
| [Permissions](../../aspose.pdf/document/permissions) { get; } | Obtient les autorisations du document. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent) { get; } | Obtient l'accès au contenu TaggedPdf. |
| [Version](../../aspose.pdf/document/version) { get; } | Obtient une version de Pdf à partir de l'en-tête du fichier Pdf. |
| static [IsLicensed](../../aspose.pdf/document/islicensed) { get; } | Obtient l'état sous licence du système. Renvoie true si le système fonctionne en mode licence et false sinon. |

## Méthodes

| Nom | La description |
| --- | --- |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml)(Stream) | Lier xml au document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_3)(string) | Lier xml au document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_1)(Stream, Stream) | Lier xml/xsl au document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_4)(string, string) | Lier xml/xsl au document |
| [BindXml](../../aspose.pdf/document/bindxml#bindxml_2)(Stream, Stream, XmlReaderSettings) | Lier xml/xsl au document |
| [ChangePasswords](../../aspose.pdf/document/changepasswords)(string, string, string) | Modifie les mots de passe des documents. Cette action ne peut être effectuée qu'en utilisant le mot de passe du propriétaire. |
| [Check](../../aspose.pdf/document/check)(bool) | Valide le document. |
| [Convert](../../aspose.pdf/document/convert#convert_3)(CallBackGetHocr) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [Convert](../../aspose.pdf/document/convert#convert_2)(PdfFormatConversionOptions) | Convertir le document en utilisant les options de conversion spécifiées |
| [Convert](../../aspose.pdf/document/convert#convert_4)(Stream, PdfFormat, ConvertErrorAction) | Convertir le document et enregistrer les erreurs dans le flux spécifié. |
| [Convert](../../aspose.pdf/document/convert#convert_6)(string, PdfFormat, ConvertErrorAction) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [Convert](../../aspose.pdf/document/convert#convert)(Fixup, Stream, bool, object[]) | Convertir le document en appliquant le Fixup. |
| [Convert](../../aspose.pdf/document/convert#convert_1)(Fixup, string, bool, object[]) | Convertir le document en appliquant le Fixup. |
| [Convert](../../aspose.pdf/document/convert#convert_5)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [Convert](../../aspose.pdf/document/convert#convert_7)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convertir le document et enregistrer les erreurs dans le fichier spécifié. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream)(Page) | Convertir la page en PNG pour le flux d'images DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt)() | Déchiffre le document. Appelez puis Enregistrer pour obtenir la version décryptée du document. |
| [Dispose](../../aspose.pdf/document/dispose)() | Ferme toutes les ressources utilisées par ce document. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Crypte le document. Appelez puis Enregistrer pour obtenir une version chiffrée du document. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Crypte le document. Appelez puis Enregistrer pour obtenir une version chiffrée du document. |
| [Encrypt](../../aspose.pdf/document/encrypt#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Crypte le document. Appelez puis Enregistrer pour obtenir une version chiffrée du document. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf)(Stream) | Exporter toutes les annotations de document dans le flux. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf#exportannotationstoxfdf_1)(string) | Exporte toutes les annotations de document vers le fichier XFDF |
| [Flatten](../../aspose.pdf/document/flatten#flatten)() | Supprime tous les champs du document et place leurs valeurs à la place. |
| [Flatten](../../aspose.pdf/document/flatten#flatten_1)(FlattenSettings) | Supprime tous les champs du document et place leurs valeurs à la place. |
| [FreeMemory](../../aspose.pdf/document/freememory)() | Efface la mémoire |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue)(string) | Renvoie la valeur de l'élément du dictionnaire du catalogue. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid)(string) | Obtient un objet avec l'ID spécifié dans le document. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata)(Stream) | Obtenir les métadonnées XMP du document. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importe les annotations du flux vers le document. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importe les annotations du fichier XFDF vers le document. |
| [Optimize](../../aspose.pdf/document/optimize)() | Linéariser le document afin de - ouvrir la première page le plus rapidement possible ; - afficher la page suivante ou suivre le lien vers la page suivante le plus rapidement possible ; - afficher la page de manière incrémentielle au fur et à mesure qu'elle arrive lorsque les données d'une page sont livrées sur un canal lent (afficher d'abord les données les plus utiles) . Au contraire, seul le document est préparé pour avoir une structure optimisée, appelez puis Enregistrer pour obtenir un document optimisé. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources)() | Optimiser les ressources dans le document : 1. Les ressources qui ne sont pas utilisées sur les pages du document sont supprimées ; 2. Les ressources égales sont réunies en un seul objet ; 3. Les objets inutilisés sont supprimés. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources#optimizeresources_1)(OptimizationOptions) | Optimiser les ressources du document conformément à la stratégie d'optimisation définie. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs)() | Traiter les paragraphes pour le générateur. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata)() | Supprime les métadonnées du document. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance)() | Supprimer la conformité pdfa du document |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance)() | Supprimer la conformité pdfUa du document |
| [Repair](../../aspose.pdf/document/repair)() | Répare le document cassé. |
| [Save](../../aspose.pdf/document/save#save)() | Enregistrer le document de manière incrémentielle (c'est-à-dire en utilisant la technique de mise à jour incrémentielle). |
| [Save](../../aspose.pdf/document/save#save_1)(SaveOptions) | Enregistre le document avec les options d'enregistrement. |
| [Save](../../aspose.pdf/document/save#save_2)(Stream) | Stocke le document dans le flux. |
| [Save](../../aspose.pdf/document/save#save_5)(string) | Enregistre le document dans le fichier spécifié. |
| [Save](../../aspose.pdf/document/save#save_3)(Stream, SaveFormat) | Enregistre le document sous un nouveau nom avec un format de fichier. |
| [Save](../../aspose.pdf/document/save#save_4)(Stream, SaveOptions) | Enregistre le document dans un flux avec des options d'enregistrement. |
| [Save](../../aspose.pdf/document/save#save_6)(string, SaveFormat) | Enregistre le document sous un nouveau nom avec un format de fichier. |
| [Save](../../aspose.pdf/document/save#save_7)(string, SaveOptions) | Enregistre le document avec un nouveau nom en définissant ses options d'enregistrement. |
| [Save](../../aspose.pdf/document/save#save_8)(HttpResponse, string, ContentDisposition, SaveOptions) | Enregistre le document dans un flux de réponse avec des options d'enregistrement. |
| [SaveXml](../../aspose.pdf/document/savexml)(string) | Enregistrer le document au format XML. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_2)(DocumentDevice, Stream) | Envoie le document entier au périphérique de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_3)(DocumentDevice, string) | Envoie le document entier au périphérique de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto#sendto)(DocumentDevice, int, int, Stream) | Envoie certaines pages du document au périphérique de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto#sendto_1)(DocumentDevice, int, int, string) | Envoie le document entier au périphérique de document pour traitement. |
| [SetTitle](../../aspose.pdf/document/settitle)(string) | Définir le titre du document PDF |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata)(Stream) | Définir les métadonnées XMP du document. |
| [Validate](../../aspose.pdf/document/validate#validate)(PdfFormatConversionOptions) | Valider le document dans le fichier spécifié. |
| [Validate](../../aspose.pdf/document/validate#validate_1)(Stream, PdfFormat) | Valider le document dans le fichier spécifié. |
| [Validate](../../aspose.pdf/document/validate#validate_2)(string, PdfFormat) | Valider le document dans le fichier spécifié. |
| static [Convert](../../aspose.pdf/document/convert#convert)(Stream, LoadOptions, Stream, SaveOptions) | Convertit le flux au format source en flux au format de destination. |
| static [Convert](../../aspose.pdf/document/convert#convert_1)(Stream, LoadOptions, string, SaveOptions) | Convertit le flux au format source en fichier de destination au format de destination. |
| static [Convert](../../aspose.pdf/document/convert#convert_2)(string, LoadOptions, Stream, SaveOptions) | Convertit le fichier source au format source en flux au format de destination. |
| static [Convert](../../aspose.pdf/document/convert#convert_3)(string, LoadOptions, string, SaveOptions) | Convertit le fichier source au format source en fichier de destination au format de destination. |

## Autres membres

| Nom | La description |
| --- | --- |
| delegate [CallBackGetHocr](document.callbackgethocr) | La procédure de rappel pour la reconnaissance hocr. |
| delegate [FontSubstitutionHandler](document.fontsubstitutionhandler) | Représente la méthode qui gérera l'événement FontSubstitution. |
| interface [IDocumentFontUtilities](document.idocumentfontutilities) | Contient la fonctionnalité pour régler les polices |

### Voir également

* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
