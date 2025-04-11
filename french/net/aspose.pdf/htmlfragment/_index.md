---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlFragment. Représente un fragment html
type: docs
weight: 5520
url: /fr/net/aspose.pdf/htmlfragment/
---
## Classe HtmlFragment

Représente un fragment html.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | Initialise une nouvelle instance de la classe HtmlFragment. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Obtient ou définit les HtmlLoadOptions qui seront utilisées pour charger (et rendre) le HTML dans cette instance de classe. Veuillez l'utiliser lorsqu'il est nécessaire d'utiliser un paramètre spécifique pour l'importation de HTML pour cette instance ou celle-ci (par exemple, lorsque cette instance doit utiliser un BasePath spécifique pour le HTML importé ou doit utiliser un chargeur spécifique de ressources externes). Si le paramètre est par défaut (null), alors les options de chargement HTML standard seront utilisées. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit l'hyperlien du fragment (pour le générateur pdf). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Obtient ou définit la rupture des mots |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. Par défaut, c'est faux. (pour la génération pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. Par défaut, c'est faux. (pour la génération pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. Par défaut, c'est faux. (pour la génération pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. Par défaut, c'est faux. (pour la génération pdf) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Obtient ou définit si le paragraphe a une marge par défaut sinon la marge est 0 |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération pdf) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Obtient le rectangle du HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Obtient ou définit la police |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte dans la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Clone le fragment html. |

### Voir aussi

* classe [FormattedFragment](../formattedfragment/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)