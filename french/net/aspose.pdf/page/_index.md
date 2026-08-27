---
title: "Class Page"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Page. Classe représentant une page d'un document PDF"
type: docs
weight: 8190
url: /fr/net/aspose.pdf/page/
---
## Page class

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
| [Background](../../aspose.pdf/page/background/) { get; set; } | Obtient ou définit la couleur d'arrière-plan de la page. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Obtient ou définit la boîte de débordement de la page. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Définit le type de couleur des pages en fonction des informations provenant des opérateurs SetColor, des images et des formulaires. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Obtient la collection des opérateurs dans le flux de contenu de la page. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Obtient ou définit la boîte de rognage de la page. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Obtient ou définit la durée d'affichage de la page. Il s'agit du temps en secondes pendant lequel la page doit être affichée pendant la présentation. Retourne -1 si la durée n'est pas définie. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Obtient la liste des objets Field dans l'ordre de tabulation sur cette page. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Obtient ou définit le pied de page. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Obtient ou définit une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page pour une utilisation dans le modèle d'imagerie transparente. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Obtient ou définit l'en-tête de la page. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Obtient ou définit l'ajout de paragraphes après le dernier paragraphe de la page |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Obtient ou définit la collection des calques. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Obtient ou définit la boîte média de la page. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Obtient ou définit le style de ligne pour les notes (pour le générateur uniquement, non rempli lors de la lecture du document) |
| [Number](../../aspose.pdf/page/number/) { get; } | Obtient le numéro de la page. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Obtient ou définit les informations de la page (pour le générateur uniquement, non rempli lors de la lecture du document). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Obtient les paragraphes. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Obtient ou définit le rectangle de la page. Pour l'obtention : la boîte de rognage de la page est renvoyée si spécifiée, sinon la boîte média de la page est renvoyée. Pour la définition : la boîte média de la page est toujours définie. Veuillez noter que cette propriété ne tient pas compte de la rotation de la page. Pour obtenir le rectangle de la page en tenant compte de la rotation, veuillez utiliser ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Obtient ou définit la rotation de la page. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Obtient la matrice de transformation pour la Page. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Obtient ou définit l'ordre d'onglet de la Page. Valeurs possibles : Row, Column. Par défaut, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Obtient ou définit les informations de la table des matières. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Obtient ou définit la trim box de la Page. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Obtient ou définit la valeur UserUnit. Un nombre positif indiquant la taille des unités d'espace utilisateur par défaut, en multiples de 1/72 pouce. La valeur par défaut est 1. Veuillez définir zéro ou une valeur négative afin de supprimer cette entrée dans la Page. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Obtient ou définit le filigrane de la Page. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Accepte l'objet visiteur [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) qui fournit des fonctionnalités pour travailler avec les Annotation. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Accepte l'objet visiteur [`ImagePlacementAbsorber`](../imageplacementabsorber/) qui fournit des fonctionnalités pour travailler avec les objets de placement d'image. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Accepte l'objet visiteur [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) qui fournit des fonctionnalités pour travailler avec les objets texte. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Accepte l'objet visiteur [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) qui fournit des fonctionnalités pour travailler avec les objets texte. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Ajoute des graphiques à la Page. Fonctionne plus rapidement que l'ajout d'éléments un par un avec la méthode [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Ajoute une image sur la Page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Ajoute une image sur la Page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Ajoute une image recherchable sur la Page et la place au centre du rectangle spécifié en conservant les proportions de l'image. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Ajoute une image sur la Page et la place en fonction de la position du rectangle de l'image. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Place un tampon dans la Page. Le tampon peut être un numéro de Page, une image ou un texte simple, par ex. un logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Convertit la Page actuelle en bitmap puis renvoie un tableau d'octets. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Convertit la Page actuelle en XML avec l'encodage UTF-8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Calcule la valeur bbox – rectangle contenant le contenu sans marges visibles. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Convertit la page en PNG pour le flux d'images DSR, OMR, OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Supprime les graphiques de la Page. Fonctionne plus rapidement que la suppression d'éléments un par un avec la méthode [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Libère la mémoire |
| [Flatten](../../aspose.pdf/page/flatten/)() | Supprime tous les champs situés sur la Page et place leurs valeurs à la place. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Efface les données en cache |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Renvoie les notifications concernant les opérations internes avec le contenu de la Page. (Seules les notifications concernant les événements de paragraphe dans les scénarios d'ajout de texte sont prises en charge pour le moment.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Renvoie le rectangle de la Page selon son CropBox (ou MediaBox si CropBox est nul). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Récupère les ressources associées à la Page. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Détecte la présence de graphiques vectoriels, s'ils sont présents sur la Page. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Obtient le drapeau indiquant si la Page est vide ou non. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Convertit la Page en niveaux de gris. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Fusionne toutes les calques de la Page en un seul calque avec le nom de calque spécifié. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Fusionne toutes les calques de la Page en un seul calque avec le nom de calque spécifié et un identifiant de groupe de contenu optionnel. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Redimensionne la Page. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Envoie la page au processus avec le dispositif de page fourni. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Envoie la page au processus avec le dispositif de page fourni. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Définit la taille de la page pour la page. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Essaie d'enregistrer les graphiques vectoriels s'ils sont présents sur la page. Le format d'enregistrement est SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Traduit la valeur entière en membre d'énumération de rotation correspondant. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Traduit le membre d'énumération de rotation en valeur entière. |

## Événements

| Nom | Description |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Événement pour personnaliser l'en-tête et le pied de page. |

## Autres membres

| Nom | Description |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Procédure pour personnaliser l'en-tête et le pied de page. |

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


