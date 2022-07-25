---
title: HeaderArtifact
second_title: Référence de l'API Aspose.PDF pour .NET
description: La classe décrit lartefact Header. Cet artefact peut être utilisé pour définir le titre de la page.
type: docs
weight: 3340
url: /fr/net/aspose.pdf/headerartifact/
---
## HeaderArtifact class

La classe décrit l'artefact Header. Cet artefact peut être utilisé pour définir le titre de la page.

```csharp
public class HeaderArtifact : Artifact
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [HeaderArtifact](headerartifact)() | Crée une instance d'artefact d'en-tête. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment) { get; set; } | Alignement horizontal de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment) { get; set; } | Alignement vertical de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin) { get; set; } | Marge inférieure de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Contents](../../aspose.pdf/artifact/contents) { get; } | Obtient une collection d'opérateurs internes d'artefacts. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype) { get; set; } | Obtient le nom du sous-type d'artefact. Peut être utilisé si le sous-type d'artefact n'est pas un sous-type standard. |
| [CustomType](../../aspose.pdf/artifact/customtype) { get; set; } | Obtient le nom du type d'artefact. Peut être utilisé si le type d'artefact n'est pas standard. |
| [Form](../../aspose.pdf/artifact/form) { get; } | Obtient XForm de l'artefact (si XForm est utilisé). |
| [Image](../../aspose.pdf/artifact/image) { get; } | Obtient l'image de l'artefact (si présent). |
| [IsBackground](../../aspose.pdf/artifact/isbackground) { get; set; } | Si true L'artefact est placé derrière le contenu de la page. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin) { get; set; } | Marge gauche de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Lines](../../aspose.pdf/artifact/lines) { get; } | Lignes d'artefact de texte multiligne. |
| [Opacity](../../aspose.pdf/artifact/opacity) { get; set; } | Obtient ou définit l'opacité de l'artefact. Les valeurs possibles sont dans la plage 0..1. |
| [Position](../../aspose.pdf/artifact/position) { get; set; } | Obtient ou définit la position de l'artefact. Si cette propriété est spécifiée, les marges et les alignements sont ignorés. |
| [Rectangle](../../aspose.pdf/artifact/rectangle) { get; } | Obtient le rectangle de l'artefact. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin) { get; set; } | Marge droite de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Rotation](../../aspose.pdf/artifact/rotation) { get; set; } | Obtient ou définit l'angle de rotation de l'artefact. |
| [Subtype](../../aspose.pdf/artifact/subtype) { get; set; } | Obtient le sous-type d'artefact. Si l'artefact a un sous-type non standard, le nom du sous-type peut être lu via CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text) { get; set; } | Obtient le texte de l'artefact. |
| [TextState](../../aspose.pdf/artifact/textstate) { get; set; } | État du texte pour le texte de l'artefact. |
| [TopMargin](../../aspose.pdf/artifact/topmargin) { get; set; } | Marge supérieure de l'artefact. Si la position est spécifiée explicitement (dans la propriété Position), cette valeur est ignorée. |
| [Type](../../aspose.pdf/artifact/type) { get; set; } | Obtient le type d'artefact. |

## Méthodes

| Nom | La description |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates)() | Démarrer les mises à jour différées. Utilisez cette fonction si vous devez apporter plusieurs modifications au même artefact pour améliorer les performances. Habituellement, les opérateurs d'artefact sont modifiés à tout moment lorsque la propriété d'artefact a été modifiée. Cela entraîne la modification du contenu de la page à chaque fois que l'artefact a été modifié. Pour éviter cet effet, placez toutes les mises à jour d'artefacts entre les appels StartUpdates/SaveUpdates. Cela permet de modifier le contenu de la page une seule fois. |
| [Dispose](../../aspose.pdf/artifact/dispose)() | Débarrassez-vous de l'artefact. |
| [GetValue](../../aspose.pdf/artifact/getvalue)(string) | Obtient la valeur personnalisée de l'artefact. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue)(string) | Supprimer la valeur personnalisée de l'artefact. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates)() | Enregistre toutes les mises à jour dans l'artefact qui ont été effectuées après l'appel de BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage)(Stream) | Définit l'image de l'artefact. |
| [SetImage](../../aspose.pdf/artifact/setimage)(string) | Définit l'image de l'artefact. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate)(string[], TextState) | Définissez le texte et les propriétés de texte de l'artefact. Permet de spécifier plusieurs lignes. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage)(Page) | Définit la page PDF qui est placée sur la page du document en tant qu'artefact. |
| [SetText](../../aspose.pdf/artifact/settext)(FormattedText) | Définit le texte de l'artefact. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate)(string, TextState) | Définissez le texte et les propriétés de texte de l'artefact. |
| [SetValue](../../aspose.pdf/artifact/setvalue)(string, string) | Définit la valeur personnalisée de l'artefact. |

### Voir également

* class [Artifact](../artifact)
* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
