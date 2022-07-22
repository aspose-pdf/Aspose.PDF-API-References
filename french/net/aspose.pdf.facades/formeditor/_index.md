---
title: FormEditor
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe pour lédition de formulaires ajout/suppression de champs etc.
type: docs
weight: 2340
url: /fr/net/aspose.pdf.facades/formeditor/
---
## FormEditor class

Classe pour l'édition de formulaires (ajout/suppression de champs, etc.)

```csharp
public sealed class FormEditor : SaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [FormEditor](formeditor#constructor)() | Constructeur pour FormEditor. |
| [FormEditor](formeditor#constructor_1)(Document) | Initialise nouveau[`FormEditor`](../formeditor) objet sur la base de la*document* . |

## Propriétés

| Nom | La description |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/formeditor/attachmentname) { get; set; } | Obtient ou définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [ContentDisposition](../../aspose.pdf.facades/formeditor/contentdisposition) { get; set; } | Obtient ou définit la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. Valeur possible : en ligne / pièce jointe. Par défaut : en ligne. |
| [ConvertTo](../../aspose.pdf.facades/formeditor/convertto) { set; } | Définit le format de fichier PDF. Le fichier de résultat sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [ExportItems](../../aspose.pdf.facades/formeditor/exportitems) { get; set; } | Définit les options de la zone de liste déroulante avec les valeurs d'exportation. |
| [Facade](../../aspose.pdf.facades/formeditor/facade) { get; set; } | Définit les attributs visuels du champ. |
| [Items](../../aspose.pdf.facades/formeditor/items) { get; set; } | Définit les éléments qui seront ajoutés à la zone de liste ou à la zone de liste déroulante nouvellement créée. |
| [RadioButtonItemSize](../../aspose.pdf.facades/formeditor/radiobuttonitemsize) { get; set; } | Obtient ou définit la taille de l'élément de bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). |
| [RadioGap](../../aspose.pdf.facades/formeditor/radiogap) { get; set; } | Le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50. |
| [RadioHoriz](../../aspose.pdf.facades/formeditor/radiohoriz) { get; set; } | Le drapeau pour indiquer si les radios sont disposées horizontalement ou verticalement, la valeur par défaut est true. |
| [Response](../../aspose.pdf.facades/formeditor/response) { get; set; } | Obtient ou définit l'objet de réponse où le résultat de l'opération sera stocké. |
| [SaveOptions](../../aspose.pdf.facades/formeditor/saveoptions) { get; set; } | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [SubmitFlag](../../aspose.pdf.facades/formeditor/submitflag) { get; set; } | Définir les drapeaux de soumission du bouton de soumission |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield)(FieldType, string, int, float, float, float, float) | Ajouter un champ du type spécifié au formulaire. |
| [AddField](../../aspose.pdf.facades/formeditor/addfield#addfield_1)(FieldType, string, string, int, float, float, float, float) | Ajouter un champ du type spécifié au formulaire. |
| [AddFieldScript](../../aspose.pdf.facades/formeditor/addfieldscript)(string, string) | Ajoutez du JavaScript pour un champ PushButton. Si un ancien événement existe, un nouvel événement est ajouté après celui-ci. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem)(string, string) | Ajoute un nouvel élément à la zone de liste. |
| [AddListItem](../../aspose.pdf.facades/formeditor/addlistitem#addlistitem_1)(string, string[]) | Ajouter un nouvel élément avec une valeur d'exportation au champ de zone de liste existant, uniquement pour le champ de zone de liste déroulante AcroForm. |
| [AddSubmitBtn](../../aspose.pdf.facades/formeditor/addsubmitbtn)(string, int, string, string, float, float, float, float) | Ajouter un bouton d'envoi sur le formulaire. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialise la façade. |
| override [Close](../../aspose.pdf.facades/formeditor/close)() | Ferme la façade. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield)(string, string, int) | Copie un champ existant à la même position dans le numéro de page spécifié. Un nouveau document sera produit, qui contiendra tout ce que le document source a à l'exception du champ nouvellement copié. |
| [CopyInnerField](../../aspose.pdf.facades/formeditor/copyinnerfield#copyinnerfield_1)(string, string, int, float, float) | Copie un champ existant vers une nouvelle position spécifiée à la fois par le numéro de page et les ordonnées. Un nouveau document sera produit, qui contiendra tout ce que contient le document source à l'exception du champ nouvellement copié. |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield)(string, string) | Copie un champ existant d'un document PDF vers un autre document avec le numéro de page et les ordonnées d'origine. Remarque : Uniquement pour les champs AcroForm (hors boîte radio). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_1)(string, string, int) | Copie un champ existant d'un document PDF vers un autre document avec le numéro de page spécifié et les ordonnées d'origine. Remarque : Uniquement pour les champs AcroForm (à l'exclusion de la boîte radio). |
| [CopyOuterField](../../aspose.pdf.facades/formeditor/copyouterfield#copyouterfield_2)(string, string, int, float, float) | Copie un champ existant d'un document PDF vers un autre document avec un numéro de page et des ordonnées spécifiés. Remarque : Uniquement pour les champs AcroForm (à l'exclusion de la boîte radio). |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield)() | Modifie les attributs visuels de tous les champs du document PDF. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_1)(FieldType) | Modifie les attributs visuels de tous les champs avec le type de champ spécifié. |
| [DecorateField](../../aspose.pdf.facades/formeditor/decoratefield#decoratefield_2)(string) | Modifie les attributs visuels du champ spécifié. |
| [DelListItem](../../aspose.pdf.facades/formeditor/dellistitem)(string, string) | Supprimer l'élément du champ de liste. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [GetFieldAppearance](../../aspose.pdf.facades/formeditor/getfieldappearance)(string) | Obtenir les indicateurs de champ. |
| [MoveField](../../aspose.pdf.facades/formeditor/movefield)(string, float, float, float, float) | Définir la nouvelle position du champ. |
| [RemoveField](../../aspose.pdf.facades/formeditor/removefield)(string) | Supprimer le champ du formulaire. |
| [RemoveFieldAction](../../aspose.pdf.facades/formeditor/removefieldaction)(string) | Supprimer l'action de soumission du champ. |
| [RenameField](../../aspose.pdf.facades/formeditor/renamefield)(string, string) | Modifier le nom du champ. |
| [ResetFacade](../../aspose.pdf.facades/formeditor/resetfacade)() | Réinitialiser tous les attributs visuels sur une valeur vide. |
| [ResetInnerFacade](../../aspose.pdf.facades/formeditor/resetinnerfacade)() | Réinitialiser tous les attributs visuels de la façade intérieure sur une valeur vide. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Enregistre le document PDF dans le flux spécifié. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Enregistre le document PDF dans le fichier spécifié. |
| [SetFieldAlignment](../../aspose.pdf.facades/formeditor/setfieldalignment)(string, int) | Définir le style d'alignement d'un champ de texte. |
| [SetFieldAlignmentV](../../aspose.pdf.facades/formeditor/setfieldalignmentv)(string, int) | Définir le style d'alignement vertical d'un champ de texte. |
| [SetFieldAppearance](../../aspose.pdf.facades/formeditor/setfieldappearance)(string, AnnotationFlags) | Définir les indicateurs de champ |
| [SetFieldAttribute](../../aspose.pdf.facades/formeditor/setfieldattribute)(string, PropertyFlag) | Définir les attributs du champ. |
| [SetFieldCombNumber](../../aspose.pdf.facades/formeditor/setfieldcombnumber)(string, int) | Définit le nombre de peignes pour un champ de texte régulier sur une seule ligne (le champ est automatiquement divisé en autant de positions équidistantes, ou peignes, que la valeur du paramètre combNumber). |
| [SetFieldLimit](../../aspose.pdf.facades/formeditor/setfieldlimit)(string, int) | Définit le nombre maximal de caractères du champ de texte. |
| [SetFieldScript](../../aspose.pdf.facades/formeditor/setfieldscript)(string, string) | Définissez JavaScript pour un champ PushButton. Si l'ancien JavaScript existait, il sera remplacé par le nouveau. |
| [SetSubmitFlag](../../aspose.pdf.facades/formeditor/setsubmitflag)(string, SubmitFormFlag) | Définir l'indicateur de soumission du bouton de soumission. |
| [SetSubmitUrl](../../aspose.pdf.facades/formeditor/setsubmiturl)(string, string) | Définit l'URL du bouton. |
| [Single2Multiple](../../aspose.pdf.facades/formeditor/single2multiple)(string) | Changer un champ de texte à une seule ligne en un champ à plusieurs lignes. |

### Voir également

* class [SaveableFacade](../saveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
