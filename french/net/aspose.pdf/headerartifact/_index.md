---
title: Class HeaderArtifact
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HeaderArtifact. La classe décrit l'artéfact d'en-tête. Cet artéfact peut être utilisé pour définir le titre de la page
type: docs
weight: 5420
url: /fr/net/aspose.pdf/headerartifact/
---
## Classe HeaderArtifact

La classe décrit l'artéfact d'en-tête. Cet artéfact peut être utilisé pour définir le titre de la page.

```csharp
public class HeaderArtifact : Artifact
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [HeaderArtifact](headerartifact/)() | Crée une instance d'artéfact d'en-tête. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Alignement horizontal de l'artéfact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Alignement vertical de l'artéfact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Marge inférieure de l'artéfact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Obtient la collection des opérateurs internes de l'artéfact. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Obtient le nom du sous-type d'artéfact. Peut être utilisé si le sous-type d'artéfact n'est pas un sous-type standard. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Obtient le nom du type d'artéfact. Peut être utilisé si le type d'artéfact est non standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Obtient le XForm de l'artéfact (si XForm est utilisé). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Obtient l'image de l'artéfact (si présente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Si vrai, l'artéfact est placé derrière le contenu de la page. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Marge gauche de l'artéfact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Lignes de l'artéfact de texte multiligne. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Obtient ou définit l'opacité de l'artéfact. Les valeurs possibles sont dans la plage 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Obtient ou définit la position de l'artéfact. Si cette propriété est spécifiée, alors les marges et les alignements sont ignorés. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Obtient le rectangle de l'artéfact. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Marge droite de l'artéfact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Obtient ou définit l'angle de rotation de l'artéfact. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Obtient le sous-type d'artéfact. Si l'artéfact a un sous-type non standard, le nom du sous-type peut être lu via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Obtient le texte de l'artéfact. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | État du texte pour le texte de l'artéfact. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Marge supérieure de l'artéfact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Obtient le type d'artéfact. |

## Méthodes

| Nom | Description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Commence les mises à jour différées. Utilisez cette fonctionnalité si vous devez apporter plusieurs modifications au même artéfact pour améliorer les performances. En général, les opérateurs d'artéfact sont modifiés chaque fois qu'une propriété d'artéfact est modifiée. Cela entraîne un changement du contenu de la page chaque fois que l'artéfact est modifié. Pour éviter cet effet, placez toutes les mises à jour d'artéfact entre les appels StartUpdates/SaveUpdates. Cela permet de modifier le contenu de la page une seule fois. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Dispose de l'artéfact. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Obtient la valeur personnalisée de l'artéfact. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Supprime la valeur personnalisée de l'artéfact. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Enregistre toutes les mises à jour dans l'artéfact qui ont été effectuées après l'appel à BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Définit l'image de l'artéfact. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Définit l'image de l'artéfact. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Définit le texte et les propriétés de texte de l'artéfact. Permet de spécifier plusieurs lignes. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Définit quelle chaîne sera remplacée par le numéro de page. La valeur par défaut est #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Définit la page PDF qui est placée sur la page du document en tant qu'artéfact. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Définit le texte de l'artéfact. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Définit le texte et les propriétés de texte de l'artéfact. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Définit la valeur personnalisée de l'artéfact. |

### Voir aussi

* classe [Artifact](../artifact/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)