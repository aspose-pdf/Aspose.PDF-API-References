---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Options d'enregistrement pour l'exportation au format Html"
type: docs
weight: 1990
url: /fr/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

Options d'enregistrement pour l'exportation au format Html

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | Initialise une nouvelle instance de la classe HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | Initialise une nouvelle instance de la classe {@code HtmlSaveOptions}. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | Initialise une nouvelle instance de la classe HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | Initialise une nouvelle instance de la classe HtmlSaveOptions. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée ne sera pas découpé en différentes pages HTML, mais sera placé dans un seul grand fichier HTML résultant. Cependant, chaque page PDF source sera représentée par sa propre zone rectangulaire dans le HTML (si nécessaire, ces zones peuvent être bordées pour afficher les bords du papier de la page avec l'attribut spécial 'PageBorderIfAny'). Ce paramètre définit la largeur de la marge qui sera forcée autour de ces zones HTML de sortie représentant les pages du document PDF source. En essence, il définit l'intervalle garanti entre les représentations HTML des pages \"papier\" du PDF dans ce mode de conversion. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | Ce paramètre définit les mesures d'anticrénelage requises lors de la conversion d'images d'arrière-plan composées du PDF vers le HTML. |
| [getBatchSize](#getBatchSize--) | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | Lorsque le convertisseur PDFtoHTML génère les CSS résultants, les noms de classes CSS (par exemple \".stl_01 {}\" ... \".stl_NN {}\") sont générés et utilisés dans le CSS final. Cette propriété permet de définir de force un préfixe pour les noms de classes. Par exemple, si vous souhaitez que tous les noms de classes commencent par 'my_prefix_' (c’est‑à‑dire quelque chose comme 'my_prefix_1' ... 'my_prefix_NNN'), il suffit d’attribuer 'my_prefix_' à cette propriété avant la conversion. Si cette propriété reste inchangée (c’est‑à‑dire que la valeur null est laissée), le convertisseur générera lui‑même les noms de classes (ce sera quelque chose comme \".stl_01 {}\" ... \".stl_NN {}\"). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si elle est présente) lors de la conversion de PDF en HTML pour la gestion de l'enregistrement des CSS liés au document HTML créé dans son ensemble ou à ses pages (si plusieurs pages HTML sont générées). Si vous souhaitez gérer le fichier CSS d'une manière spécifique, veuillez simplement créer la méthode appropriée et affecter le délégué créé à partir de celle‑ci à cette propriété. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une page HTML (plus précisément du balisage HTML, sans fichiers liés externes le cas échéant) qui a été créée pendant la conversion. Dans ce cas, le traitement (comme l'enregistrement du HTML de la page dans un flux ou sur le disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour enregistrer la page HTML doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement pour tel ou tel cas doit être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'htmlSavingInfo' : cela signalera au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur lui‑même, de la même façon que s'il n'y avait aucun code personnalisé externe pour le traitement. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex. il peut servir à afficher une barre de progression ou des messages concernant le nombre actuel de pages traitées, exemple de code du gestionnaire qui affiche la progression dans la console : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si elle est présente) pendant la conversion pour la gestion personnalisée des fichiers de ressources référencés créés (comme les images et les polices) liés aux nœuds du HTML enregistré. Cette stratégie doit traiter les ressources et renvoyer une chaîne qui représente l'URL souhaitée de la ressource enregistrée dans le HTML généré. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | Ce champ peut contenir une méthode personnalisée qui renvoie l'URL (ou le modèle d'URL si la génération multipage est activée – voir les détails ci‑dessous) du CSS concerné tel qu'il doit être inséré dans le HTML résultant généré. Par ex., si vous souhaitez que le convertisseur place une URL spécifique à la place du nom de fichier CSS standard dans le CSS généré, vous devez simplement créer et affecter à cette propriété une méthode qui génère l'URL souhaitée. Si le drapeau 'SplitCssIntoPages' est défini, alors cette stratégie personnalisée (le cas échéant) doit renvoyer non pas l'URL exacte du CSS mais plutôt une chaîne modèle qui (après substitution du paramètre par le numéro de page avec la fonction String.Format() du convertisseur) peut être résolue en URL pour le CSS de telle ou telle page. Exemples de chaînes de retour attendues dans ce cas : 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' ) |
| [getDefaultFontName](#getDefaultFontName--) | Spécifie le nom d'une police installée qui est utilisée pour remplacer toute police du document qui n'est pas incorporée et qui n'est pas installée dans le système. Si null, la police de substitution par défaut est utilisée. |
| [getDocumentType](#getDocumentType--) | Obtient le {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | Liste des noms de polices PDF incorporées qui ne seront pas incorporées dans le HTML. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent avoir des numéros à base 1. C’est‑à‑dire que les numéros valides de pages doivent être pris dans la plage (1...[NumberOfPagesInConvertedDocument]). L’ordre d’apparition des pages dans cette liste n’affecte pas leur ordre dans la ou les pages HTML résultantes — dans les pages résultantes, elles seront toujours présentées dans l’ordre où elles se trouvent dans le PDF source. Si cette liste est nulle (comme c’est le cas par défaut), toutes les pages seront converties. Si un numéro de page de cette liste dépasse la plage des pages présentes (1-[amountOfPagesInDocument]), une exception sera levée. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | Cet attribut spécifie le texte de paragraphe en pleine largeur pour le mode Flux, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Définit une règle spéciale d’encodage pour ajuster le décodage PDF du document actuel |
| [getFontSavingMode](#getFontSavingMode--) | Définit le mode d’enregistrement des polices qui sera utilisé lors de l’enregistrement du PDF au format souhaité |
| [getFontSources](#getFontSources--) | <p> Sources de polices pré‑enregistrées. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | Parfois, des exigences spécifiques concernant la génération du balisage HTML sont présentes. Ce paramètre définit les modes de préparation HTML qui peuvent être utilisés lors de la conversion de PDF en HTML pour répondre à ces exigences spécifiques. |
| [getImageResolution](#getImageResolution--) | Obtient ou définit la résolution pour le rendu des images. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Définit le mode de positionnement des lettres dans les mots dans le HTML résultant |
| [getMinimalLineWidth](#getMinimalLineWidth--) | Cet attribut définit la largeur minimale d’une ligne de tracé graphique. Si l’épaisseur de la ligne est inférieure à 1 px, Adobe Acrobat l’arrondit à cette valeur. Ainsi, cet attribut peut être utilisé pour émuler ce comportement dans les navigateurs HTML. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | Cet attribut représente un ensemble de paramètres utilisés pour dessiner une bordure (le cas échéant) dans le document HTML résultant autour de la zone qui représente la page PDF source. En essence, il concerne l’affichage des bords du papier de la page, et non la bordure de la page référencée dans le PDF lui‑même. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | Cet attribut représente un ensemble de marges de page supplémentaires (le cas échéant) dans le document HTML résultant autour de la zone qui représente la page PDF source. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | Il définit si les fichiers référencés (HTML, polices, images, CSS) seront incorporés dans le fichier HTML principal ou seront générés comme des entités binaires séparées |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | Le PDF converti peut contenir des images raster. Ce paramètre définit comment elles doivent être traitées lors de la conversion du PDF en HTML |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Obtient ou définit le chemin du répertoire où toutes les images doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers image (le cas échéant) seront enregistrés avec les autres fichiers liés au HTML. Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Obtient ou définit le chemin du répertoire où seules les images SVG doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers SVG (le cas échéant) seront enregistrés avec les autres fichiers image (près du fichier de sortie) ou dans un dossier spécial pour les images (s’il est spécifié dans l’option SpecialImagesFolderIfAny). Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné. |
| [getTitle](#getTitle--) | Obtient ou définit le titre de la page HTML. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Obtient le drapeau indiquant si les graphiques SVG trouvés (le cas échéant) seront compressés (zippés) au format SVGZ lors de l’enregistrement. Valeur : {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | Si l’attribut ConvertMarkedContentToLayers est défini sur true, alors tous les éléments à l’intérieur d’un contenu marqué PDF (couche) seront placés dans une div HTML avec l’attribut \"data-pdflayer\" spécifiant le nom de la couche. Ce nom de couche sera extrait des propriétés optionnelles du contenu marqué PDF. Si cet attribut est false (par défaut), aucune couche ne sera créée à partir du contenu marqué PDF. |
| [isFixedLayout](#isFixedLayout--) | Obtient une valeur indiquant si le HTML est créé en mise en page fixe. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false par défaut |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée sera placé dans un seul grand fichier HTML de résultat. Ce drapeau définit si le HTML de résultat sera généré de manière à ce que le flux des zones représentant les pages PDF dans le HTML de résultat dépende de la résolution d'écran du visualiseur. Supposons que la largeur de l'écran du visualiseur soit suffisante pour placer 2 ou plus de pages côte à côte en direction horizontale. Si ce drapeau est réglé sur true, alors cette opportunité sera utilisée (autant de pages seront affichées en direction horizontale les unes à côté des autres autant que possible, puis le groupe horizontal suivant de pages sera affiché sous le premier). Sinon, les pages s'écouleront de la manière suivante : la page suivante se place toujours sous la précédente. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | Cet attribut active le mode où les glyphes de texte ne seront pas regroupés en mots et chaînes. Ce mode permet de conserver une précision maximale lors du positionnement des glyphes sur la page et peut être utilisé pour la conversion de documents contenant des notes de musique ou des glyphes qui doivent être placés séparément les uns des autres. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Définit si, dans le HTML créé, les zones vides en haut et en bas sans aucun contenu (le cas échéant) seront supprimées. |
| [isRenderTextAsImage](#isRenderTextAsImage--) | Si l'attribut RenderTextAsImage est réglé sur true, le texte de la source devient une image dans le HTML. Cela peut être utile pour rendre le texte non sélectionnable ou si le texte HTML n'est pas rendu correctement. |
| [isSaveFullFont](#isSaveFullFont--) | Indique que la police complète sera enregistrée, ne prend en charge que les polices True Type. Par défaut, SaveFullFont = false et le convertisseur enregistre le sous-ensemble de la police initiale nécessaire pour afficher le texte du document. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | Le PDF peut contenir des textes qui sont ombragés par d'autres éléments (par ex. par des images) mais qui peuvent être sélectionnés dans le presse‑papier dans Acrobat Reader (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML de résultat afin d'imiter le comportement d'Acrobat Reader (sinon ces textes sont généralement enregistrés comme cachés, non disponibles pour la copie). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Le PDF peut contenir des textes transparents qui peuvent être sélectionnés dans le presse‑papier (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML de résultat. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | Cet attribut spécifie un regroupement séquentiel des glyphes et des mots en chaînes. Par exemple, les balises et les mots ont un ordre différent dans le HTML converti et vous souhaitez qu'ils correspondent. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | Lorsque le mode multipage est sélectionné (c’est‑à‑dire que 'SplitIntoPages' est 'true'), cet attribut définit s'il faut créer un fichier CSS séparé pour chaque page HTML de résultat. Par défaut, cet attribut est false, ainsi un seul grand CSS commun est créé pour toutes les pages générées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement bien supérieure à la taille d'un seul grand fichier CSS, car dans le premier cas les classes CSS sont dupliquées dans plusieurs fichiers CSS pour chaque page. Ainsi, ce paramètre est préférable à n’utiliser que lorsque vous êtes intéressé par le traitement futur de chaque page HTML de manière indépendante, et que la taille du CSS de chaque page séparée est le problème le plus critique. |
| [isSplitIntoPages](#isSplitIntoPages--) | Obtient le drapeau qui indique si chaque page du document source sera convertie en son propre document HTML cible, c’est‑à‑dire si le HTML de résultat sera découpé en plusieurs pages HTML. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | Le PDF lui‑même ne contient pas de marqueurs de soulignement pour les textes. Il les émule avec une ligne placée sous le texte. Cette option permet au convertisseur d'essayer de deviner qu'une ligne est le soulignement d'un texte et d'insérer cette information dans le CSS au lieu de dessiner le soulignement graphiquement. |
| [isUseZOrder](#isUseZOrder--) | Si l'attribut UseZORder est réglé sur true, les graphiques et le texte sont ajoutés au document HTML résultant conformément à l'ordre Z du document PDF original. Si cet attribut est false, tous les graphiques sont placés en une seule couche, ce qui peut entraîner des effets indésirables pour les objets qui se chevauchent. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée ne sera pas découpé en différentes pages HTML, mais sera placé dans un seul grand fichier HTML résultant. Cependant, chaque page PDF source sera représentée par sa propre zone rectangulaire dans le HTML (si nécessaire, ces zones peuvent être bordées pour afficher les bords du papier de la page avec l'attribut spécial 'PageBorderIfAny'). Ce paramètre définit la largeur de la marge qui sera forcée autour de ces zones HTML de sortie représentant les pages du document PDF source. En essence, il définit l'intervalle garanti entre les représentations HTML des pages \"papier\" du PDF dans ce mode de conversion. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | Ce paramètre définit les mesures d'anticrénelage requises lors de la conversion d'images d'arrière-plan composées du PDF vers le HTML. |
| [setBatchSize](#setBatchSize-int-) | Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Définit le drapeau qui indique si les graphiques SVG trouvés (le cas échéant) seront compressés (zippés) au format SVGZ lors de l'enregistrement Valeur : Le {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | Si l’attribut ConvertMarkedContentToLayers est défini sur true, alors tous les éléments à l’intérieur d’un contenu marqué PDF (couche) seront placés dans une div HTML avec l’attribut \"data-pdflayer\" spécifiant le nom de la couche. Ce nom de couche sera extrait des propriétés optionnelles du contenu marqué PDF. Si cet attribut est false (par défaut), aucune couche ne sera créée à partir du contenu marqué PDF. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | Lorsque le convertisseur PDFtoHTML génère les CSS résultants, les noms de classes CSS (par exemple \".stl_01 {}\" ... \".stl_NN {}\") sont générés et utilisés dans le CSS final. Cette propriété permet de définir de force un préfixe pour les noms de classes. Par exemple, si vous souhaitez que tous les noms de classes commencent par 'my_prefix_' (c’est‑à‑dire quelque chose comme 'my_prefix_1' ... 'my_prefix_NNN'), il suffit d’attribuer 'my_prefix_' à cette propriété avant la conversion. Si cette propriété reste inchangée (c’est‑à‑dire que la valeur null est laissée), le convertisseur générera lui‑même les noms de classes (ce sera quelque chose comme \".stl_01 {}\" ... \".stl_NN {}\"). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si elle est présente) lors de la conversion de PDF en HTML pour la gestion de l'enregistrement des CSS liés au document HTML créé dans son ensemble ou à ses pages (si plusieurs pages HTML sont générées). Si vous souhaitez gérer le fichier CSS d'une manière spécifique, veuillez simplement créer la méthode appropriée et affecter le délégué créé à partir de celle‑ci à cette propriété. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une page HTML (pour être précis - balisage HTML, sans fichiers liés externes le cas échéant) qui a été créée lors de la conversion. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) pendant la conversion pour la gestion personnalisée des fichiers de ressources référencés créés (comme les images et les polices) liés aux nœuds du HTML enregistré. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Ce champ peut contenir une méthode personnalisée qui renvoie l'URL (ou le modèle d'URL si la génération multipage est activée - voir les détails ci-dessous) du CSS concerné tel qu'il doit être inséré dans le HTML généré. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Spécifie le nom d'une police installée qui est utilisée pour remplacer toute police du document qui n'est pas incorporée et qui n'est pas installée dans le système. Si null, la police de substitution par défaut est utilisée. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | Définit le {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | Liste des noms de polices PDF incorporées qui ne seront pas incorporées dans le HTML. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent avoir des numéros à base 1. C’est‑à‑dire que les numéros valides de pages doivent être pris dans la plage (1...[NumberOfPagesInConvertedDocument]). L’ordre d’apparition des pages dans cette liste n’affecte pas leur ordre dans la ou les pages HTML résultantes — dans les pages résultantes, elles seront toujours présentées dans l’ordre où elles se trouvent dans le PDF source. Si cette liste est nulle (comme c’est le cas par défaut), toutes les pages seront converties. Si un numéro de page de cette liste dépasse la plage des pages présentes (1-[amountOfPagesInDocument]), une exception sera levée. |
| [setFixedLayout](#setFixedLayout-boolean-) | Définit une valeur indiquant si ce HTML est créé en mise en page fixe. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | Cet attribut spécifie le texte de paragraphe en pleine largeur pour le mode Flux, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Définit une règle spéciale d’encodage pour ajuster le décodage PDF du document actuel |
| [setFontSavingMode](#setFontSavingMode-int-) | Définit le mode d’enregistrement des polices qui sera utilisé lors de l’enregistrement du PDF au format souhaité |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | Parfois, des exigences spécifiques concernant la génération du balisage HTML sont présentes. Ce paramètre définit les modes de préparation HTML qui peuvent être utilisés lors de la conversion de PDF en HTML pour répondre à ces exigences spécifiques. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false par défaut |
| [setImageResolution](#setImageResolution-int-) | Obtient ou définit la résolution pour le rendu des images. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Définit le mode de positionnement des lettres dans les mots dans le HTML résultant |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | Cet attribut définit la largeur minimale d’une ligne de tracé graphique. Si l’épaisseur de la ligne est inférieure à 1 px, Adobe Acrobat l’arrondit à cette valeur. Ainsi, cet attribut peut être utilisé pour émuler ce comportement dans les navigateurs HTML. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Cet attribut représente l'ensemble des paramètres utilisés pour dessiner une bordure (le cas échéant) dans le document HTML résultant autour de la zone qui représente la page PDF source. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Cet attribut représente un ensemble de marges de page supplémentaires (le cas échéant) dans le document HTML résultant autour de la zone qui représente la page PDF source. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée sera placé dans un seul grand fichier HTML de résultat. Ce drapeau définit si le HTML de résultat sera généré de manière à ce que le flux des zones représentant les pages PDF dans le HTML de résultat dépende de la résolution d'écran du visualiseur. Supposons que la largeur de l'écran du visualiseur soit suffisante pour placer 2 ou plus de pages côte à côte en direction horizontale. Si ce drapeau est réglé sur true, alors cette opportunité sera utilisée (autant de pages seront affichées en direction horizontale les unes à côté des autres autant que possible, puis le groupe horizontal suivant de pages sera affiché sous le premier). Sinon, les pages s'écouleront de la manière suivante : la page suivante se place toujours sous la précédente. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | Il définit si les fichiers référencés (HTML, polices, images, CSS) seront incorporés dans le fichier HTML principal ou seront générés comme des entités binaires séparées |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | Cet attribut active le mode où les glyphes de texte ne seront pas regroupés en mots et chaînes. Ce mode permet de conserver une précision maximale lors du positionnement des glyphes sur la page et peut être utilisé pour la conversion de documents contenant des notes de musique ou des glyphes qui doivent être placés séparément les uns des autres. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | Le PDF converti peut contenir des images raster. Ce paramètre définit comment elles doivent être traitées lors de la conversion du PDF en HTML |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Définit si, dans le HTML créé, les zones vides en haut et en bas sans aucun contenu (le cas échéant) seront supprimées. |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | Si l'attribut RenderTextAsImage est réglé sur true, le texte de la source devient une image dans le HTML. Cela peut être utile pour rendre le texte non sélectionnable ou si le texte HTML n'est pas rendu correctement. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Indique que la police complète sera enregistrée, ne prend en charge que les polices True Type. Par défaut, SaveFullFont = false et le convertisseur enregistre le sous-ensemble de la police initiale nécessaire pour afficher le texte du document. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Le PDF peut contenir des textes qui sont ombragés par d'autres éléments (par ex. par des images) mais qui peuvent être sélectionnés dans le presse‑papier dans Acrobat Reader (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML de résultat afin d'imiter le comportement d'Acrobat Reader (sinon ces textes sont généralement enregistrés comme cachés, non disponibles pour la copie). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Le PDF peut contenir des textes transparents qui peuvent être sélectionnés dans le presse‑papier (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML de résultat. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | Cet attribut spécifie un regroupement séquentiel des glyphes et des mots en chaînes. Par exemple, les balises et les mots ont un ordre différent dans le HTML converti et vous souhaitez qu'ils correspondent. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Obtient ou définit le chemin du répertoire où toutes les images doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers image (le cas échéant) seront enregistrés avec les autres fichiers liés au HTML. Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Obtient ou définit le chemin du répertoire où seules les images SVG doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers SVG (le cas échéant) seront enregistrés avec les autres fichiers image (près du fichier de sortie) ou dans un dossier spécial pour les images (s’il est spécifié dans l’option SpecialImagesFolderIfAny). Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | Lorsque le mode multipage est sélectionné (c’est‑à‑dire que 'SplitIntoPages' est 'true'), cet attribut définit s'il faut créer un fichier CSS séparé pour chaque page HTML de résultat. Par défaut, cet attribut est false, ainsi un seul grand CSS commun est créé pour toutes les pages générées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement bien supérieure à la taille d'un seul grand fichier CSS, car dans le premier cas les classes CSS sont dupliquées dans plusieurs fichiers CSS pour chaque page. Ainsi, ce paramètre est préférable à n’utiliser que lorsque vous êtes intéressé par le traitement futur de chaque page HTML de manière indépendante, et que la taille du CSS de chaque page séparée est le problème le plus critique. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Définit le drapeau qui indique si chaque page du document source sera convertie en son propre document HTML cible, c’est‑à‑dire si le HTML résultant sera divisé en plusieurs pages HTML. |
| [setTitle](#setTitle-java.lang.String-) | Obtient ou définit le titre de la page HTML. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | Le PDF lui‑même ne contient pas de marqueurs de soulignement pour les textes. Il les émule avec une ligne placée sous le texte. Cette option permet au convertisseur d'essayer de deviner qu'une ligne est le soulignement d'un texte et d'insérer cette information dans le CSS au lieu de dessiner le soulignement graphiquement. |
| [setUseZOrder](#setUseZOrder-boolean-) | Si l'attribut UseZORder est réglé sur true, les graphiques et le texte sont ajoutés au document HTML résultant conformément à l'ordre Z du document PDF original. Si cet attribut est false, tous les graphiques sont placés en une seule couche, ce qui peut entraîner des effets indésirables pour les objets qui se chevauchent. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

Initialise une nouvelle instance de la classe HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

Initialise une nouvelle instance de la classe {@code HtmlSaveOptions}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fixedLayout |  | valeur booléenne |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
Initialise une nouvelle instance de la classe HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
Initialise une nouvelle instance de la classe HtmlSaveOptions.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée ne sera pas découpé en différentes pages HTML, mais sera placé dans un seul grand fichier HTML résultant. Cependant, chaque page PDF source sera représentée par sa propre zone rectangulaire dans le HTML (si nécessaire, ces zones peuvent être bordées pour afficher les bords du papier de la page avec l'attribut spécial 'PageBorderIfAny'). Ce paramètre définit la largeur de la marge qui sera forcée autour de ces zones HTML de sortie représentant les pages du document PDF source. En essence, il définit l'intervalle garanti entre les représentations HTML des pages \"papier\" du PDF dans ce mode de conversion.

**Returns:**
valeur int @deprecated AdditionalMarginWidthInPoints est obsolète, veuillez utiliser PageMarginIfAny à la place.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

Ce paramètre définit les mesures d'anticrénelage requises lors de la conversion d'images d'arrière-plan composées du PDF vers le HTML.

**Returns:**
Élément AntialiasingProcessingType @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination.

**Returns:**
valeur int

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

Lorsque le convertisseur PDFtoHTML génère les CSS résultants, les noms de classes CSS (par exemple \".stl_01 {}\" ... \".stl_NN {}\") sont générés et utilisés dans le CSS final. Cette propriété permet de définir de force un préfixe pour les noms de classes. Par exemple, si vous souhaitez que tous les noms de classes commencent par 'my_prefix_' (c’est‑à‑dire quelque chose comme 'my_prefix_1' ... 'my_prefix_NNN'), il suffit d’attribuer 'my_prefix_' à cette propriété avant la conversion. Si cette propriété reste inchangée (c’est‑à‑dire que la valeur null est laissée), le convertisseur générera lui‑même les noms de classes (ce sera quelque chose comme \".stl_01 {}\" ... \".stl_NN {}\").

**Returns:**
valeur String

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si elle est présente) lors de la conversion de PDF en HTML pour la gestion de l'enregistrement des CSS liés au document HTML créé dans son ensemble ou à ses pages (si plusieurs pages HTML sont générées). Si vous souhaitez gérer le fichier CSS d'une manière spécifique, veuillez simplement créer la méthode appropriée et affecter le délégué créé à partir de celle‑ci à cette propriété.

**Returns:**
Instance CssSavingStrategy

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une page HTML (plus précisément du balisage HTML, sans fichiers liés externes le cas échéant) qui a été créée pendant la conversion. Dans ce cas, le traitement (comme l'enregistrement du HTML de la page dans un flux ou sur le disque) peut être effectué dans ce code personnalisé. Dans ce cas, toutes les actions nécessaires pour enregistrer la page HTML doivent être réalisées dans le code de la méthode fournie, car l'enregistrement du résultat dans le code du convertisseur ne sera pas utilisé. Si, pour une raison quelconque, le traitement pour tel ou tel cas doit être effectué par le code du convertisseur lui‑même, et non dans le code personnalisé, veuillez définir dans le code personnalisé le drapeau 'CustomProcessingCancelled' de la variable du paramètre 'htmlSavingInfo' : cela signalera au convertisseur que toutes les étapes nécessaires au traitement de cette ressource doivent être effectuées par le convertisseur lui‑même, de la même façon que s'il n'y avait aucun code personnalisé externe pour le traitement.

**Returns:**
Instance HtmlPageMarkupSavingStrategy

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex. il peut servir à afficher une barre de progression ou des messages concernant le nombre actuel de pages traitées, exemple de code du gestionnaire qui affiche la progression dans la console : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
Instance ConversionProgressEventHandler

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si elle est présente) pendant la conversion pour la gestion personnalisée des fichiers de ressources référencés créés (comme les images et les polices) liés aux nœuds du HTML enregistré. Cette stratégie doit traiter les ressources et renvoyer une chaîne qui représente l'URL souhaitée de la ressource enregistrée dans le HTML généré.

**Returns:**
Instance ResourceSavingStrategy

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

Ce champ peut contenir une méthode personnalisée qui renvoie l'URL (ou le modèle d'URL si la génération multipage est activée – voir les détails ci‑dessous) du CSS concerné tel qu'il doit être inséré dans le HTML résultant généré. Par ex., si vous souhaitez que le convertisseur place une URL spécifique à la place du nom de fichier CSS standard dans le CSS généré, vous devez simplement créer et affecter à cette propriété une méthode qui génère l'URL souhaitée. Si le drapeau 'SplitCssIntoPages' est défini, alors cette stratégie personnalisée (le cas échéant) doit renvoyer non pas l'URL exacte du CSS mais plutôt une chaîne modèle qui (après substitution du paramètre par le numéro de page avec la fonction String.Format() du convertisseur) peut être résolue en URL pour le CSS de telle ou telle page. Exemples de chaînes de retour attendues dans ce cas : 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' )

**Returns:**
Instance CssUrlMakingStrategy

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Spécifie le nom d'une police installée qui est utilisée pour remplacer toute police du document qui n'est pas incorporée et qui n'est pas installée dans le système. Si null, la police de substitution par défaut est utilisée.

**Returns:**
Valeur String : nom de la police

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Obtient le {@code HtmlDocumentTypeInternal}.

**Returns:**
Le {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

Liste des noms de polices PDF incorporées qui ne seront pas incorporées dans le HTML.

**Returns:**
tableau d'éléments String

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent avoir des numéros à base 1. C’est‑à‑dire que les numéros valides de pages doivent être pris dans la plage (1...[NumberOfPagesInConvertedDocument]). L’ordre d’apparition des pages dans cette liste n’affecte pas leur ordre dans la ou les pages HTML résultantes — dans les pages résultantes, elles seront toujours présentées dans l’ordre où elles se trouvent dans le PDF source. Si cette liste est nulle (comme c’est le cas par défaut), toutes les pages seront converties. Si un numéro de page de cette liste dépasse la plage des pages présentes (1-[amountOfPagesInDocument]), une exception sera levée.

**Returns:**
tableau d'int

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

Cet attribut spécifie le texte de paragraphe en pleine largeur pour le mode Flux, FixedLayout = false

**Returns:**
valeur booléenne

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Définit une règle spéciale d’encodage pour ajuster le décodage PDF du document actuel

**Returns:**
Élément FontEncodingRules @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

Définit le mode d’enregistrement des polices qui sera utilisé lors de l’enregistrement du PDF au format souhaité

**Returns:**
Élément FontSavingModes @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Sources de polices pré‑enregistrées. </p>

**Returns:**
Objet FontSourceCollection <hr> <p> Les polices peuvent être enregistrées préalablement à des fins de cache, puis transmises au processus de conversion Html. Par exemple, cela peut être utile dans un scénario de division de document et de traitement des pages du document dans plusieurs threads avec un seul ensemble de polices. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

Parfois, des exigences spécifiques concernant la génération du balisage HTML sont présentes. Ce paramètre définit les modes de préparation HTML qui peuvent être utilisés lors de la conversion de PDF en HTML pour répondre à ces exigences spécifiques.

**Returns:**
Élément HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Obtient ou définit la résolution pour le rendu des images.

**Returns:**
Valeur: Resolution

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Définit le mode de positionnement des lettres dans les mots dans le HTML résultant

**Returns:**
Élément LettersPositioningMethods @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

Cet attribut définit la largeur minimale d’une ligne de tracé graphique. Si l’épaisseur de la ligne est inférieure à 1 px, Adobe Acrobat l’arrondit à cette valeur. Ainsi, cet attribut peut être utilisé pour émuler ce comportement dans les navigateurs HTML.

**Returns:**
Valeur flottante

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

Cet attribut représente un ensemble de paramètres utilisés pour dessiner une bordure (le cas échéant) dans le document HTML résultant autour de la zone qui représente la page PDF source. En essence, il concerne l’affichage des bords du papier de la page, et non la bordure de la page référencée dans le PDF lui‑même.

**Returns:**
Instance BorderInfo

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

Cet attribut représente un ensemble de marges de page supplémentaires (le cas échéant) dans le document HTML résultant autour de la zone qui représente la page PDF source.

**Returns:**
Instance MarginInfo

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

Il définit si les fichiers référencés (HTML, polices, images, CSS) seront incorporés dans le fichier HTML principal ou seront générés comme des entités binaires séparées

**Returns:**
Élément PartsEmbeddingModes @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

Le PDF converti peut contenir des images raster. Ce paramètre définit comment elles doivent être traitées lors de la conversion du PDF en HTML

**Returns:**
Élément RasterImagesSavingModes @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Obtient ou définit le chemin du répertoire où toutes les images doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers image (le cas échéant) seront enregistrés avec les autres fichiers liés au HTML. Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné.

**Returns:**
valeur String

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Obtient ou définit le chemin du répertoire où seules les images SVG doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers SVG (le cas échéant) seront enregistrés avec les autres fichiers image (près du fichier de sortie) ou dans un dossier spécial pour les images (s’il est spécifié dans l’option SpecialImagesFolderIfAny). Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné.

**Returns:**
valeur String

### getTitle {#getTitle--}
```
public final String getTitle()
```

Obtient ou définit le titre de la page HTML.

**Returns:**
valeur String

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Obtient le drapeau indiquant si les graphiques SVG trouvés (le cas échéant) seront compressés (zippés) au format SVGZ lors de l’enregistrement. Valeur : {@code HtmlDocumentType}.

**Returns:**
valeur booléenne

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

Si l’attribut ConvertMarkedContentToLayers est défini sur true, alors tous les éléments à l’intérieur d’un contenu marqué PDF (couche) seront placés dans une div HTML avec l’attribut \"data-pdflayer\" spécifiant le nom de la couche. Ce nom de couche sera extrait des propriétés optionnelles du contenu marqué PDF. Si cet attribut est false (par défaut), aucune couche ne sera créée à partir du contenu marqué PDF.

**Returns:**
valeur booléenne

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

Obtient une valeur indiquant si le HTML est créé en mise en page fixe.

**Returns:**
valeur: {@code true} si [fixed layout] ; sinon, {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false par défaut

**Returns:**
valeur booléenne

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée sera placé dans un seul grand fichier HTML de résultat. Ce drapeau définit si le HTML de résultat sera généré de manière à ce que le flux des zones représentant les pages PDF dans le HTML de résultat dépende de la résolution d'écran du visualiseur. Supposons que la largeur de l'écran du visualiseur soit suffisante pour placer 2 ou plus de pages côte à côte en direction horizontale. Si ce drapeau est réglé sur true, alors cette opportunité sera utilisée (autant de pages seront affichées en direction horizontale les unes à côté des autres autant que possible, puis le groupe horizontal suivant de pages sera affiché sous le premier). Sinon, les pages s'écouleront de la manière suivante : la page suivante se place toujours sous la précédente.

**Returns:**
valeur booléenne

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

Cet attribut active le mode où les glyphes de texte ne seront pas regroupés en mots et chaînes. Ce mode permet de conserver une précision maximale lors du positionnement des glyphes sur la page et peut être utilisé pour la conversion de documents contenant des notes de musique ou des glyphes qui doivent être placés séparément les uns des autres. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true.

**Returns:**
valeur booléenne

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Définit si, dans le HTML créé, les zones vides en haut et en bas sans aucun contenu (le cas échéant) seront supprimées.

**Returns:**
valeur booléenne

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

Si l'attribut RenderTextAsImage est réglé sur true, le texte de la source devient une image dans le HTML. Cela peut être utile pour rendre le texte non sélectionnable ou si le texte HTML n'est pas rendu correctement.

**Returns:**
valeur booléenne

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Indique que la police complète sera enregistrée, ne prend en charge que les polices True Type. Par défaut, SaveFullFont = false et le convertisseur enregistre le sous-ensemble de la police initiale nécessaire pour afficher le texte du document.

**Returns:**
valeur booléenne

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

Le PDF peut contenir des textes qui sont ombragés par d'autres éléments (par ex. par des images) mais qui peuvent être sélectionnés dans le presse‑papier dans Acrobat Reader (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML de résultat afin d'imiter le comportement d'Acrobat Reader (sinon ces textes sont généralement enregistrés comme cachés, non disponibles pour la copie).

**Returns:**
valeur booléenne

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Le PDF peut contenir des textes transparents qui peuvent être sélectionnés dans le presse‑papier (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML de résultat.

**Returns:**
valeur booléenne

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

Cet attribut spécifie un regroupement séquentiel des glyphes et des mots en chaînes. Par exemple, les balises et les mots ont un ordre différent dans le HTML converti et vous souhaitez qu'ils correspondent. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true.

**Returns:**
valeur booléenne

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

Lorsque le mode multipage est sélectionné (c’est‑à‑dire que 'SplitIntoPages' est 'true'), cet attribut définit s'il faut créer un fichier CSS séparé pour chaque page HTML de résultat. Par défaut, cet attribut est false, ainsi un seul grand CSS commun est créé pour toutes les pages générées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement bien supérieure à la taille d'un seul grand fichier CSS, car dans le premier cas les classes CSS sont dupliquées dans plusieurs fichiers CSS pour chaque page. Ainsi, ce paramètre est préférable à n’utiliser que lorsque vous êtes intéressé par le traitement futur de chaque page HTML de manière indépendante, et que la taille du CSS de chaque page séparée est le problème le plus critique.

**Returns:**
valeur booléenne

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Obtient le drapeau qui indique si chaque page du document source sera convertie en son propre document HTML cible, c’est‑à‑dire si le HTML de résultat sera découpé en plusieurs pages HTML.

**Returns:**
valeur booléenne

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

Le PDF lui‑même ne contient pas de marqueurs de soulignement pour les textes. Il les émule avec une ligne placée sous le texte. Cette option permet au convertisseur d'essayer de deviner qu'une ligne est le soulignement d'un texte et d'insérer cette information dans le CSS au lieu de dessiner le soulignement graphiquement.

**Returns:**
valeur booléenne

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

Si l'attribut UseZORder est réglé sur true, les graphiques et le texte sont ajoutés au document HTML résultant conformément à l'ordre Z du document PDF original. Si cet attribut est false, tous les graphiques sont placés en une seule couche, ce qui peut entraîner des effets indésirables pour les objets qui se chevauchent.

**Returns:**
valeur booléenne

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée ne sera pas découpé en différentes pages HTML, mais sera placé dans un seul grand fichier HTML résultant. Cependant, chaque page PDF source sera représentée par sa propre zone rectangulaire dans le HTML (si nécessaire, ces zones peuvent être bordées pour afficher les bords du papier de la page avec l'attribut spécial 'PageBorderIfAny'). Ce paramètre définit la largeur de la marge qui sera forcée autour de ces zones HTML de sortie représentant les pages du document PDF source. En essence, il définit l'intervalle garanti entre les représentations HTML des pages \"papier\" du PDF dans ce mode de conversion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int @deprecated AdditionalMarginWidthInPoints est obsolète, veuillez utiliser PageMarginIfAny à la place. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

Ce paramètre définit les mesures d'anticrénelage requises lors de la conversion d'images d'arrière-plan composées du PDF vers le HTML.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| antialiasingProcessing |  | Élément AntialiasingProcessingType @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Définit la taille du lot si la conversion par lots est applicable à la paire de formats source et destination.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Définit le drapeau qui indique si les graphiques SVG trouvés (le cas échéant) seront compressés (zippés) au format SVGZ lors de l'enregistrement Valeur : Le {@code HtmlDocumentType}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

Si l’attribut ConvertMarkedContentToLayers est défini sur true, alors tous les éléments à l’intérieur d’un contenu marqué PDF (couche) seront placés dans une div HTML avec l’attribut \"data-pdflayer\" spécifiant le nom de la couche. Ce nom de couche sera extrait des propriétés optionnelles du contenu marqué PDF. Si cet attribut est false (par défaut), aucune couche ne sera créée à partir du contenu marqué PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
Lorsque le convertisseur PDFtoHTML génère les CSS résultants, les noms de classes CSS (par exemple \".stl_01 {}\" ... \".stl_NN {}\") sont générés et utilisés dans le CSS final. Cette propriété permet de définir de force un préfixe pour les noms de classes. Par exemple, si vous souhaitez que tous les noms de classes commencent par 'my_prefix_' (c’est‑à‑dire quelque chose comme 'my_prefix_1' ... 'my_prefix_NNN'), il suffit d’attribuer 'my_prefix_' à cette propriété avant la conversion. Si cette propriété reste inchangée (c’est‑à‑dire que la valeur null est laissée), le convertisseur générera lui‑même les noms de classes (ce sera quelque chose comme \".stl_01 {}\" ... \".stl_NN {}\").

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si elle est présente) lors de la conversion de PDF en HTML pour la gestion de l'enregistrement des CSS liés au document HTML créé dans son ensemble ou à ses pages (si plusieurs pages HTML sont générées). Si vous souhaitez gérer le fichier CSS d'une manière spécifique, veuillez simplement créer la méthode appropriée et affecter le délégué créé à partir de celle‑ci à cette propriété.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
Le résultat de la conversion peut contenir une ou plusieurs pages HTML. Vous pouvez affecter à cette propriété un délégué créé à partir d'une méthode personnalisée qui implémente le traitement d'une page HTML (pour être précis - balisage HTML, sans fichiers liés externes le cas échéant) qui a été créée lors de la conversion.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Ce gestionnaire peut être utilisé pour gérer les événements de progression de la conversion, par ex.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
Ce champ peut contenir la stratégie d'enregistrement qui doit être utilisée (si présente) pendant la conversion pour la gestion personnalisée des fichiers de ressources référencés créés (comme les images et les polices) liés aux nœuds du HTML enregistré.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
Ce champ peut contenir une méthode personnalisée qui renvoie l'URL (ou le modèle d'URL si la génération multipage est activée - voir les détails ci-dessous) du CSS concerné tel qu'il doit être inséré dans le HTML généré.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Spécifie le nom d'une police installée qui est utilisée pour remplacer toute police du document qui n'est pas incorporée et qui n'est pas installée dans le système. Si null, la police de substitution par défaut est utilisée.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
Définit le {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
Liste des noms de polices PDF incorporées qui ne seront pas incorporées dans le HTML.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

Avec cette propriété, vous pouvez définir explicitement quelles pages du document doivent être converties. Les pages de cette liste doivent avoir des numéros à base 1. C’est‑à‑dire que les numéros valides de pages doivent être pris dans la plage (1...[NumberOfPagesInConvertedDocument]). L’ordre d’apparition des pages dans cette liste n’affecte pas leur ordre dans la ou les pages HTML résultantes — dans les pages résultantes, elles seront toujours présentées dans l’ordre où elles se trouvent dans le PDF source. Si cette liste est nulle (comme c’est le cas par défaut), toutes les pages seront converties. Si un numéro de page de cette liste dépasse la plage des pages présentes (1-[amountOfPagesInDocument]), une exception sera levée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

Définit une valeur indiquant si ce HTML est créé en mise en page fixe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | : {@code true} si [fixed layout] ; sinon, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

Cet attribut spécifie le texte de paragraphe en pleine largeur pour le mode Flux, FixedLayout = false

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Définit une règle spéciale d’encodage pour ajuster le décodage PDF du document actuel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontEncodingStrategy |  | Élément FontEncodingRules @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

Définit le mode d’enregistrement des polices qui sera utilisé lors de l’enregistrement du PDF au format souhaité

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fontSavingMode |  | Élément FontSavingModes @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

Parfois, des exigences spécifiques concernant la génération du balisage HTML sont présentes. Ce paramètre définit les modes de préparation HTML qui peuvent être utilisés lors de la conversion de PDF en HTML pour répondre à ces exigences spécifiques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | Élément HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtient ou définit l’indication selon laquelle les erreurs liées à l’absence de police seront ignorées. true - signifie que les erreurs d’absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false par défaut

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Obtient ou définit la résolution pour le rendu des images.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur: Resolution |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Définit le mode de positionnement des lettres dans les mots dans le HTML résultant

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

Cet attribut définit la largeur minimale d’une ligne de tracé graphique. Si l’épaisseur de la ligne est inférieure à 1 px, Adobe Acrobat l’arrondit à cette valeur. Ainsi, cet attribut peut être utilisé pour émuler ce comportement dans les navigateurs HTML.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
Cet attribut représente l'ensemble des paramètres utilisés pour dessiner une bordure (le cas échéant) dans le document HTML résultant autour de la zone qui représente la page PDF source.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
Cet attribut représente un ensemble de marges de page supplémentaires (le cas échéant) dans le document HTML résultant autour de la zone qui représente la page PDF source.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

Si l'attribut 'SplitOnPages=false', alors tout le HTML représentant toutes les pages PDF d'entrée sera placé dans un seul grand fichier HTML de résultat. Ce drapeau définit si le HTML de résultat sera généré de manière à ce que le flux des zones représentant les pages PDF dans le HTML de résultat dépende de la résolution d'écran du visualiseur. Supposons que la largeur de l'écran du visualiseur soit suffisante pour placer 2 ou plus de pages côte à côte en direction horizontale. Si ce drapeau est réglé sur true, alors cette opportunité sera utilisée (autant de pages seront affichées en direction horizontale les unes à côté des autres autant que possible, puis le groupe horizontal suivant de pages sera affiché sous le premier). Sinon, les pages s'écouleront de la manière suivante : la page suivante se place toujours sous la précédente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | valeur booléenne |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

Il définit si les fichiers référencés (HTML, polices, images, CSS) seront incorporés dans le fichier HTML principal ou seront générés comme des entités binaires séparées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| partsEmbeddingMode |  | Élément PartsEmbeddingModes @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

Cet attribut active le mode où les glyphes de texte ne seront pas regroupés en mots et chaînes. Ce mode permet de conserver une précision maximale lors du positionnement des glyphes sur la page et peut être utilisé pour la conversion de documents contenant des notes de musique ou des glyphes qui doivent être placés séparément les uns des autres. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

Le PDF converti peut contenir des images raster. Ce paramètre définit comment elles doivent être traitées lors de la conversion du PDF en HTML

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImagesSavingMode |  | Élément RasterImagesSavingModes @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Définit si, dans le HTML créé, les zones vides en haut et en bas sans aucun contenu (le cas échéant) seront supprimées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | valeur booléenne |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

Si l'attribut RenderTextAsImage est réglé sur true, le texte de la source devient une image dans le HTML. Cela peut être utile pour rendre le texte non sélectionnable ou si le texte HTML n'est pas rendu correctement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Indique que la police complète sera enregistrée, ne prend en charge que les polices True Type. Par défaut, SaveFullFont = false et le convertisseur enregistre le sous-ensemble de la police initiale nécessaire pour afficher le texte du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

Le PDF peut contenir des textes qui sont ombragés par d'autres éléments (par ex. par des images) mais qui peuvent être sélectionnés dans le presse‑papier dans Acrobat Reader (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML de résultat afin d'imiter le comportement d'Acrobat Reader (sinon ces textes sont généralement enregistrés comme cachés, non disponibles pour la copie).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | valeur booléenne |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Le PDF peut contenir des textes transparents qui peuvent être sélectionnés dans le presse‑papier (cela se produit généralement lorsque le document contient des images et des textes OCRisés extraits). Ce paramètre indique au convertisseur s'il faut enregistrer ces textes comme des textes transparents sélectionnables dans le HTML de résultat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| saveTransparentTexts |  | valeur booléenne |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

Cet attribut spécifie un regroupement séquentiel des glyphes et des mots en chaînes. Par exemple, les balises et les mots ont un ordre différent dans le HTML converti et vous souhaitez qu'ils correspondent. Ce paramètre ne sera appliqué au document que lorsque la valeur de l'attribut FixedLayout est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Obtient ou définit le chemin du répertoire où toutes les images doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers image (le cas échéant) seront enregistrés avec les autres fichiers liés au HTML. Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Obtient ou définit le chemin du répertoire où seules les images SVG doivent être enregistrées si elles sont rencontrées lors de l’enregistrement du document au format HTML. Si le paramètre est vide ou nul, les fichiers SVG (le cas échéant) seront enregistrés avec les autres fichiers image (près du fichier de sortie) ou dans un dossier spécial pour les images (s’il est spécifié dans l’option SpecialImagesFolderIfAny). Cela n’affecte rien si la propriété CustomImageSavingStrategy a été utilisée avec succès pour traiter le fichier image concerné.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

Lorsque le mode multipage est sélectionné (c’est‑à‑dire que 'SplitIntoPages' est 'true'), cet attribut définit s'il faut créer un fichier CSS séparé pour chaque page HTML de résultat. Par défaut, cet attribut est false, ainsi un seul grand CSS commun est créé pour toutes les pages générées. La taille totale de tous les CSS générés dans ce mode (un CSS par page) est généralement bien supérieure à la taille d'un seul grand fichier CSS, car dans le premier cas les classes CSS sont dupliquées dans plusieurs fichiers CSS pour chaque page. Ainsi, ce paramètre est préférable à n’utiliser que lorsque vous êtes intéressé par le traitement futur de chaque page HTML de manière indépendante, et que la taille du CSS de chaque page séparée est le problème le plus critique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Définit le drapeau qui indique si chaque page du document source sera convertie en son propre document HTML cible, c’est‑à‑dire si le HTML résultant sera divisé en plusieurs pages HTML.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTitle {#setTitle-java.lang.String-}
Obtient ou définit le titre de la page HTML.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

Le PDF lui‑même ne contient pas de marqueurs de soulignement pour les textes. Il les émule avec une ligne placée sous le texte. Cette option permet au convertisseur d'essayer de deviner qu'une ligne est le soulignement d'un texte et d'insérer cette information dans le CSS au lieu de dessiner le soulignement graphiquement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | valeur booléenne |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

Si l'attribut UseZORder est réglé sur true, les graphiques et le texte sont ajoutés au document HTML résultant conformément à l'ordre Z du document PDF original. Si cet attribut est false, tous les graphiques sont placés en une seule couche, ce qui peut entraîner des effets indésirables pour les objets qui se chevauchent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
