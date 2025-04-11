---
title: Class FormEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.FormEditor. Classe pour éditer des formulaires, ajouter/supprimer des champs, etc.
type: docs
weight: 4330
url: /fr/net/aspose.pdf.facades/formeditor/
---
## Classe FormEditor

Classe pour éditer des formulaires (ajouter/supprimer des champs, etc.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FormEditor](formeditor/#constructor)() | Constructeur pour FormEditor. |
| [FormEditor](formeditor/#constructor_1)(Document) | Initialise un nouvel objet `FormEditor` sur la base du *document*. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto/) { set; } | Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré dans le format PDF par défaut sans conversion. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur lequel il travaille. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems/) { get; set; } | Définit les options pour la boîte combinée avec des valeurs d'exportation. |
| [Facade](../../aspose.pdf.facades/formeditor/facade/) { get; set; } | Définit les attributs visuels du champ. |
| [Items](../../aspose.pdf.facades/formeditor/items/) { get; set; } | Définit les éléments qui seront ajoutés à la liste nouvellement créée ou à la boîte combinée. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize/) { get; set; } | Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap/) { get; set; } | Le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, par défaut 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz/) { get; set; } | Le drapeau pour indiquer si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag/) { get; set; } | Définit les drapeaux de soumission du bouton de soumission |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield)(FieldType, string, int, float, float, float, float) | Ajoute un champ du type spécifié au formulaire. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield/#addfield_1)(FieldType, string, string, int, float, float, float, float) | Ajoute un champ du type spécifié au formulaire. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript/)(string, string) | Ajoute JavaScript pour un champ PushButton. Si un ancien événement existe, le nouvel événement est ajouté après. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem)(string, string) | Ajoute un nouvel élément à la boîte de liste. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem/#addlistitem_1)(string, string[]) | Ajoute un nouvel élément avec une valeur d'exportation au champ de boîte de liste existant, uniquement pour le champ de boîte combinée AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn/)(string, int, string, string, float, float, float, float) | Ajoute un bouton de soumission au formulaire. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| override [Close](../../aspose.pdf.facades/formeditor/close/)() | Ferme la façade. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield)(string, string, int) | Copie un champ existant à la même position dans le numéro de page spécifié. Un nouveau document sera produit, qui contient tout ce que le document source a sauf pour le champ nouvellement copié. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield/#copyinnerfield_1)(string, string, int, float, float) | Copie un champ existant à une nouvelle position spécifiée par le numéro de page et les ordonnées. Un nouveau document sera produit, qui contient tout ce que le document source a sauf pour le champ nouvellement copié. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield)(string, string) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les ordonnées d'origine. Remarque : uniquement pour les champs AcroForm (excluant la case à cocher). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_1)(string, string, int) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les ordonnées d'origine. Remarque : uniquement pour les champs AcroForm (excluant la case à cocher). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield/#copyouterfield_2)(string, string, int, float, float) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les ordonnées. Remarque : uniquement pour les champs AcroForm (excluant la case à cocher). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield)() | Modifie les attributs visuels de tous les champs dans le document PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_1)(FieldType) | Modifie les attributs visuels de tous les champs avec le type de champ spécifié. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield/#decoratefield_2)(string) | Modifie les attributs visuels du champ spécifié. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem/)(string, string) | Supprime un élément du champ de liste. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Dispose de la façade. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance/)(string) | Obtient les drapeaux du champ. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield/)(string, float, float, float, float) | Définit la nouvelle position du champ. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield/)(string) | Supprime le champ du formulaire. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction/)(string) | Supprime l'action de soumission du champ. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield/)(string, string) | Change le nom du champ. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade/)() | Réinitialise tous les attributs visuels à une valeur vide. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade/)() | Réinitialise tous les attributs visuels de la façade intérieure à une valeur vide. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Enregistre le document PDF dans le fichier spécifié. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment/)(string, int) | Définit le style d'alignement d'un champ de texte. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv/)(string, int) | Définit le style d'alignement vertical d'un champ de texte. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance/)(string, AnnotationFlags) | Définit les drapeaux du champ |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute/)(string, PropertyFlag) | Définit les attributs du champ. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber/)(string, int) | Définit le nombre de combinaisons pour un champ de texte régulier à une seule ligne (le champ est automatiquement divisé en autant de positions également espacées, ou combinaisons, que la valeur du paramètre combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit/)(string, int) | Définit le nombre maximum de caractères du champ de texte. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript/)(string, string) | Définit JavaScript pour un champ PushButton. Si un ancien JavaScript existait, il sera remplacé par le nouveau. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag/)(string, SubmitFormFlag) | Définit le drapeau de soumission du bouton de soumission. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl/)(string, string) | Définit l'URL du bouton. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple/)(string) | Change un champ de texte à une seule ligne en un champ à plusieurs lignes. |

### Voir aussi

* classe [SaveableFacade](../saveablefacade/)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)