---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Page. Classe représentant une page d'un document PDF
type: docs
weight: 8050
url: /fr/net/aspose.pdf/page/
---
## Classe Page

Classe représentant une page d'un document PDF.

```csharp
public sealed class Page : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Obtient la collection des propriétés de la page. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Obtient la collection des annotations de la page. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Obtient ou définit la boîte d'art de la page. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Obtient la collection des artefacts sur la page. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Obtient ou définit la couleur de fond de la page. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Obtient ou définit l'image de fond pour la page (pour le générateur uniquement, non remplie lors de la lecture du document). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Obtient ou définit la boîte de débordement de la page. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Définit le type de couleur des pages en fonction des informations obtenues des opérateurs SetColor, des images et des formulaires. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Obtient la collection des opérateurs dans le flux de contenu de la page. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Obtient ou définit la boîte de rognage de la page. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Obtient ou définit la durée d'affichage de la page. C'est le temps en secondes que la page doit être affichée lors de la présentation. Renvoie -1 si la durée n'est pas définie. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Obtient la liste des objets Field dans l'ordre de tabulation sur cette page. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Obtient ou définit le pied de page. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Obtient ou définit une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparent. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Obtient ou définit l'en-tête de la page. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Obtient ou définit l'ajout de paragraphes après le dernier paragraphe de la page. |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Obtient ou définit la collection de calques. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Obtient ou définit la boîte média de la page. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Obtient ou définit le style de ligne pour les notes. (pour le générateur uniquement, non rempli lors de la lecture du document) |
| [Number](../../aspose.pdf/page/number/) { get; } | Obtient le numéro de la page. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Obtient ou définit les informations de la page (pour le générateur uniquement, non rempli lors de la lecture du document). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Obtient les paragraphes. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Obtient ou définit le rectangle de la page. Pour obtenir : la boîte de rognage de la page est renvoyée si spécifiée, sinon la boîte média de la page est renvoyée. Pour définir : la boîte média de la page est toujours définie. Veuillez noter que cette propriété ne prend pas en compte la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, veuillez utiliser ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Obtient ou définit la rotation de la page. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Obtient la matrice de transformation pour la page. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Obtient ou définit l'ordre de tabulation de la page. Valeurs possibles : Ligne, Colonne. Par défaut, Manuel |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Obtient ou définit les informations de la table des matières. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Obtient ou définit la boîte de coupe de la page. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Obtient ou définit la valeur UserUnit. Un nombre positif donnant la taille des unités d'espace utilisateur par défaut, en multiples de 1 / 72 pouce. La valeur par défaut est 1. Veuillez définir une valeur nulle ou négative afin de supprimer cette entrée dans la page. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Obtient ou définit le filigrane de la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Accepte l'objet visiteur [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) qui fournit des fonctionnalités pour travailler avec les annotations. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Accepte l'objet visiteur [`ImagePlacementAbsorber`](../imageplacementabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de placement d'image. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Accepte l'objet visiteur [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de texte. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Accepte l'objet visiteur [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de texte. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Ajoute des graphiques à la page. Fonctionne plus rapidement que l'ajout d'éléments un par un avec la méthode [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Ajoute une image sur la page et la place au milieu du rectangle spécifié en conservant la proportion de l'image. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Ajoute une image sur la page et la place au milieu du rectangle spécifié en conservant la proportion de l'image. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Ajoute une image recherchable sur la page et la place au milieu du rectangle spécifié en conservant la proportion de l'image. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Ajoute une image sur la page et la place en fonction de la position du rectangle de l'image. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Met un tampon dans la page. Le tampon peut être un numéro de page, une image ou un texte simple, par exemple un logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Convertit la page actuelle en bitmap et renvoie ensuite un tableau d'octets. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Convertit la page actuelle en xml en encodage utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Calcule la valeur bbox - rectangle contenant le contenu sans marges visibles. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Convertit la page en PNG pour le flux d'image DSR, OMR, OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Supprime des graphiques de la page. Fonctionne plus rapidement que la suppression d'éléments un par un avec la méthode [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Libère de la mémoire |
| [Flatten](../../aspose.pdf/page/flatten/)() | Supprime tous les champs situés sur la page et place leurs valeurs à la place. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Efface les données mises en cache |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Renvoie des notifications sur les opérations internes avec le contenu de la page. (Seules les notifications concernant les événements de paragraphe dans les scénarios d'ajout de texte sont prises en charge pour le moment.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Renvoie le rectangle de la page selon sa CropBox (ou MediaBox si CropBox est nul). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Récupère les ressources associées à la page. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Détecte la présence de graphiques vectoriels, s'ils sont présents sur la page. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Obtient le drapeau indiquant si la page est vide ou non. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Convertit la page en niveaux de gris. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Fusionne tous les calques de la page en un seul calque avec le nouveau nom de calque spécifié. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Fusionne tous les calques de la page en un seul calque avec le nouveau nom de calque spécifié et un Id de groupe de contenu optionnel. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Redimensionne la page. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Envoie la page à traiter avec le périphérique de page donné. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Envoie la page à traiter avec le périphérique de page donné. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Définit la taille de la page pour la page. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Essaie de sauvegarder les graphiques vectoriels s'ils sont présents sur la page. Le format de sauvegarde est SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Traduit la valeur entière en membre d'énumération de rotation correspondant. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Traduit le membre d'énumération de rotation en valeur entière. |

## Événements

| Nom | Description |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Événement pour personnaliser l'en-tête et le pied de page. |

## Autres Membres

| Nom | Description |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Procédure pour personnaliser l'en-tête et le pied de page. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)