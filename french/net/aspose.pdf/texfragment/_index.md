---
title: "Classe TeXFragment"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.TeXFragment. Représente un fragment TeX"
type: docs
weight: 10540
url: /fr/net/aspose.pdf/texfragment/
---
## TeXFragment class

Représente un fragment TeX.

```csharp
public class TeXFragment : FormattedFragment
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | Initialise une nouvelle instance de la classe HtmlFragment. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | Initialise une nouvelle instance de la classe HtmlFragment. |

## Propriétés

| Nom | Description |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Obtient ou définit un alignement horizontal du paragraphe |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur PDF). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false. (pour la génération PDF) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. La valeur par défaut est false. (pour la génération PDF) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. La valeur par défaut est false. (pour la génération PDF) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page avec le paragraphe suivant. La valeur par défaut est false. (pour la génération PDF) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Obtient ou définit TeXLoadOptions qui seront utilisés pour le chargement (et le rendu) du LaTeX dans cette instance de classe. Veuillez l'utiliser lorsqu'il est nécessaire d'appliquer un paramètre spécifique pour l'importation du LaTeX pour telle ou telle instance (par ex. lorsque cette instance ou celle‑ci doit utiliser un BasePath spécifique pour le LaTeX importé ou doit utiliser un chargeur spécifique de ressources externes). Si le paramètre est par défaut (null), les options de chargement LaTeX standard seront utilisées. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur entière qui indique le Z-order du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Clone le fragment. |

### Voir aussi

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


