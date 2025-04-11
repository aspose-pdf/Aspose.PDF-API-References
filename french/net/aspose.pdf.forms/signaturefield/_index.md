---
title: Class SignatureField
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.SignatureField. Représente un champ de formulaire de signature
type: docs
weight: 5290
url: /fr/net/aspose.pdf.forms/signaturefield/
---
## Classe SignatureField

Représente un champ de formulaire de signature.

```csharp
public sealed class SignatureField : Field
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SignatureField](signaturefield/#constructor)(Document, Rectangle) | Initialise une nouvelle instance de la classe `SignatureField`. |
| [SignatureField](signaturefield/#constructor_1)(Page, Rectangle) | Initialise une nouvelle instance de la classe `SignatureField`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Obtient les actions d'annotation. (2 propriétés) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Obtient ou définit l'état d'apparence actuel de l'annotation. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Obtient ou définit le nom alternatif du champ (Un nom de champ alternatif qui doit être utilisé à la place du nom de champ réel chaque fois que le champ doit être identifié dans l'interface utilisateur). Le nom alternatif est utilisé comme info-bulle de champ dans Adobe Acrobat. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Obtient ou définit l'index de cette annotation sur la page. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Obtient le type d'annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Obtient ou définit les caractéristiques de la bordure de l'annotation. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Obtient les caractéristiques de l'annotation. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Obtient ou définit la couleur de l'annotation. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Obtient ou définit le texte de l'annotation. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Obtient le nombre de sous-champs dans ce champ. (Par exemple, le nombre d'éléments dans un champ de bouton radio). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Obtient ou définit l'apparence par défaut du champ. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Obtient ou définit le drapeau exportable du champ. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Drapeaux de l'annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Obtient le nom complet qualifié de l'annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Obtient ou définit la hauteur de l'annotation. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Mode de surlignage de l'annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Obtient ou définit l'hyperlien de fragment (pour le générateur de pdf). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si ce paragraphe sera dans la colonne suivante. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Obtient ou définit une valeur booléenne qui indique si ce champ est un champ non terminal, c'est-à-dire un groupe de champs. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Obtient ou définit si un paragraphe est en ligne. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Obtient ou définit une valeur booléenne qui force ce paragraphe à être généré sur une nouvelle page. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Obtient ou définit une valeur booléenne qui indique si le paragraphe actuel reste sur la même page que le paragraphe suivant. Par défaut, c'est faux. (pour la génération de pdf) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Propriété pour le support du générateur. Utilisé lorsque le champ est ajouté à l'en-tête ou au pied de page. Si vrai, ce champ sera créé une fois et son apparence sera visible sur toutes les pages du document. Si faux, un champ séparé sera créé pour chaque page du document. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Renvoie vrai si le dictionnaire est synchronisé. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Obtient le sous-champ contenu dans ce champ par le nom du sous-champ. (2 indexeurs) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Obtient ou définit le nom de mappage du champ qui doit être utilisé lors de l'exportation des données de champ de formulaire interactif depuis le document. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Obtient ou définit une marge extérieure pour le paragraphe (pour la génération de pdf) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Obtient ou définit la date et l'heure auxquelles l'annotation a été récemment modifiée. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Obtient ou définit le nom de l'annotation sur la page. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Une action qui doit être effectuée lorsque l'annotation est activée. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Obtient l'index de la page qui contient ce champ. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Obtient le parent de l'annotation. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Obtient ou définit le nom partiel du champ. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Obtient ou définit le statut en lecture seule du champ. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Obtient ou définit le rectangle du champ. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Obtient ou définit le statut requis du champ. |
| [Signature](../../aspose.pdf.forms/signaturefield/signature/) { get; } | Obtient l'objet signature. Cet objet contient des données de signature concernant les normes cryptographiques à clé publique. Les classes [`PKCS1`](../pkcs1/), [`PKCS7`](../pkcs7/) et [`PKCS7Detached`](../pkcs7detached/) représentent tous les types d'objets de signature pris en charge. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Obtient le dictionnaire d'apparence de l'annotation. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Objet de synchronisation. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Obtient ou définit l'ordre des onglets du champ. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Obtient ou définit l'alignement du texte pour l'annotation. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | Obtient ou définit la valeur du champ. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Obtient ou définit un alignement vertical du paragraphe |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Obtient ou définit la largeur de l'annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Obtient ou définit une valeur int qui indique l'ordre Z du graphique. Un graphique avec un ZIndex plus grand sera placé au-dessus du graphique avec un ZIndex plus petit. ZIndex peut être négatif. Un graphique avec un ZIndex négatif sera placé derrière le texte sur la page. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Accepte le visiteur. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Met à jour les paramètres et l'apparence, selon la transformation de matrice. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clone cette instance. Méthode virtuelle. Renvoie toujours null. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Copie les sous-champs de ce champ dans un tableau à partir de l'index spécifié. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Exécute une action JavaScript spécifiée pour le champ. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exporte le champ de formulaire PDF spécifié au format JSON et écrit le résultat dans le flux fourni. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Exporte le champ de formulaire PDF spécifié au format JSON et écrit le résultat dans le fichier spécifié. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Exporte le contenu du champ spécifié dans un flux JSON. Les valeurs des champs de bouton ne sont pas exportées. |
| [ExtractCertificate](../../aspose.pdf.forms/signaturefield/extractcertificate/)() | Extrait le certificat X.509 unique au format DER sous forme de flux. |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage)() | Extrait l'image de la signature sous forme de flux encodé en jpeg. |
| [ExtractImage](../../aspose.pdf.forms/signaturefield/extractimage/#extractimage_1)(ImageFormat) | Extrait l'image de la signature sous forme de flux encodé. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Supprime ce champ et place sa valeur directement sur la page. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Renvoie le nom de l'état "coché" selon les noms d'état existants. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | Renvoie l'énumérateur des champs contenus. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Renvoie le rectangle de l'annotation en tenant compte de la rotation de la page. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Importe des données dans les champs spécifiés à partir d'un flux JSON, sur la base d'une correspondance exacte des noms complets des champs. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | Importe des données dans le champ spécifié à partir d'un flux JSON, en utilisant le nom complet spécifié dans la variable 'fieldFullNameInJSON' pour la correspondance. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Recalcule tous les champs calculés sur le formulaire. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Définit la position du champ. |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign)(Signature) | Signe le document en utilisant ce champ de signature. |
| [Sign](../../aspose.pdf.forms/signaturefield/sign/#sign_1)(Signature, Stream, string) | Signe le document en utilisant ce champ de signature. |

### Voir aussi

* classe [Field](../field/)
* espace de noms [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)