---
title: "Classe TextSearchOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Text.TextSearchOptions. Représente les options de recherche de texte"
type: docs
weight: 11230
url: /fr/net/aspose.pdf.text/textsearchoptions/
---
## TextSearchOptions class

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
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Obtient ou définit l'indication selon laquelle les erreurs liées à l'absence de police seront ignorées par l'absorbeur de texte (fragment). true - signifie que les erreurs d'absence de police seront ignorées. Les segments de texte faisant référence à des ressources incorrectes seront sautés lors du traitement. false (par défaut) - l'erreur d'absence de police interrompra le traitement en lançant une exception. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Obtient ou définit l'indication selon laquelle les fragments de texte représentant l'ombre du texte normal seront ignorés lors de la recherche. true - signifie que le texte d'ombre ne sera pas trouvé (essayez cela si la recherche de texte renvoie des fragments dupliqués à des positions proches). false - signifie que le texte d'ombre sera trouvé ainsi que le texte normal (valeur par défaut). |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Obtient ou définit l'indication selon laquelle une expression régulière est utilisée. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Obtient ou définit l'indication selon laquelle le texte est recherché à l'intérieur des limites de la page. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Obtient ou définit l'indication selon laquelle les erreurs d'extraction (décodage) du texte seront enregistrées dans l'absorbeur de texte (fragment). true - signifie que les erreurs d'extraction (décodage) du texte seront enregistrées. Cela peut réduire les performances. false (par défaut) - aucune journalisation des erreurs. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Obtient ou définit le rectangle qui encadre le texte recherché. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Obtient ou définit la valeur qui autorise la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) lors de la recherche de texte. true - la recherche de graphiques liés au texte sera effectuée (valeur par défaut). false - les éléments graphiques pouvant être présents dans le document source seront ignorés. Activez cette option en cas de problèmes de performances ou si vous n'avez pas besoin de gérer le soulignement, l'arrière-plan ou le rognage. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Obtient ou définit la valeur qui autorise la recherche de texte dans les Annotations. true - le texte sera recherché dans les Annotations. false - le texte dans les Annotations ne sera pas analysé par TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Obtient ou définit la valeur qui limite la recherche de graphiques liés au texte (soulignement, arrière-plan, etc.) sur une page au nombre spécifié d'éléments. La valeur par défaut est 250. Réduisez la valeur en cas de problèmes de performances, augmentez-la si certains éléments graphiques n'ont pas été trouvés. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Obtient ou définit l'indication selon laquelle le texte sera recherché en utilisant le codage du moteur de police. true - signifie que le codage du moteur de police sera utilisé (essayez cela si la recherche de texte échoue à cause d'un codage imparfait dans le document). false - signifie que le codage de la police du document sera utilisé (valeur par défaut). |

### Voir aussi

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


