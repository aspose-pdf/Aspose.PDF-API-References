---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextSearchOptions. Représente les options de recherche de texte
type: docs
weight: 11040
url: /fr/net/aspose.pdf.text/textsearchoptions/
---
## Classe TextSearchOptions

Représente les options de recherche de texte

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Initialise une nouvelle instance de l'objet `TextSearchOptions`. Spécifie le mode d'utilisation des expressions régulières. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Initialise une nouvelle instance de l'objet `TextSearchOptions`. Spécifie le rectangle qui délimite le texte recherché. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Initialise une nouvelle instance de l'objet `TextSearchOptions`. Spécifie le rectangle qui délimite le texte recherché et le mode d'utilisation des expressions régulières. |

## Propriétés

| Nom | Description |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Obtient ou définit l'indication que les erreurs liées à l'absence de police seront ignorées par l'absorbeur de texte (fragment). vrai - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte qui se réfèrent à des ressources incorrectes seront ignorés lors du traitement. faux (par défaut) - l'erreur d'absence de police mettra fin au traitement en lançant une exception. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Obtient ou définit l'indication que les fragments de texte représentant l'ombre du texte normal seront ignorés lors de la recherche. vrai - signifie que le texte d'ombre ne sera pas trouvé (essayez cela si la recherche de texte renvoie des fragments dupliqués à des positions proches) faux - signifie que le texte d'ombre sera trouvé ainsi que le texte normal (valeur par défaut) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Obtient ou définit l'indication que l'expression régulière est utilisée. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Obtient ou définit l'indication que le texte est recherché dans les limites de la page. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Obtient ou définit l'indication que les erreurs d'extraction de texte (décodage) seront enregistrées dans l'absorbeur de texte (fragment). vrai - signifie que les erreurs d'extraction de texte (décodage) seront enregistrées. Cela peut diminuer les performances. faux (par défaut) - pas d'enregistrement d'erreurs. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Obtient ou définit le rectangle qui délimite le texte recherché. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Obtient ou définit la valeur qui permet de rechercher des graphiques liés au texte (soulignement, arrière-plan, etc.) lors de la recherche de texte. vrai - la recherche de graphiques liés au texte sera effectuée (valeur par défaut). faux - les éléments graphiques qui peuvent être présents dans le document source seront ignorés. Définissez cela en cas de problèmes de performance ou si vous n'avez pas besoin de gérer le soulignement, l'arrière-plan ou le clipping. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Obtient ou définit la valeur qui permet de rechercher du texte dans les annotations. vrai - le texte sera recherché dans les annotations. faux - le texte dans les annotations ne sera pas analysé par TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Obtient ou définit la valeur qui limite la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) sur une page pour le nombre spécifié d'éléments. La valeur par défaut est 250. Définissez une valeur inférieure en cas de problèmes de performance, essayez une valeur plus grande si certains éléments graphiques n'ont pas été trouvés. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Obtient ou définit l'indication que le texte sera recherché en utilisant l'encodage du moteur de police. vrai - signifie que l'encodage du moteur de police sera utilisé (essayez cela si la recherche de texte échoue en raison d'un encodage imparfait dans le document) faux - signifie que l'encodage de police du document sera utilisé (valeur par défaut) |

### Voir aussi

* classe [TextOptions](../textoptions/)
* espace de noms [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)