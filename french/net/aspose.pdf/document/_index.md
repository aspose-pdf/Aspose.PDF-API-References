---
title: "Classe Document"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Document. Classe représentant un document PDF."
type: docs
weight: 3900
url: /fr/net/aspose.pdf/document/
---
## Document class

Classe représentant le document PDF.

```csharp
public sealed class Document : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Document](document/#constructor)() | Initialise un document vide. |
| [Document](document/#constructor_1)(PdfVersion) | Initialise un document vide par version. |
| [Document](document/#constructor_2)(Stream) | Initialise une nouvelle instance de Document à partir du flux *input*. |
| [Document](document/#constructor_11)(string) | Il suffit d'initialiser Document en utilisant *filename*. Identique à [`Document`](./document/). |
| [Document](document/#constructor_6)(Stream, bool) | Initialise une nouvelle instance de Document à partir du flux *input*. |
| [Document](document/#constructor_4)(Stream, CertificateEncryptionOptions) | Initialise une nouvelle instance de Document à partir du flux *input*. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Ouvre un document existant depuis un flux en fournissant la conversion nécessaire pour obtenir un document pdf. |
| [Document](document/#constructor_7)(Stream, string) | Initialise une nouvelle instance de Document à partir du flux *input*. |
| [Document](document/#constructor_15)(string, bool) | Il suffit d'initialiser Document en utilisant *filename*. Identique à [`Document`](./document/). |
| [Document](document/#constructor_13)(string, CertificateEncryptionOptions) | Initialise une nouvelle instance de la classe `Document` pour travailler avec un document chiffré. |
| [Document](document/#constructor_12)(string, LoadOptions) | Ouvre un document existant depuis un fichier en fournissant les options de conversion nécessaires pour obtenir un document pdf. |
| [Document](document/#constructor_16)(string, string) | Initialise une nouvelle instance de la classe `Document` pour travailler avec un document chiffré. |
| [Document](document/#constructor_5)(Stream, CertificateEncryptionOptions, bool) | Initialise une nouvelle instance de Document à partir du flux *input*. |
| [Document](document/#constructor_9)(Stream, string, bool) | Initialise une nouvelle instance de Document à partir du flux *input*. |
| [Document](document/#constructor_8)(Stream, string, ICustomSecurityHandler) | Initialise une nouvelle instance de Document à partir du flux *input*. |
| [Document](document/#constructor_14)(string, CertificateEncryptionOptions, bool) | Initialise une nouvelle instance de la classe `Document` pour travailler avec un document chiffré. |
| [Document](document/#constructor_18)(string, string, bool) | Initialise une nouvelle instance de la classe `Document` pour travailler avec un document chiffré. |
| [Document](document/#constructor_17)(string, string, ICustomSecurityHandler) | Initialise une nouvelle instance de la classe `Document` pour travailler avec un document chiffré. |
| [Document](document/#constructor_10)(Stream, string, bool, ICustomSecurityHandler) | Initialise une nouvelle instance de Document à partir du flux *input*. |
| [Document](document/#constructor_19)(string, string, bool, ICustomSecurityHandler) | Initialise une nouvelle instance de la classe `Document` pour travailler avec un document chiffré. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Obtient les actions du document. Cette propriété est une instance de la classe DocumentActions qui permet d'obtenir/définir les actions BeforClosing, BeforSaving, etc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Permet de fusionner le contenu des pages pour optimiser la taille du document. Si utilisé, alors des pages différentes mais dupliquées peuvent référencer le même objet de contenu. Veuillez noter que ce mode peut entraîner des effets secondaires tels que la modification du contenu d'une page lorsque une autre page est modifiée. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Obtient ou définit la couleur d'arrière-plan du document. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Obtient ou définit le drapeau spécifiant si la position de la fenêtre du document sera centrée à l'écran. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Obtient la collection du document. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Obtient les paramètres de sécurité si le document est chiffré. Si le document n'est pas chiffré, alors l'exception correspondante sera levée dans .net 1.1 ou CryptoAlgorithm sera nul pour les autres versions de .net. |
| [CustomSecurityHandler](../../aspose.pdf/document/customsecurityhandler/) { get; } | Obtient un gestionnaire de sécurité personnalisé. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Obtient la collection des destinations. Obsolète. Veuillez utiliser NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Obtient ou définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | De nombreuses opérations avec une police ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police. Par exemple, certaines polices ne peuvent pas être incorporées dans un document PDF si les règles de licence désactivent l'incorporation pour cette police. Ce drapeau est utilisé pour désactiver toutes les restrictions de licence pour toutes les polices dans le document PDF actuel. Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est activé, cela signifie que la personne qui l'active assume toute la responsabilité des éventuelles violations de licence ou de loi. Ainsi, il le fait à ses propres risques. Il est fortement recommandé d'utiliser ce drapeau uniquement lorsque vous êtes pleinement convaincu de ne pas enfreindre le droit d'auteur. Par défaut false. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Obtient ou définit le drapeau indiquant si la barre de titre de la fenêtre du document doit afficher le titre du document. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Obtient ou définit l'option de gestion du mode d'impression recto verso à utiliser lors de l'impression du fichier depuis la boîte de dialogue d'impression. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Obtient la collection de fichiers incorporés au document. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Propriété qui indique que le document doit incorporer toutes les polices standard Type1 dont le drapeau IsEmbedded est réglé sur true. Toutes les polices PDF peuvent être incorporées dans le document simplement en définissant le drapeau IsEmbedded sur true, mais les polices standard Type1 du PDF sont une exception à cette règle. L'incorporation des polices Type1 standard nécessite beaucoup de temps, il faut donc non seulement régler le drapeau IsEmbedded sur true pour la police spécifiée, mais aussi définir un drapeau supplémentaire au niveau du document – EmbedStandardFonts = true ; Cette propriété ne peut être définie qu'une seule fois pour toutes les polices. Par défaut false. |
| [EnableNotificationLogging](../../aspose.pdf/document/enablenotificationlogging/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut activer la journalisation des notifications. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Obtient ou définit le drapeau qui permet de décharger partiellement le document de la mémoire. Cela permet de réduire l'utilisation de la mémoire mais peut avoir un effet négatif sur les performances. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Obtient ou définit le drapeau pour gérer la désinfection des champs de signature. Activé par défaut. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Nom du fichier PDF à l'origine de ce document |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Obtient ou définit le drapeau indiquant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Instance de IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Obtient le formulaire Acro du document. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Lance une Exception si le document est enregistré avec des modifications et possède une signature |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Obtient ou définit le drapeau indiquant si la barre de menus doit être masquée lorsque le document est actif. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Obtient ou définit le drapeau indiquant si la barre d'outils doit être masquée lorsque le document est actif. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Obtient ou définit le drapeau indiquant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
| [Id](../../aspose.pdf/document/id/) { get; } | Obtient l'ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Obtient ou définit le drapeau d'ignorance des erreurs dans les fichiers source. Lorsque des pages du document source sont copiées dans le document de destination, le processus de copie s'arrête avec une exception si certains objets des fichiers source sont corrompus lorsque ce drapeau est à false. Exemple : dest.Pages.Add(src.Pages); Si ce drapeau est réglé sur true, les objets corrompus seront remplacés par des valeurs vides. Par défaut : true. |
| [Info](../../aspose.pdf/document/info/) { get; } | Obtient les informations du document. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Obtient le statut chiffré du document. True si le document est chiffré. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Obtient ou définit une valeur indiquant si le document est linéarisé. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Obtient si le document est conforme au PDF/A. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Obtient si le document est conforme au PDF/UA. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Obtient ou définit si le document est conforme au PDF/A. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Collection de JavaScript au niveau du document. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Obtient la structure logique du document. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Métadonnées du Document. (Un document PDF peut inclure des informations générales, telles que le titre du document, l'auteur, ainsi que les dates de création et de modification. Ces informations globales concernant le document (par opposition à son contenu ou à sa structure) sont appelées métadonnées et sont destinées à faciliter le catalogage et la recherche de documents dans des bases de données externes.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Collection de destinations nommées dans le document. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Obtient ou définit le mode de page, spécifiant comment afficher le document lors de la sortie du mode plein écran. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Obtient ou définit l'action effectuée à l'ouverture du document. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Obtient ou définit le drapeau d'optimisation. Lorsque des pages sont ajoutées au document, les flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si ce drapeau est défini. Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des exigences de mémoire plus importantes. Valeur par défaut : false. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Obtient les repères du document. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Obtient la collection d'intentions de sortie dans le document. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Obtient ou définit les informations de page. (pour le générateur uniquement, non rempli lors de la lecture du document) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Obtient les libellés de page dans le document. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Obtient ou définit la mise en page qui doit être utilisée lorsque le document est ouvert. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Obtient ou définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Obtient ou définit la collection de pages du document. Notez que les pages sont numérotées à partir de 1 dans la collection. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Obtient le format PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Obtient les autorisations du document. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Obtient ou définit un drapeau spécifiant si la taille de page PDF doit être utilisée pour sélectionner le bac à papier d'entrée. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Obtient ou définit l'option de mise à l'échelle de page qui doit être sélectionnée lorsqu'une boîte de dialogue d'impression est affichée pour ce document. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Obtient l'accès au contenu TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Obtient une version de Pdf à partir de l'en-tête du fichier Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Obtient et définit la limite de taille de fichier pour charger un fichier complet en mémoire. La valeur est définie en mégaoctets. La valeur par défaut est de 210 Mb. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Obtient l'état sous licence du système. Retourne true si le système fonctionne en mode sous licence et false sinon. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Fusionne les documents. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Fusionne les fichiers pdf. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Fusionne les documents. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Fusionne les documents. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Lie le xml au document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Lie le xml au document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Lie le xml/xsl au document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Lie le xml/xsl au document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Lie le xml/xsl au document |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Modifie les mots de passe du document. Cette action ne peut être effectuée qu'avec le mot de passe du propriétaire. |
| [Check](../../aspose.pdf/document/check/)(bool) | Valide le document. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Convertit le document en utilisant les options de conversion spécifiées |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Reconnaît les images à l'intérieur du document et ajoute des chaînes hocr dessus. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Reconnaît les images à l'intérieur du document et ajoute des chaînes hocr dessus. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Convertit le document et enregistre les erreurs dans le flux spécifié. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Convertit le document en appliquant le Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Convertit le document en appliquant le Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Convertit la page en PNG pour le flux d'images DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Déchiffre le document. Appelez ensuite Save pour obtenir la version déchiffrée du document. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Ferme toutes les ressources utilisées par ce document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) | Chiffre le document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, DocumentPrivilege, ICustomSecurityHandler) | Chiffre le document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_3)(string, string, Permissions, CryptoAlgorithm) | Chiffre le document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_5)(string, string, Permissions, ICustomSecurityHandler) | Chiffre le document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Chiffre le document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_4)(string, string, Permissions, CryptoAlgorithm, bool) | Chiffre le document. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Exporte toutes les annotations du document dans le flux. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Exporte toutes les annotations du document vers le fichier XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Supprime tous les champs du document et place leurs valeurs à la place. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Supprime tous les champs (et les annotations) du document et place leurs valeurs à la place. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Remplace le contenu transparent par des graphiques raster et vectoriels non transparents. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Libère la mémoire |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Renvoie la valeur de l'élément du dictionnaire du catalogue. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Obtient un objet avec l'ID spécifié dans le document. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Obtient les métadonnées XMP du document. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Vérifie si le document PDF actuel a été enregistré avec des mises à jour incrémentielles. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importe les annotations du flux vers le document. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importe les annotations du fichier XFDF vers le document. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Vérifie si le document nécessite l'appel de la méthode Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Charge un fichier, le convertissant en PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Fusionne les documents. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Fusionne les fichiers pdf. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Fusionne les documents. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Fusionne les documents. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linéariser le document afin de - ouvrir la première page le plus rapidement possible ; - afficher la page suivante ou suivre le lien vers la page suivante le plus rapidement possible ; - afficher la page de façon incrémentielle dès qu'elle arrive lorsque les données d'une page sont livrées sur un canal lent (afficher d'abord les données les plus utiles) ; - permettre l'interaction de l'utilisateur, comme le suivi d'un lien, d'être effectuée même avant que la page entière n'ait été reçue et affichée. L'appel de cette méthode ne sauvegarde pas réellement le document. Au contraire, le document n'est préparé qu'à avoir une structure optimisée, appelez ensuite Save pour obtenir le document optimisé. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Optimiser les ressources du document : 1. Les ressources qui ne sont pas utilisées sur les pages du document sont supprimées ; 2. Les ressources identiques sont fusionnées en un seul objet ; 3. Les objets inutilisés sont supprimés. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Optimiser les ressources du document selon la stratégie d'optimisation définie. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organise les nœuds de l'arbre des pages d'un document en un arbre équilibré. Seulement si le document possède plus de nodesNumInSubtrees objets de page, sinon cela ne fait rien. N'appelez pas cette méthode pendant l'itération sur les éléments Pages, cela peut donner des résultats imprévisibles. |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Traiter les paragraphes pour le générateur. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Supprime les métadonnées du document. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Supprimer la conformité pdfa du document |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Supprimer la conformité pdfUa du document |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Répare le document endommagé. |
| [Save](../../aspose.pdf/document/save/#save)() | Enregistrer le document de façon incrémentielle (c.-à-d. en utilisant la technique de mise à jour incrémentielle). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Enregistre le document avec des options d'enregistrement. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Stocke le document dans un flux. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Enregistre le document dans le fichier spécifié. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Enregistre le document sous un nouveau nom ainsi qu'avec un format de fichier. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Enregistre le document dans un flux avec des options d'enregistrement. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Enregistre le document sous un nouveau nom ainsi qu'avec un format de fichier. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Enregistrer le document de façon incrémentielle (c.-à-d. en utilisant la technique de mise à jour incrémentielle). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Enregistre le document avec des options d'enregistrement. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Stocke le document dans un flux. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Enregistre le document dans le fichier spécifié. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Enregistre le document sous un nouveau nom ainsi qu'avec un format de fichier. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Enregistre le document dans un flux avec des options d'enregistrement. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Enregistre le document sous un nouveau nom ainsi qu'avec un format de fichier. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Enregistre le document sous un nouveau nom en définissant ses options d'enregistrement. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Enregistrer le document au format XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Envoie l'intégralité du document au dispositif de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Envoie l'intégralité du document au dispositif de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Envoie certaines pages du document au dispositif de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Envoie l'intégralité du document au dispositif de document pour traitement. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Définir le titre du document Pdf |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Définir les métadonnées XMP du document. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Valider le document dans le fichier spécifié. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Valider le document dans le fichier spécifié. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Valider le document dans le fichier spécifié. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Convertit le flux du format source en flux du format de destination. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Convertit le flux du format source en fichier de destination dans le format de destination. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Convertit le fichier source du format source en flux dans le format de destination. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Convertit le fichier source au format source en fichier de destination au format de destination. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Définit la limite de taille de fichier pour charger un fichier complet en mémoire à la valeur par défaut égale à 210 Mo. |

## Champs

| Nom | Description |
| --- | --- |
| const [DefaultNodesNumInSubtrees](../../aspose.pdf/document/defaultnodesnuminsubtrees/) |  |

## Événements

| Nom | Description |
| --- | --- |
| event [FontSubstitution](../../aspose.pdf/document/fontsubstitution/) | Se produit lorsque la police remplace une autre police dans le document. |

## Autres membres

| Nom | Description |
| --- | --- |
| delegate [CallBackGetHocr](../../aspose.pdf/document.callbackgethocr) |  |
| delegate [CallBackGetHocrWithPage](../../aspose.pdf/document.callbackgethocrwithpage) |  |
| delegate [FontSubstitutionHandler](../../aspose.pdf/document.fontsubstitutionhandler) | Représente la méthode qui gérera l'événement FontSubstitution. |
| interface [IDocumentFontUtilities](../../aspose.pdf/document.idocumentfontutilities) | Contient des fonctionnalités pour ajuster les polices |
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Représente les options pour les méthodes Merge. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Représente les options de réparation d’un document PDF. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


