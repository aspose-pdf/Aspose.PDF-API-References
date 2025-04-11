---
title: Class Document
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Document. Classe représentant un document PDF
type: docs
weight: 3780
url: /fr/net/aspose.pdf/document/
---
## Classe Document

Classe représentant un document PDF.

```csharp
public sealed class Document : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Document](document/#constructor)() | Initialise un document vide. |
| [Document](document/#constructor_1)(PdfVersion) | Initialise un document vide par version. |
| [Document](document/#constructor_2)(Stream) | Initialise une nouvelle instance de Document à partir du *flux* d'entrée. |
| [Document](document/#constructor_7)(string) | Initialise simplement Document en utilisant *nom de fichier*. Identique à [`Document`](./document/). |
| [Document](document/#constructor_4)(Stream, bool) | Initialise une nouvelle instance de Document à partir du *flux* d'entrée. |
| [Document](document/#constructor_3)(Stream, LoadOptions) | Ouvre un document existant à partir d'un flux en fournissant la conversion nécessaire pour obtenir un document PDF. |
| [Document](document/#constructor_5)(Stream, string) | Initialise une nouvelle instance de Document à partir du *flux* d'entrée. |
| [Document](document/#constructor_9)(string, bool) | Initialise simplement Document en utilisant *nom de fichier*. Identique à [`Document`](./document/). |
| [Document](document/#constructor_8)(string, LoadOptions) | Ouvre un document existant à partir d'un fichier en fournissant les options de conversion nécessaires pour obtenir un document PDF. |
| [Document](document/#constructor_10)(string, string) | Initialise une nouvelle instance de la classe `Document` pour travailler avec un document crypté. |
| [Document](document/#constructor_6)(Stream, string, bool) | Initialise une nouvelle instance de Document à partir du *flux* d'entrée. |
| [Document](document/#constructor_11)(string, string, bool) | Initialise une nouvelle instance de la classe `Document` pour travailler avec un document crypté. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf/document/actions/) { get; } | Obtient les actions du document. Cette propriété est une instance de la classe DocumentActions qui permet d'obtenir/définir les actions BeforClosing, BeforSaving, etc. |
| [AllowReusePageContent](../../aspose.pdf/document/allowreusepagecontent/) { get; set; } | Permet de fusionner le contenu des pages pour optimiser la taille du document. Si utilisé, alors des pages différentes mais dupliquées peuvent référencer le même objet de contenu. Veuillez noter que ce mode peut provoquer des effets secondaires comme le changement du contenu de la page lorsque l'autre page est modifiée. |
| [Background](../../aspose.pdf/document/background/) { get; set; } | Obtient ou définit la couleur de fond du document. |
| [CenterWindow](../../aspose.pdf/document/centerwindow/) { get; set; } | Obtient ou définit un indicateur spécifiant si la position de la fenêtre du document sera centrée sur l'écran. |
| [Collection](../../aspose.pdf/document/collection/) { get; set; } | Obtient la collection de documents. |
| [CryptoAlgorithm](../../aspose.pdf/document/cryptoalgorithm/) { get; } | Obtient les paramètres de sécurité si le document est crypté. Si le document n'est pas crypté, une exception correspondante sera levée dans .net 1.1 ou CryptoAlgorithm sera nul pour d'autres versions .net. |
| [Destinations](../../aspose.pdf/document/destinations/) { get; } | Obtient la collection de destinations. Obsolète. Veuillez utiliser NamedDestinations. |
| [Direction](../../aspose.pdf/document/direction/) { get; set; } | Obtient ou définit l'ordre de lecture du texte : L2R (de gauche à droite) ou R2L (de droite à gauche). |
| [DisableFontLicenseVerifications](../../aspose.pdf/document/disablefontlicenseverifications/) { get; set; } | De nombreuses opérations avec des polices ne peuvent pas être exécutées si ces opérations sont interdites par la licence de cette police. Par exemple, certaines polices ne peuvent pas être intégrées dans un document PDF si les règles de licence désactivent l'intégration pour cette police. Ce drapeau est utilisé pour désactiver toutes les restrictions de licence pour toutes les polices dans le document PDF actuel. Soyez prudent lors de l'utilisation de ce drapeau. Lorsqu'il est défini, cela signifie que la personne qui définit ce drapeau assume toute la responsabilité des violations possibles de licence/droit. Il le prend donc à ses propres risques. Il est fortement recommandé d'utiliser ce drapeau uniquement lorsque vous êtes pleinement convaincu que vous ne violez pas la loi sur le droit d'auteur. Par défaut, faux. |
| [DisplayDocTitle](../../aspose.pdf/document/displaydoctitle/) { get; set; } | Obtient ou définit un indicateur spécifiant si la barre de titre de la fenêtre du document doit afficher le titre du document. |
| [Duplex](../../aspose.pdf/document/duplex/) { get; set; } | Obtient ou définit l'option de gestion du mode d'impression recto verso à utiliser lors de l'impression du fichier à partir de la boîte de dialogue d'impression. |
| [EmbeddedFiles](../../aspose.pdf/document/embeddedfiles/) { get; } | Obtient la collection de fichiers intégrés au document. |
| [EmbedStandardFonts](../../aspose.pdf/document/embedstandardfonts/) { get; set; } | Propriété qui déclare que le document doit intégrer toutes les polices standard de type 1 qui ont le drapeau IsEmbedded défini sur vrai. Toutes les polices PDF peuvent être intégrées dans le document simplement en définissant le drapeau IsEmbedded sur vrai, mais les polices standard de type 1 PDF sont une exception à cette règle. L'intégration des polices standard de type 1 nécessite beaucoup de temps, donc pour intégrer ces polices, il est nécessaire non seulement de définir le drapeau IsEmbedded sur vrai pour la police spécifiée, mais également de définir un drapeau supplémentaire au niveau du document - EmbedStandardFonts = true ; Cette propriété ne peut être définie qu'une seule fois pour toutes les polices. Par défaut, faux. |
| [EnableObjectUnload](../../aspose.pdf/document/enableobjectunload/) { get; set; } | Obtient ou définit un indicateur qui permet de décharger partiellement le document de la mémoire. Cela permet de réduire l'utilisation de la mémoire mais peut avoir un effet négatif sur les performances. |
| [EnableSignatureSanitization](../../aspose.pdf/document/enablesignaturesanitization/) { get; set; } | Obtient ou définit un indicateur pour gérer la désinfection des champs de signature. Activé par défaut. |
| [FileName](../../aspose.pdf/document/filename/) { get; } | Nom du fichier PDF qui a causé ce document |
| [FitWindow](../../aspose.pdf/document/fitwindow/) { get; set; } | Obtient ou définit un indicateur spécifiant si la fenêtre du document doit être redimensionnée pour s'adapter à la première page affichée. |
| [FontUtilities](../../aspose.pdf/document/fontutilities/) { get; } | Instance IDocumentFontUtilities |
| [Form](../../aspose.pdf/document/form/) { get; } | Obtient le formulaire Acro du document. |
| [HandleSignatureChange](../../aspose.pdf/document/handlesignaturechange/) { get; set; } | Lève une exception si le document sera enregistré avec des modifications et a une signature |
| [HideMenubar](../../aspose.pdf/document/hidemenubar/) { get; set; } | Obtient ou définit un indicateur spécifiant si la barre de menu doit être masquée lorsque le document est actif. |
| [HideToolBar](../../aspose.pdf/document/hidetoolbar/) { get; set; } | Obtient ou définit un indicateur spécifiant si la barre d'outils doit être masquée lorsque le document est actif. |
| [HideWindowUI](../../aspose.pdf/document/hidewindowui/) { get; set; } | Obtient ou définit un indicateur spécifiant si les éléments de l'interface utilisateur doivent être masqués lorsque le document est actif. |
| [Id](../../aspose.pdf/document/id/) { get; } | Obtient l'ID. |
| [IgnoreCorruptedObjects](../../aspose.pdf/document/ignorecorruptedobjects/) { get; set; } | Obtient ou définit un indicateur d'ignorance des erreurs dans les fichiers sources. Lorsque des pages du document source sont copiées dans le document de destination, le processus de copie est arrêté avec une exception si certains objets dans les fichiers sources sont corrompus lorsque ce drapeau est faux. exemple : dest.Pages.Add(src.Pages); Si ce drapeau est défini sur vrai, alors les objets corrompus seront remplacés par des valeurs vides. Par défaut : vrai. |
| [Info](../../aspose.pdf/document/info/) { get; } | Obtient les informations du document. |
| [IsEncrypted](../../aspose.pdf/document/isencrypted/) { get; } | Obtient le statut crypté du document. Vrai si le document est crypté. |
| [IsLinearized](../../aspose.pdf/document/islinearized/) { get; set; } | Obtient ou définit une valeur indiquant si le document est linéarisé. |
| [IsPdfaCompliant](../../aspose.pdf/document/ispdfacompliant/) { get; } | Obtient si le document est conforme au pdfa. |
| [IsPdfUaCompliant](../../aspose.pdf/document/ispdfuacompliant/) { get; } | Obtient si le document est conforme au pdfua. |
| [IsXrefGapsAllowed](../../aspose.pdf/document/isxrefgapsallowed/) { get; set; } | Obtient ou définit si le document est conforme au pdfa. |
| [JavaScript](../../aspose.pdf/document/javascript/) { get; } | Collection de JavaScript au niveau du document. |
| [LogicalStructure](../../aspose.pdf/document/logicalstructure/) { get; } | Obtient la structure logique du document. |
| [Metadata](../../aspose.pdf/document/metadata/) { get; } | Métadonnées du document. (Un document PDF peut inclure des informations générales, telles que le titre du document, l'auteur et les dates de création et de modification. Ces informations globales sur le document (par opposition à son contenu ou à sa structure) sont appelées métadonnées et sont destinées à aider à cataloguer et à rechercher des documents dans des bases de données externes.) |
| [NamedDestinations](../../aspose.pdf/document/nameddestinations/) { get; } | Collection de destinations nommées dans le document. |
| [NonFullScreenPageMode](../../aspose.pdf/document/nonfullscreenpagemode/) { get; set; } | Obtient ou définit le mode de page, spécifiant comment afficher le document en quittant le mode plein écran. |
| [OpenAction](../../aspose.pdf/document/openaction/) { get; set; } | Obtient ou définit l'action effectuée à l'ouverture du document. |
| [OptimizeSize](../../aspose.pdf/document/optimizesize/) { get; set; } | Obtient ou définit le drapeau d'optimisation. Lorsque des pages sont ajoutées au document, des flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si ce drapeau est défini. Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des exigences de mémoire plus importantes. Valeur par défaut : faux. |
| [Outlines](../../aspose.pdf/document/outlines/) { get; } | Obtient les contours du document. |
| [OutputIntents](../../aspose.pdf/document/outputintents/) { get; } | Obtient la collection d'intentions de sortie dans le document. |
| [PageInfo](../../aspose.pdf/document/pageinfo/) { get; set; } | Obtient ou définit les informations de page. (pour le générateur uniquement, non rempli lors de la lecture du document) |
| [PageLabels](../../aspose.pdf/document/pagelabels/) { get; } | Obtient les étiquettes de page dans le document. |
| [PageLayout](../../aspose.pdf/document/pagelayout/) { get; set; } | Obtient ou définit la mise en page de la page qui doit être utilisée lorsque le document est ouvert. |
| [PageMode](../../aspose.pdf/document/pagemode/) { get; set; } | Obtient ou définit le mode de page, spécifiant comment le document doit être affiché lorsqu'il est ouvert. |
| [Pages](../../aspose.pdf/document/pages/) { get; } | Obtient ou définit la collection de pages du document. Notez que les pages sont numérotées à partir de 1 dans la collection. |
| [PdfFormat](../../aspose.pdf/document/pdfformat/) { get; } | Obtient le format PDF |
| [Permissions](../../aspose.pdf/document/permissions/) { get; } | Obtient les autorisations du document. |
| [PickTrayByPdfSize](../../aspose.pdf/document/picktraybypdfsize/) { get; set; } | Obtient ou définit un indicateur spécifiant si la taille de la page PDF doit être utilisée pour sélectionner le bac à papier d'entrée. |
| [PrintScaling](../../aspose.pdf/document/printscaling/) { get; set; } | Obtient ou définit l'option de mise à l'échelle de la page qui doit être sélectionnée lorsque la boîte de dialogue d'impression est affichée pour ce document. |
| [TaggedContent](../../aspose.pdf/document/taggedcontent/) { get; } | Obtient l'accès au contenu TaggedPdf. |
| [Version](../../aspose.pdf/document/version/) { get; } | Obtient une version de Pdf à partir de l'en-tête du fichier Pdf. |
| static [FileSizeLimitToMemoryLoading](../../aspose.pdf/document/filesizelimittomemoryloading/) { get; set; } | Obtient et définit la limite de taille de fichier pour charger un fichier entier en mémoire. La valeur est définie en mégaoctets. La valeur par défaut est 210 Mo. |
| static [IsLicensed](../../aspose.pdf/document/islicensed/) { get; } | Obtient l'état de licence du système. Renvoie vrai si le système fonctionne en mode sous licence et faux sinon. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments)(params Document[]) | Fusionne des documents. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_3)(params string[]) | Fusionne des fichiers PDF. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_1)(MergeOptions, params Document[]) | Fusionne des documents. |
| static [MergeDocuments](../../aspose.pdf/document/mergedocuments/#mergedocuments_2)(MergeOptions, params string[]) | Fusionne des documents. |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml)(Stream) | Lier xml au document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_3)(string) | Lier xml au document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_1)(Stream, Stream) | Lier xml/xsl au document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_4)(string, string) | Lier xml/xsl au document |
| [BindXml](../../aspose.pdf/document/bindxml/#bindxml_2)(Stream, Stream, XmlReaderSettings) | Lier xml/xsl au document |
| [ChangePasswords](../../aspose.pdf/document/changepasswords/)(string, string, string) | Change les mots de passe du document. Cette action ne peut être effectuée qu'en utilisant le mot de passe propriétaire. |
| [Check](../../aspose.pdf/document/check/)(bool) | Valide le document. |
| [Convert](../../aspose.pdf/document/convert/#convert_2)(PdfFormatConversionOptions) | Convertit le document en utilisant les options de conversion spécifiées |
| [Convert](../../aspose.pdf/document/convert/#convert_3)(CallBackGetHocr, bool) | Reconnaît les images à l'intérieur du document et ajoute des chaînes hocr par-dessus. |
| [Convert](../../aspose.pdf/document/convert/#convert_4)(CallBackGetHocrWithPage, bool) | Reconnaît les images à l'intérieur du document et ajoute des chaînes hocr par-dessus. |
| [Convert](../../aspose.pdf/document/convert/#convert_5)(Stream, PdfFormat, ConvertErrorAction) | Convertit le document et enregistre les erreurs dans le flux spécifié. |
| [Convert](../../aspose.pdf/document/convert/#convert_7)(string, PdfFormat, ConvertErrorAction) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| [Convert](../../aspose.pdf/document/convert/#convert)(Fixup, Stream, bool, object[]) | Convertit le document en appliquant le Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_1)(Fixup, string, bool, object[]) | Convertit le document en appliquant le Fixup. |
| [Convert](../../aspose.pdf/document/convert/#convert_6)(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| [Convert](../../aspose.pdf/document/convert/#convert_8)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Convertit le document et enregistre les erreurs dans le fichier spécifié. |
| [ConvertPageToPNGMemoryStream](../../aspose.pdf/document/convertpagetopngmemorystream/)(Page) | Convertit la page en PNG pour le flux d'image DSR, OMR, OCR. |
| [Decrypt](../../aspose.pdf/document/decrypt/)() | Décrypte le document. Appelez ensuite Save pour obtenir la version décryptée du document. |
| [Dispose](../../aspose.pdf/document/dispose/)() | Ferme toutes les ressources utilisées par ce document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_1)(string, string, Permissions, CryptoAlgorithm) | Crypte le document. Appelez ensuite Save pour obtenir la version cryptée du document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt)(string, string, DocumentPrivilege, CryptoAlgorithm, bool) | Crypte le document. Appelez ensuite Save pour obtenir la version cryptée du document. |
| [Encrypt](../../aspose.pdf/document/encrypt/#encrypt_2)(string, string, Permissions, CryptoAlgorithm, bool) | Crypte le document. Appelez ensuite Save pour obtenir la version cryptée du document. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf)(Stream) | Exporte toutes les annotations du document dans le flux. |
| [ExportAnnotationsToXfdf](../../aspose.pdf/document/exportannotationstoxfdf/#exportannotationstoxfdf_1)(string) | Exporte toutes les annotations du document vers un fichier XFDF |
| [Flatten](../../aspose.pdf/document/flatten/#flatten)() | Supprime tous les champs du document et place leurs valeurs à la place. |
| [Flatten](../../aspose.pdf/document/flatten/#flatten_1)(FlattenSettings) | Supprime tous les champs (et annotations) du document et place leurs valeurs à la place. |
| [FlattenTransparency](../../aspose.pdf/document/flattentransparency/)() | Remplace le contenu transparent par des graphiques raster et vectoriels non transparents. |
| [FreeMemory](../../aspose.pdf/document/freememory/)() | Efface la mémoire |
| [GetCatalogValue](../../aspose.pdf/document/getcatalogvalue/)(string) | Renvoie la valeur de l'élément du dictionnaire de catalogues. |
| [GetObjectById](../../aspose.pdf/document/getobjectbyid/)(string) | Obtient un objet avec l'ID spécifié dans le document. |
| [GetXmpMetadata](../../aspose.pdf/document/getxmpmetadata/)(Stream) | Obtient les métadonnées XMP du document. |
| [HasIncrementalUpdate](../../aspose.pdf/document/hasincrementalupdate/)() | Vérifie si le document PDF actuel a été enregistré avec des mises à jour incrémentielles. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importe des annotations du flux vers le document. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf/document/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importe des annotations du fichier XFDF vers le document. |
| [IsRepairNeeded](../../aspose.pdf/document/isrepairneeded/)(out RepairOptions) | Vérifie si le document nécessite un appel à la méthode Repair. |
| [LoadFrom](../../aspose.pdf/document/loadfrom/)(string, LoadOptions) | Charge un fichier, le convertissant en PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge)(params Document[]) | Fusionne des documents. |
| [Merge](../../aspose.pdf/document/merge/#merge_3)(params string[]) | Fusionne des fichiers PDF. |
| [Merge](../../aspose.pdf/document/merge/#merge_1)(MergeOptions, params Document[]) | Fusionne des documents. |
| [Merge](../../aspose.pdf/document/merge/#merge_2)(MergeOptions, params string[]) | Fusionne des documents. |
| [Optimize](../../aspose.pdf/document/optimize/)() | Linéarise le document afin de - ouvrir la première page aussi rapidement que possible ; - afficher la page suivante ou suivre un lien vers la page suivante aussi rapidement que possible ; - afficher la page de manière incrémentielle à mesure qu'elle arrive lorsque les données pour une page sont livrées sur un canal lent (afficher d'abord les données les plus utiles) ; - permettre l'interaction de l'utilisateur, comme suivre un lien, à effectuer même avant que la page entière ait été reçue et affichée. L'invocation de cette méthode ne sauvegarde pas réellement le document. Au contraire, le document est seulement préparé pour avoir une structure optimisée, appelez ensuite Save pour obtenir un document optimisé. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources)() | Optimise les ressources dans le document : 1. Les ressources qui ne sont pas utilisées sur les pages du document sont supprimées ; 2. Les ressources égales sont regroupées en un seul objet ; 3. Les objets non utilisés sont supprimés. |
| [OptimizeResources](../../aspose.pdf/document/optimizeresources/#optimizeresources_1)(OptimizationOptions) | Optimise les ressources dans le document selon la stratégie d'optimisation définie. |
| [PageNodesToBalancedTree](../../aspose.pdf/document/pagenodestobalancedtree/)(byte) | Organise les nœuds d'arbre de page dans un document en un arbre équilibré. Seulement si le document a plus de nodesNumInSubtrees objets de page, sinon il ne fait rien. Ne pas appeler cette méthode lors de l'itération sur les éléments Pages, cela peut donner des résultats imprévisibles |
| [ProcessParagraphs](../../aspose.pdf/document/processparagraphs/)() | Traite les paragraphes pour le générateur. |
| [RemoveMetadata](../../aspose.pdf/document/removemetadata/)() | Supprime les métadonnées du document. |
| [RemovePdfaCompliance](../../aspose.pdf/document/removepdfacompliance/)() | Supprime la conformité pdfa du document |
| [RemovePdfUaCompliance](../../aspose.pdf/document/removepdfuacompliance/)() | Supprime la conformité pdfUa du document |
| [Repair](../../aspose.pdf/document/repair/)(RepairOptions) | Répare le document corrompu. |
| [Save](../../aspose.pdf/document/save/#save)() | Sauvegarde le document de manière incrémentielle (c'est-à-dire en utilisant la technique de mise à jour incrémentielle). |
| [Save](../../aspose.pdf/document/save/#save_1)(SaveOptions) | Sauvegarde le document avec des options de sauvegarde. |
| [Save](../../aspose.pdf/document/save/#save_2)(Stream) | Stocke le document dans un flux. |
| [Save](../../aspose.pdf/document/save/#save_5)(string) | Sauvegarde le document dans le fichier spécifié. |
| [Save](../../aspose.pdf/document/save/#save_3)(Stream, SaveFormat) | Sauvegarde le document avec un nouveau nom ainsi qu'un format de fichier. |
| [Save](../../aspose.pdf/document/save/#save_4)(Stream, SaveOptions) | Sauvegarde le document dans un flux avec des options de sauvegarde. |
| [Save](../../aspose.pdf/document/save/#save_6)(string, SaveFormat) | Sauvegarde le document avec un nouveau nom ainsi qu'un format de fichier. |
| [Save](../../aspose.pdf/document/save/#save_7)(string, SaveOptions) | Sauvegarde le document avec un nouveau nom en définissant ses options de sauvegarde. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_7)(CancellationToken) | Sauvegarde le document de manière incrémentielle (c'est-à-dire en utilisant la technique de mise à jour incrémentielle). |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync)(SaveOptions, CancellationToken) | Sauvegarde le document avec des options de sauvegarde. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_3)(Stream, CancellationToken) | Stocke le document dans un flux. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_6)(string, CancellationToken) | Sauvegarde le document dans le fichier spécifié. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_1)(Stream, SaveFormat, CancellationToken) | Sauvegarde le document avec un nouveau nom ainsi qu'un format de fichier. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_2)(Stream, SaveOptions, CancellationToken) | Sauvegarde le document dans un flux avec des options de sauvegarde. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_4)(string, SaveFormat, CancellationToken) | Sauvegarde le document avec un nouveau nom ainsi qu'un format de fichier. |
| [SaveAsync](../../aspose.pdf/document/saveasync/#saveasync_5)(string, SaveOptions, CancellationToken) | Sauvegarde le document avec un nouveau nom en définissant ses options de sauvegarde. |
| [SaveXml](../../aspose.pdf/document/savexml/)(string) | Sauvegarde le document au format XML. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_2)(DocumentDevice, Stream) | Envoie l'ensemble du document à l'appareil de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_3)(DocumentDevice, string) | Envoie l'ensemble du document à l'appareil de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto)(DocumentDevice, int, int, Stream) | Envoie certaines pages du document à l'appareil de document pour traitement. |
| [SendTo](../../aspose.pdf/document/sendto/#sendto_1)(DocumentDevice, int, int, string) | Envoie l'ensemble du document à l'appareil de document pour traitement. |
| [SetTitle](../../aspose.pdf/document/settitle/)(string) | Définit le titre pour le document PDF |
| [SetXmpMetadata](../../aspose.pdf/document/setxmpmetadata/)(Stream) | Définit les métadonnées XMP du document. |
| [Validate](../../aspose.pdf/document/validate/#validate)(PdfFormatConversionOptions) | Valide le document dans le fichier spécifié. |
| [Validate](../../aspose.pdf/document/validate/#validate_1)(Stream, PdfFormat) | Valide le document dans le fichier spécifié. |
| [Validate](../../aspose.pdf/document/validate/#validate_2)(string, PdfFormat) | Valide le document dans le fichier spécifié. |
| static [Convert](../../aspose.pdf/document/convert/#convert)(Stream, LoadOptions, Stream, SaveOptions) | Convertit le flux dans le format source en flux dans le format de destination. |
| static [Convert](../../aspose.pdf/document/convert/#convert_1)(Stream, LoadOptions, string, SaveOptions) | Convertit le flux dans le format source en fichier de destination dans le format de destination. |
| static [Convert](../../aspose.pdf/document/convert/#convert_2)(string, LoadOptions, Stream, SaveOptions) | Convertit le fichier source dans le format source en flux dans le format de destination. |
| static [Convert](../../aspose.pdf/document/convert/#convert_3)(string, LoadOptions, string, SaveOptions) | Convertit le fichier source dans le format source en fichier de destination dans le format de destination. |
| static [SetDefaultFileSizeLimitToMemoryLoading](../../aspose.pdf/document/setdefaultfilesizelimittomemoryloading/)() | Définit la limite de taille de fichier pour charger un fichier entier en mémoire à la valeur par défaut égale à 210 Mo. |

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
| class [MergeOptions](../../aspose.pdf/document.mergeoptions) | Représente les options pour les méthodes de fusion. |
| class [RepairOptions](../../aspose.pdf/document.repairoptions) | Représente les options pour réparer un document PDF. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)