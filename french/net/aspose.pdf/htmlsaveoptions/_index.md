---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlSaveOptions. Options d'enregistrement pour l'exportation au format Html
type: docs
weight: 5560
url: /fr/net/aspose.pdf/htmlsaveoptions/
---
## Classe HtmlSaveOptions

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
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si les glyphes de police seront mis en cache lors de la préparation des pages aps. Améliore les performances de conversion de PDF vers d'autres formats mais augmente la consommation de mémoire. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtient ou définit la valeur booléenne qui indique si l'objet Response sera fermé après que le document ait été enregistré dans la réponse. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Obtient ou définit le drapeau qui indique si les graphiques SVG trouvés (le cas échéant) seront compressés (zippés) au format SVGZ lors de l'enregistrement. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Si l'attribut ConvertMarkedContentToLayers est défini sur true, alors tous les éléments à l'intérieur d'un contenu marqué PDF (couche) seront placés dans un div HTML avec l'attribut "data-pdflayer" spécifiant un nom de couche. Ce nom de couche sera extrait des propriétés optionnelles du contenu marqué PDF. Si cet attribut est faux (par défaut), aucune couche ne sera créée à partir du contenu marqué PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Spécifie le nom d'une police installée qui est utilisée pour substituer toute police de document qui n'est pas intégrée et non installée dans le système. Si null, alors la police de substitution par défaut est utilisée. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Obtient ou définit le [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent avoir des numéros basés sur 1. C'est-à-dire que les numéros de pages valides doivent être pris dans la plage (1...[NumberOfPagesInConvertedDocument]). L'ordre d'apparition des pages dans cette liste n'affecte pas leur ordre dans la ou les pages HTML résultantes - dans les pages résultantes, elles apparaîtront toujours dans l'ordre dans lequel elles sont présentes dans le PDF source. Si cette liste est nulle (comme c'est le cas par défaut), toutes les pages seront converties. Si un numéro de page de cette liste sort de la plage des pages présentes (1-[amountOfPagesInDocument]), une exception sera levée. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Cet attribut active la fonctionnalité d'extraction d'image ou de texte pour les documents PDF avec sous-couche OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Obtient ou définit une valeur indiquant si le HTML est créé en tant que mise en page fixe. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Cet attribut spécifie le texte de paragraphe en pleine largeur pour le mode Flow, FixedLayout = false. |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Sources de police des polices pré-enregistrées. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Le texte avec la taille spécifiée ou moins sera ignoré lors de la conversion. Nous ne supprimons pas ce texte, nous l'ignorons et ne le transférons pas dans le fichier de sortie. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Obtient ou définit l'indication que les erreurs liées à l'absence de police seront ignorées. true - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte qui se réfèrent à des ressources incorrectes seront ignorés lors du traitement. faux par défaut. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Obtient ou définit la résolution pour le rendu des images. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Cet attribut définit la largeur minimale de la ligne du chemin graphique. Si l'épaisseur de la ligne est inférieure à 1px, Adobe Acrobat l'arrondit à cette valeur. Donc, cet attribut peut être utilisé pour émuler ce comportement pour les navigateurs HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Cet attribut active le mode où les glyphes de texte ne seront pas regroupés en mots et chaînes. Ce mode permet de conserver une précision maximale lors du positionnement des glyphes sur la page et peut être utilisé pour la conversion de documents avec des notes de musique ou des glyphes qui doivent être placés séparément les uns des autres. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Si l'attribut RenderTextAsImage est défini sur true, le texte de la source devient une image dans HTML. Peut être utile pour rendre le texte non sélectionnable ou si le texte HTML n'est pas rendu correctement. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format de sauvegarde des données. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Indique que la police complète sera sauvegardée, ne prend en charge que les polices True Type. Par défaut, SaveFullFont = false et le convertisseur sauvegarde le sous-ensemble de la police initiale nécessaire pour afficher le texte du document. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Cet attribut spécifie un regroupement séquentiel des glyphes et des mots en chaînes. Par exemple, les balises et les mots ont un ordre différent dans le HTML converti et vous souhaitez qu'ils correspondent. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Lorsque le mode multipage est sélectionné (c'est-à-dire que 'SplitIntoPages' est 'true'), cet attribut définit s'il faut créer un fichier CSS séparé pour chaque page HTML résultante. Par défaut, cet attribut est faux, donc un grand CSS commun sera créé pour toutes les pages créées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement beaucoup plus grande que la taille d'un grand fichier CSS, car dans le premier cas, les classes CSS sont des doublons dans plusieurs fichiers CSS pour chaque page. Donc, ce paramètre est à utiliser uniquement lorsque vous êtes intéressé par le traitement futur de chaque page HTML indépendamment, et donc la taille du CSS de chaque page prise séparément est le problème le plus critique. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Obtient ou définit le drapeau qui indique si chaque page du document source sera convertie en son propre document HTML cible, c'est-à-dire si le HTML résultant sera divisé en plusieurs pages HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Obtient ou définit le titre de la page HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | Le drapeau pour combiner les fragments d'image en une seule image. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Si l'attribut UseZOrder est défini sur true, les graphiques et le texte sont ajoutés au document HTML résultant conformément à l'ordre Z dans le document PDF original. Si cet attribut est faux, tous les graphiques sont placés comme une seule couche, ce qui peut provoquer des effets indésirables pour les objets superposés. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback pour gérer les avertissements générés. Le WarningHandler retourne un élément de l'énumération ReturnAction spécifiant soit Continuer soit Abandonner. Continuer est l'action par défaut et l'opération de sauvegarde continue, cependant, l'utilisateur peut également retourner Abandonner, auquel cas l'opération de sauvegarde doit cesser. |

