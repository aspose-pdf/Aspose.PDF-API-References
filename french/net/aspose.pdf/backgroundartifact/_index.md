---
title: "Classe BackgroundArtifact"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.BackgroundArtifact class. La classe décrit l'artéfact d'arrière-plan. Cet artéfact permet de définir l'arrière‑plan de la page"
type: docs
weight: 2920
url: /fr/net/aspose.pdf/backgroundartifact/
---
## BackgroundArtifact class

Classe décrivant l'artefact d'arrière-plan. Cet artefact permet de définir l'arrière-plan de la Page.

```csharp
public class BackgroundArtifact : Artifact
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BackgroundArtifact](backgroundartifact/)() | Initialise l'objet BackgroundArtifact. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Alignement horizontal de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Alignement vertical de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [BackgroundColor](../../aspose.pdf/backgroundartifact/backgroundcolor/) { get; set; } | Obtient ou définit la couleur d'arrière‑plan de l'artéfact d'arrière‑plan |
| [BackgroundImage](../../aspose.pdf/backgroundartifact/backgroundimage/) { get; set; } | Obtient ou définit l'image d'arrière‑plan de l'artéfact d'arrière‑plan |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Marge inférieure de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Obtient la collection des opérateurs internes de l'artefact. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Obtient le nom du sous‑type d'artefact. Peut être utilisé si le sous‑type d'artefact n'est pas un sous‑type standard. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Obtient le nom du type d'artefact. Peut être utilisé si le type d'artefact n'est pas standard. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Obtient le XForm de l'artefact (si le XForm est utilisé). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Obtient l'image de l'artefact (si présent). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Si vrai, l'artefact est placé derrière le contenu de la page. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Marge gauche de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Lignes de l'artefact texte multiligne. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Obtient ou définit l'opacité de l'artefact. Les valeurs possibles sont dans la plage 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Obtient ou définit la position de l'artefact. Si cette propriété est spécifiée, les marges et les alignements sont ignorés. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Obtient le rectangle de l'artefact. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Marge droite de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Obtient ou définit l'angle de rotation de l'artefact. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Obtient le sous‑type d'artefact. Si l'artefact possède un sous‑type non standard, le nom du sous‑type peut être lu via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Obtient le texte de l'artefact. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | État du texte pour le texte de l'artefact. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Marge supérieure de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Obtient le type de l'artefact. |

## Méthodes

| Nom | Description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Démarrer les mises à jour différées. Utilisez cette fonctionnalité si vous devez effectuer plusieurs modifications du même artefact afin d'améliorer les performances. Généralement, les opérateurs d'artefact sont modifiés chaque fois qu'une propriété d'artefact a été modifiée. Cela entraîne la modification du contenu de la page à chaque modification de l'artefact. Pour éviter cet effet, placez toutes les mises à jour d'artefact entre les appels StartUpdates/SaveUpdates. Cela permet de modifier le contenu de la page une seule fois. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Libérez l'artefact. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Obtient la valeur personnalisée de l'artefact. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Supprime la valeur personnalisée de l'artefact. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Enregistre toutes les mises à jour de l'artefact qui ont été effectuées après l'appel à BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Définit l'image de l'artefact. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Définit l'image de l'artefact. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Définit le texte et les propriétés du texte de l'artefact. Permet de spécifier plusieurs lignes. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Définit la chaîne qui sera remplacée par le numéro de page. La valeur par défaut est #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Définit la page PDF qui est placée sur la page du document en tant qu'artefact. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Définit le texte de l'artefact. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Définit le texte et les propriétés du texte de l'artefact. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Définit la valeur personnalisée de l'artefact. |

### Voir aussi

* class [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


