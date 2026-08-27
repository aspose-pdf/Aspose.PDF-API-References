---
title: "Classe HtmlSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "classe Aspose.Pdf.HtmlSaveOptions. Options d'enregistrement pour l'exportation au format Html"
type: docs
weight: 5690
url: /fr/net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Options d'enregistrement pour l'exportation au format Html

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Initialise une nouvelle instance de la classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Initialise une nouvelle instance de la classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Initialise une nouvelle instance de la classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Initialise une nouvelle instance de la classe `HtmlSaveOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de la conversion pdf vers d’autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l’objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Obtient ou définit le drapeau qui indique si les graphiques SVG trouvés (le cas échéant) seront compressés (zippés) au format SVGZ lors de l'enregistrement. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Si l'attribut ConvertMarkedContentToLayers est défini sur true, alors tous les éléments à l'intérieur d'un contenu marqué PDF (couche) seront placés dans une div HTML avec l'attribut "data-pdflayer" spécifiant un nom de couche. Ce nom de couche sera extrait des propriétés optionnelles du contenu marqué PDF. Si cet attribut est false (par défaut), aucune couche ne sera créée à partir du contenu marqué PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Spécifie le nom d'une police installée qui est utilisée pour remplacer toute police de document qui n'est pas incorporée et n'est pas installée dans le système. Si null, la police de substitution par défaut est utilisée. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Obtient ou définit le [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent être numérotées à partir de 1. C’est‑à‑dire que les numéros valides de pages doivent être pris dans la plage (1...[NumberOfPagesInConvertedDocument]). L’ordre d’apparition des pages dans cette liste n’affecte pas leur ordre dans les pages HTML résultantes — dans les pages résultantes, elles seront toujours présentées dans l’ordre où elles figurent dans le PDF source. Si cette liste est null (comme c’est le cas par défaut), toutes les pages seront converties. Si un numéro de page de cette liste dépasse la plage des pages présentes (1-[amountOfPagesInDocument]), une exception sera levée. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d’extraction d’image ou de texte pour les documents PDF avec une sous-couche OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Obtient ou définit une valeur indiquant si ce HTML est créé avec une mise en page fixe. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Cet attribut spécifie un texte de paragraphe en pleine largeur pour le mode Flux, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Sources de polices des polices préenregistrées. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Le texte dont la taille est spécifiée ou inférieure sera ignoré lors de la conversion. Nous ne supprimons pas ce texte, nous l'ignorons et ne le transférons pas dans le fichier de sortie. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte qui font référence à des ressources incorrectes seront ignorés pendant le traitement. false par défaut |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Obtient ou définit la résolution pour le rendu d’image. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Cet attribut définit la largeur minimale de la ligne du chemin graphique. Si l’épaisseur de la ligne est inférieure à 1 px, Adobe Acrobat l’arrondit à cette valeur. Ainsi, cet attribut peut être utilisé pour émuler ce comportement dans les navigateurs HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Cet attribut active le mode où les glyphes de texte ne seront pas regroupés en mots et chaînes. Ce mode permet de conserver une précision maximale lors du positionnement des glyphes sur la page et peut être utilisé pour la conversion de documents contenant des notes de musique ou des glyphes qui doivent être placés séparément les uns des autres. Ce paramètre ne sera appliqué au document que lorsque la valeur de l’attribut FixedLayout est vraie. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Si l’attribut RenderTextAsImage est défini sur true, le texte de la source devient une image dans le HTML. Cela peut être utile pour rendre le texte non sélectionnable ou si le texte HTML n’est pas rendu correctement. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format d’enregistrement des données. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Indique que la police complète sera enregistrée, ne prend en charge que les polices True Type. Par défaut, SaveFullFont = false et le convertisseur enregistre le sous‑ensemble de la police initiale nécessaire pour afficher le texte du document. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Cet attribut spécifie un regroupement séquentiel des glyphes et des mots en chaînes. Par exemple, les balises et les mots ont un ordre différent dans le HTML converti et vous souhaitez qu’ils correspondent. Ce paramètre ne sera appliqué au document que lorsque la valeur de l’attribut FixedLayout est vraie. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Lorsque le mode multipage est sélectionné (c’est‑à‑dire que 'SplitIntoPages' est true), cet attribut définit s’il faut créer un fichier CSS séparé pour chaque page HTML résultante. Par défaut, cet attribut est false, donc un seul grand CSS commun est créé pour toutes les pages générées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement bien supérieure à celle d’un seul grand fichier CSS, car dans le premier cas les classes CSS sont dupliquées dans plusieurs fichiers CSS pour chaque page. Ainsi, ce réglage ne doit être utilisé que si vous avez besoin de traiter chaque page HTML indépendamment, et que la taille du CSS de chaque page séparée est le critère le plus critique. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Obtient ou définit le drapeau qui indique si chaque page du document source sera convertie en son propre document HTML cible, c’est‑à‑dire si le HTML résultant sera divisé en plusieurs pages HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Obtient ou définit le titre de la page HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Le drapeau pour combiner les fragments d’image en une seule image. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Si l’attribut UseZORder est défini sur true, les graphiques et le texte sont ajoutés au document HTML résultant selon l’ordre Z du document PDF original. Si cet attribut est false, tous les graphiques sont placés sur une seule couche, ce qui peut entraîner des effets indésirables pour les objets qui se chevauchent. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Rappel pour gérer les avertissements générés. Le WarningHandler renvoie l’élément d’énumération ReturnAction spécifiant soit Continue, soit Abort. Continue est l’action par défaut et l’opération Save se poursuit, cependant l’utilisateur peut également renvoyer Abort auquel cas l’opération Save doit s’arrêter. |

## Champs

| Nom | Description |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Ce paramètre définit les mesures d’antialiasing requises lors de la conversion des images d’arrière‑plan composées du PDF vers le HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Lorsque le convertisseur PDFtoHTML génère les CSS résultants, les noms de classes CSS (quelque chose comme \".stl_01 {}\" ... \".stl_NN {}\") sont créés et utilisés dans le CSS final. Cette propriété permet de définir de force le préfixe des noms de classe. Par exemple, si vous souhaitez que tous les noms de classe commencent par 'my_prefix_' (c’est‑à‑dire qu’ils ressemblent à 'my_prefix_1' ... 'my_prefix_NNN'), il suffit d’attribuer 'my_prefix_' à cette propriété avant la conversion. Si cette propriété reste inchangée (c’est‑à‑dire que la valeur null est laissée), le convertisseur générera lui‑même les noms de classe (ce sera quelque chose comme \".stl_01 {}\" ... \".stl_NN {}\"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Ce champ peut contenir la stratégie d’enregistrement qui doit être utilisée (si elle est présente) lors de la conversion de PDF en HTML pour la gestion de l’enregistrement des CSS liés au document HTML créé dans son ensemble ou à ses pages (si plusieurs pages HTML sont générées). Si vous souhaitez gérer le fichier CSS d’une manière spécifique, créez simplement la méthode correspondante et assignez le délégué créé à partir de celle‑ci à cette propriété. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez affecter à cette propriété un délégué créé à partir d’une méthode personnalisée qui implémente le traitement d’une page HTML (précisément : le balisage HTML, sans fichiers liés externes le cas échéant) générée pendant la conversion. Dans ce cas, le traitement (comme l’enregistrement du HTML de la page dans un flux ou sur le disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires à l’enregistrement de la page HTML doivent être réalisées dans le code de la méthode fournie, car l’enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement doit être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'htmlSavingInfo' : il signalera au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur lui‑même, de la même façon que s’il n’y avait aucun code personnalisé externe pour le traitement. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex. il peut servir à afficher une barre de progression ou des messages sur le nombre actuel de pages traitées ; un exemple de code du gestionnaire qui affiche la progression dans la console est : |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Ce champ peut contenir la stratégie d’enregistrement qui doit être utilisée (si elle est présente) pendant la conversion pour la gestion personnalisée des fichiers de ressources référencés créés (comme les images et les polices) liés aux nœuds du HTML enregistré. Cette stratégie doit traiter les ressources et retourner une chaîne représentant l’URL souhaitée de la ressource enregistrée dans le HTML généré. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Ce champ peut contenir une méthode personnalisée qui renvoie l’URL (ou le modèle d’URL si la génération multipage est activée – voir les détails ci‑dessous) du CSS concerné tel qu’il doit être inséré dans le HTML résultant généré. Par ex., si vous souhaitez que le convertisseur place une URL spécifique à la place du nom de fichier CSS standard dans le CSS généré, vous devez simplement créer et affecter à cette propriété une méthode qui génère l’URL souhaitée. Si le drapeau 'SplitCssIntoPages' est défini, alors cette stratégie personnalisée (le cas échéant) doit renvoyer non pas l’URL exacte du CSS mais plutôt une chaîne modèle qui (après substitution du paramètre par le numéro de page avec la fonction string.Format() du convertisseur) peut être résolue en URL pour le CSS de cette page ou de cette autre page. Exemples de chaînes de retour attendues dans ce cas : 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Liste des noms de polices PDF intégrées qui ne doivent pas être incorporées dans le HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Définit une règle spéciale d’encodage pour ajuster le décodage PDF du document actuel. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Définit le mode d’enregistrement des polices qui sera utilisé lors de l’enregistrement du PDF dans le format souhaité. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Parfois, des exigences spécifiques à la génération du balisage HTML sont présentes. Ce paramètre définit les modes de préparation HTML qui peuvent être utilisés lors de la conversion de PDF en HTML afin de répondre à ces exigences spécifiques. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traiter les pages avec quelques threads. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Définit le mode de positionnement des lettres dans les mots dans le HTML résultant. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Cet attribut représente l’ensemble des paramètres utilisés pour dessiner une bordure (le cas échéant) dans le document HTML résultant autour de la zone représentant la page PDF source. En essence, il concerne l’affichage des bords du papier de la page, et non la bordure de la page référencée dans le PDF lui‑même. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Cet attribut représente l’ensemble des marges de page supplémentaires (le cas échéant) dans le document HTML résultant autour de la zone représentant la page PDF source. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Si l’attribut 'SplitOnPages=false', alors l’ensemble du HTML représentant toutes les pages PDF d’entrée sera placé dans un seul grand fichier HTML résultant. Ce drapeau définit si le HTML résultant sera généré de manière à ce que le flux des zones représentant les pages PDF dans le HTML dépendre de la résolution d’écran du visualiseur. Supposons que la largeur de l’écran du visualiseur soit suffisante pour placer deux pages ou plus côte à côte en direction horizontale. Si ce drapeau est défini sur true, alors cette possibilité sera utilisée (autant de pages seront affichées horizontalement côte à côte que possible, puis le groupe horizontal suivant sera affiché sous le premier). Sinon, les pages s’écouleront de la façon suivante : la page suivante se place toujours sous la précédente. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Il définit si les fichiers référencés (HTML, polices, images, CSS) seront incorporés dans le fichier HTML principal ou seront générés en tant qu'entités binaires séparées |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Le PDF converti peut contenir des images raster. Ce paramètre définit comment elles doivent être traitées lors de la conversion du PDF en HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Définit si, dans le HTML créé, les zones vides supérieures et inférieures sans aucun contenu (le cas échéant) seront supprimées. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | Le PDF peut contenir des textes masqués par d'autres éléments (par ex. par des images) mais pouvant être sélectionnés dans le presse‑papier avec Acrobat Reader (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML résultant afin d'imiter le comportement d'Acrobat Reader (sinon ces textes sont généralement enregistrés comme cachés, non disponibles pour la copie). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | Le PDF peut contenir des textes transparents pouvant être sélectionnés dans le presse‑papier (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML résultant. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Obtient ou définit le chemin du répertoire dans lequel toutes les images doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers image (le cas échéant) seront enregistrés avec les autres fichiers liés au HTML. Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Obtient ou définit le chemin du répertoire dans lequel seules les images SVG doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers SVG (le cas échéant) seront enregistrés avec les autres fichiers image (près du fichier de sortie) ou dans un dossier spécial pour les images (si indiqué dans l’option SpecialImagesFolderIfAny). Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDFs contiennent des images d’arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d’arrière‑plan en mosaïque identiques placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par ex. MsWord pour le format DOCS) génèrent parfois des bordures visibles entre les parties des images d’arrière‑plan, car leurs techniques de lissage des bords d’image (anti‑aliasing) diffèrent de celles d’Acrobat Reader. Si le document exporté semble contenir de telles bordures visibles entre les parties des mêmes images d’arrière‑plan, veuillez essayer d’utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez n’utiliser cette option que lorsqu’elle est réellement nécessaire. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | Le PDF lui‑même ne contient pas de repères de soulignement pour les textes. Il les émule avec une ligne placée sous le texte. Cette option permet au convertisseur d’essayer de deviner qu’une ligne est le soulignement d’un texte et d’insérer cette information dans le CSS au lieu de dessiner le soulignement graphiquement. |

## Exemples

L’exemple suivant montre comment convertir un fichier PDF en fichier HTML

```csharp
[C#]
	// Le chemin du répertoire des documents.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// Le chemin vers votre fichier PDF.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// Le chemin du fichier HTML de sortie.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialiser HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Enregistrer le fichier HTML
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### Voir aussi

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


