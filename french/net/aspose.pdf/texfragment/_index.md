---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.TeXFragment. Représente un fragment TeX
type: docs
weight: 10360
url: /fr/net/aspose.pdf/texfragment/
---
## Classe TeXFragment

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
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. Par défaut, c'est faux. (pour la génération de pdf) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Obtient ou définit les options de chargement TeX qui seront utilisées pour le chargement (et le rendu) de LaTeX dans cette instance de classe. Veuillez l'utiliser lorsqu'il est nécessaire d'utiliser un paramètre spécifique pour l'importation de LaTeX pour cette instance (par exemple, lorsque cette instance doit utiliser un BasePath spécifique pour le LaTeX importé ou doit utiliser un chargeur spécifique de ressources externes). Si le paramètre est par défaut (null), alors les options de chargement standard de LaTeX seront utilisées. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. Le ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte sur la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Clone le fragment. |

### Voir aussi

* classe [FormattedFragment](../formattedfragment/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)