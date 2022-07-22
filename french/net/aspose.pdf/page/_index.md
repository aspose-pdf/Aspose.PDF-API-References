---
title: Page
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe représentant la page du document PDF.
type: docs
weight: 5790
url: /fr/net/aspose.pdf/page/
---
## Page class

Classe représentant la page du document PDF.

```csharp
public sealed class Page : IDisposable
```

## Propriétés

| Nom | La description |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions) { get; } | Obtient une collection de propriétés de page. |
| [Annotations](../../aspose.pdf/page/annotations) { get; } | Obtient une collection d'annotations de page. [`Annotations`](./annotations) |
| [ArtBox](../../aspose.pdf/page/artbox) { get; set; } | Obtient ou définit la zone d'art de la page. |
| [Artifacts](../../aspose.pdf/page/artifacts) { get; } | Obtient une collection d'artefacts sur la page. |
| [Background](../../aspose.pdf/page/background) { get; set; } | Obtient ou définit la couleur d'arrière-plan de la page. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage) { get; set; } | Obtient ou définit l'image d'arrière-plan de la page (pour le générateur uniquement). |
| [BleedBox](../../aspose.pdf/page/bleedbox) { get; set; } | Obtient ou définit la zone de fond perdu de la page. |
| [ColorType](../../aspose.pdf/page/colortype) { get; } | Définit le type de couleur des pages en fonction des informations obtenues des opérateurs SetColor, images et formulaires. |
| [Contents](../../aspose.pdf/page/contents) { get; } | Obtient une collection d'opérateurs dans le flux de contenu de la page. [`OperatorCollection`](../operatorcollection) |
| [CropBox](../../aspose.pdf/page/cropbox) { get; set; } | Obtient ou définit la zone de recadrage de la page. |
| [Duration](../../aspose.pdf/page/duration) { get; set; } | Obtient la durée d'affichage de la page définie. Il s'agit du temps en secondes pendant lequel la page doit être affichée lors de la présentation. Renvoie -1 si la durée n'est pas définie. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder) { get; } | Obtient la liste des objets Field dans l'ordre de tabulation sur cette page. |
| [Footer](../../aspose.pdf/page/footer) { get; set; } | Obtient ou définit le pied de page. |
| [Group](../../aspose.pdf/page/group) { get; set; } | Obtient ou définit une classe d'attributs de groupe spécifiant les attributs du groupe de pages de la page à utiliser dans le modèle d'imagerie transparent. |
| [Header](../../aspose.pdf/page/header) { get; set; } | Obtient ou définit l'en-tête de page. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast) { get; set; } | Obtient ou définit l'ajout de paragraphes après le dernier paragraphe de la page |
| [Layers](../../aspose.pdf/page/layers) { get; set; } | Obtient ou définit la collection de calques. |
| [MediaBox](../../aspose.pdf/page/mediabox) { get; set; } | Obtient ou définit la boîte multimédia de la page. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle) { get; set; } | Obtient ou définit le style de ligne pour les notes. (pour le générateur uniquement) |
| [Number](../../aspose.pdf/page/number) { get; } | Obtenir le numéro de la page. |
| [PageInfo](../../aspose.pdf/page/pageinfo) { get; set; } | Obtient ou définit les informations de la page (pour le générateur uniquement, non renseigné lors de la lecture du fichier). |
| [Paragraphs](../../aspose.pdf/page/paragraphs) { get; set; } | Récupère les paragraphes. |
| [Rect](../../aspose.pdf/page/rect) { get; set; } | Obtient ou définit le rectangle de la page. La boîte de recadrage de la page est renvoyée si elle est spécifiée, sinon la boîte de média de la page est renvoyée. Veuillez noter que cette propriété ne prend pas en compte la rotation de la page. Pour obtenir un rectangle de page en tenant compte de la rotation, veuillez utiliser ActualRect. |
| [Resources](../../aspose.pdf/page/resources) { get; } | Obtient les ressources de la page. L'objet Resources contient des collections d'images, de formulaires et de polices. [`Resources`](./resources) |
| [Rotate](../../aspose.pdf/page/rotate) { get; set; } | Obtient ou définit la rotation de la page. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix) { get; } | Obtient la matrice de transformation pour la page. |
| [TabOrder](../../aspose.pdf/page/taborder) { get; set; } | Obtient ou définit l'ordre de tabulation de la page. Valeurs possibles : Ligne, Colonne. Par défaut, Manuel |
| [TocInfo](../../aspose.pdf/page/tocinfo) { get; set; } | Obtient ou définit les informations de la table des matières. |
| [TrimBox](../../aspose.pdf/page/trimbox) { get; set; } | Obtient ou définit la zone de rognage de la page. |
| [UserUnit](../../aspose.pdf/page/userunit) { get; set; } | Obtient ou définit la valeur UserUnit. Un nombre positif donnant la taille des unités d'espace utilisateur par défaut, en multiples de 1 ⁄ 72 pouces. La valeur par défaut est 1. Veuillez définir zéro ou une valeur négative afin d'effacer cette entrée dans la page. |
| [Watermark](../../aspose.pdf/page/watermark) { get; set; } | Obtient ou définit le filigrane de la page. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept#accept)(AnnotationSelector) | Accepte[`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector) objet visiteur qui fournit des fonctionnalités pour travailler avec des annotations. |
| [Accept](../../aspose.pdf/page/accept#accept_1)(ImagePlacementAbsorber) | Accepte[`ImagePlacementAbsorber`](../imageplacementabsorber) objet visiteur qui fournit des fonctionnalités pour travailler avec des objets de placement d'image. |
| [Accept](../../aspose.pdf/page/accept#accept_2)(TextAbsorber) | Accepte[`TextAbsorber`](../../aspose.pdf.text/textabsorber) objet visiteur qui fournit des fonctionnalités pour travailler avec des objets texte. |
| [Accept](../../aspose.pdf/page/accept#accept_3)(TextFragmentAbsorber) | Accepte[`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber) objet visiteur qui fournit des fonctionnalités pour travailler avec des objets texte. |
| [AddImage](../../aspose.pdf/page/addimage#addimage)(Stream, Rectangle) | Ajoute une image sur la page et la place au milieu du rectangle spécifié en sauvegardant la proportion de l'image. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_2)(string, Rectangle) | Ajoute une image sur la page et la place au milieu du rectangle spécifié en sauvegardant la proportion de l'image. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_3)(string, Stream, Rectangle) | Ajoute une image consultable sur la page et la place au milieu du rectangle spécifié en sauvegardant la proportion de l'image. |
| [AddImage](../../aspose.pdf/page/addimage#addimage_1)(Stream, Rectangle, int, int, bool) | Ajoute une image sur la page et la place en fonction de la position du rectangle de l'image. |
| [AddStamp](../../aspose.pdf/page/addstamp)(Stamp) | Mettez le tampon dans la page. Le tampon peut être un numéro de page, une image ou un texte simple, par exemple un logo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray)(Resolution) | Convertit la page actuelle en bitmap et renvoie un tableau d'octets. |
| [AsXml](../../aspose.pdf/page/asxml)() | Convertit la page actuelle en xml en codage utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox)() | Calcule la valeur bbox - rectangle contenant du contenu sans marges visibles. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream)() | Convertir la page en PNG pour le flux d'images DSR, OMR, OCR. |
| [Dispose](../../aspose.pdf/page/dispose)() | Libère de la mémoire |
| [Flatten](../../aspose.pdf/page/flatten)() | Supprime tous les champs situés sur la page et place leurs valeurs à la place. |
| [FreeMemory](../../aspose.pdf/page/freememory)() | Efface les données mises en cache |
| [GetNotifications](../../aspose.pdf/page/getnotifications)() | Renvoie des notifications sur les opérations internes avec le contenu de la page. (Seules les notifications concernant les événements de paragraphe dans les scénarios d'ajout de texte sont désormais prises en charge.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect)(bool) | Renvoie le rectangle de la page. |
| [IsBlank](../../aspose.pdf/page/isblank)(double) | Obtient le drapeau si la page est vide ou non. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale)() | Convertit la page en niveaux de gris. |
| [SendTo](../../aspose.pdf/page/sendto#sendto)(PageDevice, Stream) | Envoie la page à traiter avec le périphérique de page donné. |
| [SendTo](../../aspose.pdf/page/sendto#sendto_1)(PageDevice, string) | Envoie la page à traiter avec le périphérique de page donné. |
| [SetPageSize](../../aspose.pdf/page/setpagesize)(double, double) | Définit la taille de la page pour la page. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation)(int) | Traduit la valeur entière en membre d'énumération de rotation correspondant. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint)(Rotation) | Traduit le membre d'énumération de rotation en valeur entière. |

## Autres membres

| Nom | La description |
| --- | --- |
| delegate [BeforePageGenerate](page.beforepagegenerate) | Procédure de personnalisation de l'en-tête et du pied de page. |

### Voir également

* espace de noms [Aspose.Pdf](../../aspose.pdf)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
