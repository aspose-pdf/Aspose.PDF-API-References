---
title: Field
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe de base pour les champs de formulaire acro.
type: docs
weight: 3000
url: /fr/net/aspose.pdf.forms/field/
---
## Field class

Classe de base pour les champs de formulaire acro.

```csharp
public class Field : WidgetAnnotation, ICollection<WidgetAnnotation>
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Field](field)(Document) | Crée un champ à utiliser dans Generator. |

## Propriétés

| Nom | La description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Obtient les actions d'annotation. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Obtient ou définit le nom alternatif du champ (un nom de champ alternatif qui doit être utilisé à la place du nom de champ réel partout où le champ doit être identifié dans l'interface utilisateur). Le nom alternatif est utilisé comme info-bulle de champ dans Adobe Acrobat . |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Obtient ou définit l'index de cette annotation sur la page. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Obtient ou définit les caractéristiques de bordure d'annotation.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Obtient les caractéristiques d'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Obtient ou définit le texte d'annotation. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Obtient ou définit le nombre de sous-champs dans ce champ. (Par exemple, le nombre d'éléments dans le champ du bouton radio). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Obtient ou définit l'apparence par défaut du champ. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Obtient ou définit l'indicateur exportable du champ. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Obtient le nom qualifié complet de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Mode de mise en surbrillance des annotations. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Obtient ou définit le lien hypertexte du fragment (pour le générateur de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. La valeur par défaut est false.(for pdf generation) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Obtient ou définit la valeur booléenne qui indique que ce champ est un champ non terminal, c'est-à-dire un groupe de champs. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Obtient ou définit qu'un paragraphe est en ligne. La valeur par défaut est false.(pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Obtient ou définit une valeur booléenne qui force la génération de ce paragraphe sur une nouvelle page. La valeur par défaut est false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste dans la même page avec le paragraphe suivant. La valeur par défaut est false.(for pdf generation) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Propriété pour la prise en charge du générateur. Utilisé lorsque le champ est ajouté à l'en-tête ou au pied de page. Si vrai, ce champ sera créé une fois et son apparence sera visible sur toutes les pages du document. Si faux, un champ séparé sera créé pour chaque page de document. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Renvoie true si le dictionnaire est synchronisé. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Obtient le sous-champ contenu dans ce champ par le nom du sous-champ. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Obtient ou définit le nom de mappage du champ qui doit être utilisé lors de l'exportation des données de champ de formulaire interactif à partir du document. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Obtient ou définit la date et l'heure auxquelles l'annotation a été récemment modifiée. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | Une action qui doit être effectuée lorsque l'annotation est activée. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Obtient l'index de la page qui contient ce champ. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Obtient l'annotation parent. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Obtient ou définit le nom partiel du champ. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Obtient ou définit l'état de lecture seule du champ. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Obtient ou définit le rectangle de champ. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Obtient ou définit l'état requis du champ. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Objet de synchronisation. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Obtient ou définit l'ordre de tabulation du champ. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| virtual [Value](../../aspose.pdf.forms/field/value) { get; set; } | Obtient ou définit la valeur du champ. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé sur le graphique avec un ZIndex plus petit. ZIndex peut être négatif. Le graphique avec ZIndex négatif sera placé derrière le texte dans la page. |
| static [FitIntoRectangle](../../aspose.pdf.forms/field/fitintorectangle) { get; set; } | Si vrai, la taille de la police sera réduite pour ajuster le texte au rectangle spécifié. |
| static [MaxFontSize](../../aspose.pdf.forms/field/maxfontsize) { get; set; } | Taille de police Maximail pouvant être utilisée pour le contenu des champs. -1 pour ne pas vérifier la taille. |
| static [MinFontSize](../../aspose.pdf.forms/field/minfontsize) { get; set; } | Taille de police minimale pouvant être utilisée pour le contenu des champs. -1 pour ne pas vérifier la taille. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Accepte le visiteur. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Mettre à jour les paramètres et l'apparence, selon la transformation matricielle. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Copie les sous-champs de ce champ dans le tableau à partir de l'index spécifié. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Supprime ce champ et place sa valeur directement sur la page. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | Renvoie l'énumérateur des champs contenus. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Renvoie le rectangle d'annotation en tenant compte de la rotation de la page. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Recactualise tous les champs calculés du formulaire. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Définir la position du champ. |

### Voir également

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* espace de noms [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
