---
title: Form
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe représentant lobjet de formulaire.
type: docs
weight: 3020
url: /fr/net/aspose.pdf.forms/form/
---
## Form class

Classe représentant l'objet de formulaire.

```csharp
public sealed class Form : ICollection<WidgetAnnotation>
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoRecalculate](../../aspose.pdf.forms/form/autorecalculate) { get; set; } | Si défini, tous les champs du formulaire seront recalculés lorsqu'un champ est modifié. La valeur par défaut est true. Définir sur false afin d'augmenter les performances lors du remplissage d'un formulaire avec une grande quantité de champs calculés. |
| [AutoRestoreForm](../../aspose.pdf.forms/form/autorestoreform) { get; set; } | Si défini, les champs de formulaire absents seront automatiquement créés s'ils sont présents dans les annotations. |
| [CalculatedFields](../../aspose.pdf.forms/form/calculatedfields) { set; } | Permet de définir l'ordre de calcul des champs. |
| [Count](../../aspose.pdf.forms/form/count) { get; } | Obtient le nombre de champs de ce formulaire. |
| [DefaultAppearance](../../aspose.pdf.forms/form/defaultappearance) { get; set; } | Obtient ou définit l'apparence par défaut du formulaire (objet qui décrit la police, la taille du texte et la couleur par défaut des champs du formulaire). |
| [DefaultResources](../../aspose.pdf.forms/form/defaultresources) { get; } | Obtient les ressources par défaut placées sur ce formulaire. |
| [EmulateRequierdGroups](../../aspose.pdf.forms/form/emulaterequierdgroups) { get; set; } | Si cette propriété est vraie, des rectangles de délimitation rouges supplémentaires seront dessinés pour les conteneurs d'éléments Xfa exclGroup requis Cette propriété a été introduite en raison de l'absence d'analogues pour exclGroup lors de la conversion de la représentation Xfa des formes en standard. Elle est fausse par défaut. |
| [Fields](../../aspose.pdf.forms/form/fields) { get; } | Obtient la liste de tous les champs au niveau le plus bas de la forme hiérarchique. |
| [IgnoreNeedsRendering](../../aspose.pdf.forms/form/ignoreneedsrendering) { get; set; } | Si cette propriété est vraie, la valeur de la clé NeedsRendering sera ignorée lors de la conversion du formulaire XFA en formulaire standard. Il est faux par défaut. |
| [IsSynchronized](../../aspose.pdf.forms/form/issynchronized) { get; } | Renvoie true si l'objet est thread-safe. |
| [Item](../../aspose.pdf.forms/form/item) { get; } | Obtient le champ du formulaire par nom de champ. Lève une exception si le champ n'a pas été trouvé. (2 indexers) |
| [RemovePermission](../../aspose.pdf.forms/form/removepermission) { get; set; } | Si cette propriété est vraie, le dictionnaire "Perms" sera supprimé du document pdf après la conversion des documents dynamiques en standard. Le dictionnaire "Perms" peut contenir une règle qui perturbe l'affichage de la sélection de champs obligatoires dans Adobe Acrobat reader. Il est faux par défaut. |
| [SignaturesAppendOnly](../../aspose.pdf.forms/form/signaturesappendonly) { get; set; } | Si défini, le document contient des signatures qui peuvent être invalidées si le fichier est enregistré (écrit) d'une manière qui modifie son contenu précédent, par opposition à une mise à jour incrémentielle. |
| [SignaturesExist](../../aspose.pdf.forms/form/signaturesexist) { get; set; } | Si défini, le document contient au moins un champ de signature. |
| [SyncRoot](../../aspose.pdf.forms/form/syncroot) { get; } | Renvoie l'objet de synchronisation. |
| [Type](../../aspose.pdf.forms/form/type) { get; set; } | Obtient le type du formulaire. Les valeurs possibles sont : Standard, Statique, Dynamique. |
| [XFA](../../aspose.pdf.forms/form/xfa) { get; } | Obtient les données XFA du formulaire (si présentes). |

## Méthodes

| Nom | La description |
| --- | --- |
| [Add](../../aspose.pdf.forms/form/add#add_1)(Field) | Ajoute un champ sur le formulaire. |
| [Add](../../aspose.pdf.forms/form/add#add_2)(Field, int) | Ajoute un champ sur le formulaire. |
| [Add](../../aspose.pdf.forms/form/add#add)(Field, string, int) | Ajoute un nouveau champ au formulaire ; Si ce champ est déjà placé sur un autre ou sur ce formulaire, la copie du champ est créée. |
| [AddFieldAppearance](../../aspose.pdf.forms/form/addfieldappearance)(Field, int, Rectangle) | Ajoute une apparence supplémentaire du champ à la page spécifiée du document à l'emplacement spécifié. |
| [AssignXfa](../../aspose.pdf.forms/form/assignxfa)(XmlDocument) | Définit XFA du formulaire sur la valeur spécifiée. |
| [CopyTo](../../aspose.pdf.forms/form/copyto)(Field[], int) | Copie les champs placés sur le formulaire dans le tableau. |
| [Delete](../../aspose.pdf.forms/form/delete#delete)(Field) | Supprimer le champ du formulaire. |
| [Delete](../../aspose.pdf.forms/form/delete#delete_1)(string) | Supprime le champ du formulaire par son nom. |
| [Flatten](../../aspose.pdf.forms/form/flatten)() | Supprime tous les champs du formulaire et place leurs valeurs directement sur la page. |
| [GetEnumerator](../../aspose.pdf.forms/form/getenumerator)() | Obtient l'énumération des champs de formulaire. |
| [GetFieldsInRect](../../aspose.pdf.forms/form/getfieldsinrect)(Rectangle) | Renvoie les champs à l'intérieur du rectangle spécifié. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield)(Field) | Vérifiez si le formulaire a déjà un champ spécifié. |
| [HasField](../../aspose.pdf.forms/form/hasfield#hasfield_1)(string) | Détermine si le champ avec le nom spécifié a déjà été ajouté au formulaire. |

## Des champs

| Nom | La description |
| --- | --- |
| [SignDependentElementsRenderingModeWhenConverted](../../aspose.pdf.forms/form/signdependentelementsrenderingmodewhenconverted) | Les formulaires peuvent contenir des informations de signature, c'est-à-dire qu'ils peuvent être signés ou non signés. Et la vue du formulaire doit parfois dépendre du fait que le formulaire est signé ou non. Cette propriété indique au convertisseur de formulaire (par exemple lors de la conversion du formulaire XFA en formulaire standard) si le formulaire de résultat doit être rendu comme signé ou comme non signé. |

## Autres membres

| Nom | La description |
| --- | --- |
| class [FlattenSettings](form.flattensettings) | Classe décrivant les paramètres de la procédure d'aplatissement du formulaire. |
| enum [SignDependentElementsRenderingModes](form.signdependentelementsrenderingmodes) | Les formulaires peuvent contenir des informations de signature et peuvent être signés ou non signés. Parfois, l'affichage des formulaires dans la visionneuse doit dépendre du fait que le formulaire est signé ou non. Cette énumération énumère les modes de rendu possibles lors de la conversion du type de formulaire en ce qui concerne le signe. |

### Voir également

* class [WidgetAnnotation](../../aspose.pdf.annotations/widgetannotation)
* espace de noms [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
