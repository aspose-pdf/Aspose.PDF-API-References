---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Artifact. La classe représente un objet Artifact PDF
type: docs
weight: 2770
url: /fr/net/aspose.pdf/artifact/
---
## Classe Artifact

La classe représente un objet Artifact PDF.

```csharp
public class Artifact : IDisposable
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | Constructeur d'un artifact avec le type et le sous-type spécifiés |
| [Artifact](artifact/#constructor_1)(string, string) | Constructeur d'un artifact avec le type et le sous-type spécifiés |

## Propriétés

| Nom | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Alignement horizontal de l'artifact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Alignement vertical de l'artifact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Marge inférieure de l'artifact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Obtient la collection des opérateurs internes de l'artifact. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Obtient le nom du sous-type de l'artifact. Peut être utilisé si le sous-type de l'artifact n'est pas un sous-type standard. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Obtient le nom du type de l'artifact. Peut être utilisé si le type de l'artifact est non standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Obtient le XForm de l'artifact (si le XForm est utilisé). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Obtient l'image de l'artifact (si présente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Si vrai, l'artifact est placé derrière le contenu de la page. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Marge gauche de l'artifact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Lignes de l'artifact de texte multiligne. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Obtient ou définit l'opacité de l'artifact. Les valeurs possibles sont dans la plage 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Obtient ou définit la position de l'artifact. Si cette propriété est spécifiée, alors les marges et les alignements sont ignorés. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Obtient le rectangle de l'artifact. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Marge droite de l'artifact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Obtient ou définit l'angle de rotation de l'artifact. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Obtient le sous-type de l'artifact. Si l'artifact a un sous-type non standard, le nom du sous-type peut être lu via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Obtient le texte de l'artifact. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | État du texte pour le texte de l'artifact. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Marge supérieure de l'artifact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Obtient le type de l'artifact. |

## Méthodes

| Nom | Description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Commence les mises à jour différées. Utilisez cette fonctionnalité si vous devez apporter plusieurs modifications au même artifact pour améliorer les performances. En général, les opérateurs d'artifact sont modifiés chaque fois qu'une propriété d'artifact est modifiée. Cela entraîne un changement du contenu de la page chaque fois que l'artifact est modifié. Pour éviter cet effet, placez toutes les mises à jour de l'artifact entre les appels StartUpdates/SaveUpdates. Cela permet de changer le contenu de la page une seule fois. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Dispose de l'artifact. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Obtient la valeur personnalisée de l'artifact. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Supprime la valeur personnalisée de l'artifact. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Enregistre toutes les mises à jour dans l'artifact qui ont été effectuées après l'appel à BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | Définit l'image de l'artifact. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | Définit l'image de l'artifact. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Définit le texte et les propriétés de texte de l'artifact. Permet de spécifier plusieurs lignes. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Définit quelle chaîne sera remplacée par le numéro de page. La valeur par défaut est #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Définit la page PDF qui est placée sur la page du document en tant qu'artifact. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Définit le texte de l'artifact. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Définit le texte et les propriétés de texte de l'artifact. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Définit la valeur personnalisée de l'artifact. |

## Autres Membres

| Nom | Description |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | Énumération des sous-types d'artifacts possibles. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | Énumération des types d'artifacts possibles. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)