---
title: "Classe HtmlFragment"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.HtmlFragment. Représente un fragment HTML"
type: docs
weight: 5650
url: /fr/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

Représente le fragment html.

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
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Obtient ou définit HtmlLoadOptions qui seront utilisés pour le chargement (et le rendu) du HTML dans cette instance de classe. Veuillez l'utiliser lorsqu'il est nécessaire d'utiliser un paramètre spécifique pour l'importation du HTML pour telle ou telle instance (par ex. lorsque cette instance ou cette autre doit utiliser un BasePath spécifique pour le HTML importé ou doit utiliser un chargeur spécifique de ressources externes). Si le paramètre est par défaut (null), alors les options de chargement HTML standard seront utilisées. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur PDF). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Obtient ou définit la coupure des mots |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Obtient ou définit si le paragraphe a une marge par défaut, sinon la marge est 0. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | Obtient le rectangle du HtmlFragment |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Obtient ou définit la police |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Clone le fragment HTML. |

### Voir aussi

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


