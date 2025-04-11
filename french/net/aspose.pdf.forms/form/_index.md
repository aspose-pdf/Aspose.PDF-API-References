---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.Form. Classe représentant un objet formulaire
type: docs
weight: 5070
url: /fr/net/aspose.pdf.forms/form/
---
## Classe Formulaire

Classe représentant un objet formulaire.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate/) { get; set; } | Si défini, tous les champs du formulaire seront recalculés lorsqu'un champ est modifié. La valeur par défaut est true. Définir sur false afin d'augmenter les performances lors du remplissage du formulaire avec un grand nombre de champs calculés. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform/) { get; set; } | Si défini, les champs de formulaire absents seront automatiquement créés s'ils sont présents dans les annotations. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields/) { set; } | Permet de définir l'ordre de calcul des champs. |
| [Count](../../aspose.pdf.forms/form/count/) { get; } | Obtient le nombre de champs sur ce formulaire. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance/) { get; set; } | Obtient ou définit l'apparence par défaut du formulaire (objet qui décrit la police par défaut, la taille du texte et la couleur pour les champs du formulaire). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources/) { get; } | Obtient les ressources par défaut placées sur ce formulaire. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups/) { get; set; } | Si cette propriété est vraie, des rectangles de contour rouges supplémentaires seront dessinés pour les conteneurs d'éléments exclGroup Xfa requis. Cette propriété a été introduite en raison de l'absence d'analogues pour l'exclGroup lors de la conversion de la représentation Xfa des formulaires en standard. Elle est fausse par défaut. |
| [Fields](../../aspose.pdf.forms/form/fields/) { get; } | Obtient la liste de tous les champs au niveau le plus bas du formulaire hiérarchique. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering/) { get; set; } | Si cette propriété est vraie, la valeur de la clé NeedsRendering sera ignorée lors de la conversion du formulaire XFA en formulaire standard. Elle est fausse par défaut. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized/) { get; } | Renvoie true si l'objet est thread-safe. |
| [Item](../../aspose.pdf.forms/form/item/) { get; } | Obtient le champ du formulaire par nom de champ. Lance une exception si le champ n'a pas été trouvé. (2 indexeurs) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission/) { get; set; } | Si cette propriété est vraie, le dictionnaire "Perms" sera supprimé du document pdf après la conversion des documents dynamiques en standard. Le dictionnaire "Perms" peut contenir des règles qui perturbent l'affichage de la sélection des champs obligatoires dans Adobe Acrobat Reader. Elle est fausse par défaut. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly/) { get; set; } | Si défini, le document contient des signatures qui peuvent être invalidées si le fichier est enregistré (écrit) d'une manière qui modifie son contenu précédent, par opposition à une mise à jour incrémentielle. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist/) { get; set; } | Si défini, le document contient au moins un champ de signature. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot/) { get; } | Renvoie l'objet de synchronisation. |
| [Type](../../aspose.pdf.forms/form/type/) { get; set; } | Obtient le type du formulaire. Les valeurs possibles sont : Standard, Statique, Dynamique. |
| [XFA](../../aspose.pdf.forms/form/xfa/) { get; } | Obtient les données XFA du formulaire (si présentes). |

## Méthodes

| Nom | Description |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add/#add_1)(Field) | Ajoute un champ au formulaire. |
| [Add](../../aspose.pdf.forms/form/add/#add_2)(Field, int) | Ajoute un champ au formulaire. |
| [Add](../../aspose.pdf.forms/form/add/#add)(Field, string, int) | Ajoute un nouveau champ au formulaire ; si ce champ est déjà placé sur un autre formulaire ou ce formulaire, une copie du champ est créée. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance/)(Field, int, Rectangle) | Ajoute une apparence supplémentaire du champ à la page spécifiée du document à l'emplacement spécifié. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa/)(XmlDocument) | Définit XFA du formulaire à la valeur spécifiée. |
| [CopyTo](../../aspose.pdf.forms/form/copyto/)(Field[], int) | Copie les champs placés sur le formulaire dans un tableau. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete)(Field) | Supprime un champ du formulaire. |
| [Delete](../../aspose.pdf.forms/form/delete/#delete_1)(string) | Supprime un champ du formulaire par son nom. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson)(Stream, ExportFieldsToJsonOptions) | Exporte les champs du formulaire PDF au format JSON et écrit le résultat dans le flux fourni. |
| [ExportToJson](../../aspose.pdf.forms/form/exporttojson/#exporttojson_1)(string, ExportFieldsToJsonOptions) | Exporte les champs du formulaire PDF au format JSON et écrit le résultat dans le fichier spécifié. |
| [Flatten](../../aspose.pdf.forms/form/flatten/)() | Supprime tous les champs du formulaire et place leurs valeurs directement sur la page. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator/)() | Obtient l'énumération des champs du formulaire. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect/)(Rectangle) | Renvoie les champs à l'intérieur du rectangle spécifié. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield)(Field) | Vérifie si le formulaire a déjà le champ spécifié. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_1)(string) | Détermine si le champ avec le nom spécifié a déjà été ajouté au formulaire. |
| [HasField](../../aspose.pdf.forms/form/hasfield/#hasfield_2)(string, bool) | Détermine si le champ avec le nom spécifié a déjà été ajouté au formulaire, avec la possibilité de regarder dans la hiérarchie des enfants des champs. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson)(Stream) | Importe les champs du formulaire PDF à partir du format JSON fourni dans le flux. |
| [ImportFromJson](../../aspose.pdf.forms/form/importfromjson/#importfromjson_1)(string) | Importe les champs du formulaire PDF à partir du format JSON fourni dans le fichier spécifié. |
| [MakeFormAnnotationsIndependent](../../aspose.pdf.forms/form/makeformannotationsindependent/)(Page) | Rend les annotations des champs de formulaire indépendantes. |
| [RemoveFieldAppearance](../../aspose.pdf.forms/form/removefieldappearance/)(Field, int) | Supprime l'apparence du champ à l'index spécifié. Si une seule apparence enfant reste, la méthode l'incorpore dans le champ. |

## Champs

| Nom | Description |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted/) | Les formulaires peuvent contenir des informations de signature, c'est-à-dire peuvent être signés ou non signés. Et la vue du formulaire doit parfois dépendre de savoir si le formulaire est signé ou non. Cette propriété indique au convertisseur de formulaire (par exemple, lors de la conversion d'un formulaire XFA en formulaire standard) si le formulaire résultant doit être rendu comme signé ou non signé. |

## Autres Membres

| Nom | Description |
| --- | --- |
| class [FlattenSettings](../../aspose.pdf.forms/form.flattensettings) | Classe qui décrit les paramètres pour la procédure de flattening du formulaire. |
| enum [SignDependentElementsRenderingModes](../../aspose.pdf.forms/form.signdependentelementsrenderingmodes) | Les formulaires peuvent contenir des informations de signature et peuvent être signés ou non signés. Parfois, la vue des formulaires dans le visualiseur doit dépendre de savoir si le formulaire est signé ou non. Cet énumère les modes de rendu possibles lors de la conversion du type de formulaire en ce qui concerne la signature. |

### Voir aussi

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)