## Champs

| Nom | Description |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Ce paramètre définit les mesures d'anticrénelage requises lors de la conversion d'images d'arrière-plan composées de PDF à HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Lorsque le convertisseur PDFtoHTML génère des CSS résultants, les noms de classes CSS (quelque chose comme ".stl_01 {}" ... ".stl_NN {}") sont générés et utilisés dans le CSS résultant. Cette propriété permet de définir de force le préfixe du nom de classe. Par exemple, si vous souhaitez que tous les noms de classes commencent par 'my_prefix_' (c'est-à-dire soient quelque chose comme 'my_prefix_1' ... 'my_prefix_NNN'), alors il suffit d'assigner 'my_prefix_' à cette propriété avant la conversion. Si cette propriété reste intacte (c'est-à-dire que null est laissé comme valeur), alors le convertisseur générera lui-même les noms de classes (ce sera quelque chose comme ".stl_01 {}" ... ".stl_NN {}"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) lors de la conversion de PDF à HTML pour le traitement de l'enregistrement des CSS liés au document HTML créé dans son ensemble ou à ses pages (si plusieurs pages HTML sont générées). Si vous souhaitez traiter le fichier CSS d'une manière spécifique, veuillez créer la méthode pertinente et assigner le délégué créé à cette propriété. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez assigner à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une page HTML (pour être précis - HTML de balisage, sans fichiers liés externes le cas échéant) qui a été créée lors de la conversion. Dans ce cas, le traitement (comme l'enregistrement du HTML de la page dans un flux ou sur le disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour l'enregistrement de la page HTML doivent être entreprises dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si le traitement pour ce cas ou un autre doit pour une raison quelconque être effectué par le code du convertisseur lui-même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable 'htmlSavingInfo' : cela signalera au convertisseur que toutes les étapes nécessaires pour le traitement de cette ressource doivent être effectuées dans le convertisseur lui-même de la même manière que s'il n'y avait pas de code personnalisé externe pour le traitement. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Ce gestionnaire peut être utilisé pour gérer les événements de progression de conversion, par exemple, il peut être utilisé pour afficher une barre de progression ou des messages sur le nombre actuel de pages traitées, un exemple de code de gestionnaire qui montre la progression sur la console est : |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) lors de la conversion pour le traitement personnalisé des fichiers de ressources référencés créés (comme des images et des polices) liés aux nœuds du HTML enregistré. Cette stratégie doit traiter les ressources et retourner une chaîne qui représente l'URL souhaitée de la ressource enregistrée dans le HTML généré. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Ce champ peut contenir une méthode personnalisée qui retourne l'URL (ou le modèle d'URL si la génération multipage est activée - voir les détails ci-dessous) du CSS sujet tel qu'il doit être placé dans le HTML résultant généré. Par exemple, si vous souhaitez que le convertisseur mette une URL spécifique à la place du nom de fichier CSS standard dans le CSS généré, alors vous devez simplement créer et mettre dans cette propriété une méthode qui génère l'URL souhaitée. Si le drapeau 'SplitCssIntoPages' est défini, alors cette stratégie personnalisée (le cas échéant) doit retourner non pas l'URL exacte du CSS mais plutôt une chaîne modèle qui (après substitution du placeholder avec le numéro de page avec la fonction string.Format() à l'intérieur du convertisseur) peut être résolue en URL pour l'URL du CSS de cette page. Des exemples de chaîne de retour attendue dans ce cas sont : 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Liste des noms de polices intégrées PDF qui ne seront pas intégrées dans le HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Définit une règle d'encodage spéciale pour ajuster le décodage PDF pour le document actuel. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Définit le mode d'enregistrement des polices qui sera utilisé lors de l'enregistrement de PDF au format souhaité. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Parfois, des exigences spécifiques pour la génération de balisage HTML sont présentes. Ce paramètre définit les modes de préparation HTML qui peuvent être utilisés lors de la conversion de PDF à HTML pour correspondre à ces exigences spécifiques. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Traite les pages dans plusieurs threads. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Définit le mode de positionnement des lettres dans les mots dans le HTML résultant. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Cet attribut représente un ensemble de paramètres utilisés pour dessiner une bordure (le cas échéant) dans le document HTML résultant autour de la zone représentant la page PDF source. En essence, cela concerne l'affichage des bords du papier de la page, pas la bordure de la page référencée dans la page PDF elle-même. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Cet attribut représente un ensemble de marges supplémentaires de page (le cas échéant) dans le document HTML résultant autour de la zone représentant la page PDF source. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée sera placé dans un grand fichier HTML résultant. Ce drapeau définit si le HTML résultant sera généré de manière à ce que le flux des zones représentant les pages PDF dans le HTML résultant dépende de la résolution de l'écran du visualiseur. Supposons que la largeur de l'écran du côté du visualiseur soit suffisamment grande pour placer 2 pages ou plus côte à côte dans la direction horizontale. Si ce drapeau est défini sur true, alors cette opportunité sera utilisée (autant de pages que possible seront affichées dans la direction horizontale les unes à côté des autres, puis le prochain groupe horizontal de pages sera affiché sous le premier). Sinon, les pages s'écouleront de la manière suivante : la page suivante va toujours sous la précédente. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Il définit si les fichiers référencés (HTML, polices, images, CSS) seront intégrés dans le fichier HTML principal ou générés en tant qu'entités binaires séparées. |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | Le PDF converti peut contenir des images raster. Ce paramètre définit comment elles doivent être traitées lors de la conversion de PDF à HTML. |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Définit si dans le HTML créé seront supprimées les zones vides en haut et en bas sans contenu (le cas échéant). |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | Le PDF peut contenir des textes qui sont ombragés par d'autres éléments (par exemple, par des images) mais peuvent être sélectionnés dans le presse-papiers dans Acrobat Reader (cela se produit généralement lorsque le document contient des images et des textes OCR extraits de celui-ci). Ce paramètre indique au convertisseur si nous devons enregistrer ces textes en tant que textes transparents sélectionnables dans le HTML résultant pour imiter le comportement d'Acrobat Reader (sinon, ces textes sont généralement enregistrés comme cachés, non disponibles pour la copie dans le presse-papiers). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | Le PDF peut contenir des textes transparents qui peuvent être sélectionnés dans le presse-papiers (cela se produit généralement lorsque le document contient des images et des textes OCR extraits de celui-ci). Ce paramètre indique au convertisseur si nous devons enregistrer ces textes en tant que textes transparents sélectionnables dans le HTML résultant. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Obtient ou définit le chemin vers le répertoire dans lequel toutes les images doivent être enregistrées si elles sont rencontrées lors de l'enregistrement du document en tant que HTML. Si le paramètre est vide ou null, alors les fichiers image (le cas échéant) seront enregistrés avec d'autres fichiers liés au HTML. Cela n'affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image pertinent. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Obtient ou définit le chemin vers le répertoire dans lequel seules les images SVG doivent être enregistrées si elles sont rencontrées lors de l'enregistrement du document en tant que HTML. Si le paramètre est vide ou null, alors les fichiers SVG (le cas échéant) seront enregistrés avec d'autres fichiers image (près du fichier de sortie) ou dans un dossier spécial pour les images (s'il est spécifié dans l'option SpecialImagesFolderIfAny). Cela n'affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image pertinent. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Parfois, les PDF contiennent des images d'arrière-plan (de pages ou de cellules de tableau) construites à partir de plusieurs mêmes images d'arrière-plan en mosaïque placées les unes à côté des autres. Dans ce cas, les rendus des formats cibles (par exemple, MsWord pour le format DOCS) génèrent parfois des frontières visibles entre les parties des images d'arrière-plan, car leurs techniques de lissage des bords d'image (anticrénelage) sont différentes de celles d'Acrobat Reader. Si cela ressemble à un document exporté contenant de telles frontières visibles entre les parties des mêmes images d'arrière-plan, veuillez essayer d'utiliser ce paramètre pour vous débarrasser de cet effet indésirable. ATTENTION ! Cette optimisation de la qualité ralentit généralement considérablement la conversion, donc, veuillez utiliser cette option uniquement lorsque cela est vraiment nécessaire. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | Le PDF lui-même ne contient pas de marqueurs de soulignement pour les textes. Il est émulé avec une ligne située sous le texte. Cette option permet au convertisseur d'essayer de deviner que cette ou cette ligne est un soulignement de texte et de mettre cette information dans le CSS au lieu de dessiner le soulignement graphiquement. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en fichier HTML

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
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

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assemblage [Aspose.PDF](../../)