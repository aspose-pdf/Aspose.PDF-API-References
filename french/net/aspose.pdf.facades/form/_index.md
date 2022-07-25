---
title: Form
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe représentant lobjet de formulaire Acro.
type: docs
weight: 2300
url: /fr/net/aspose.pdf.facades/form/
---
## Form class

Classe représentant l'objet de formulaire Acro.

```csharp
public sealed class Form : SaveableFacade
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Form](form#constructor)() | Constructeur de formulaire sans paramètres. |
| [Form](form#constructor_1)(Document) | Initialise nouveau[`Form`](../form) objet sur la base de la*document* . |
| [Form](form#constructor_4)(Stream) | Constructeur de formulaire. |
| [Form](form#constructor_8)(string) | Constructeur de formulaire. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/form/attachmentname) { get; set; } | Obtient ou définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [ContentDisposition](../../aspose.pdf.facades/form/contentdisposition) { get; set; } | Obtient ou définit la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. Valeur possible : en ligne / pièce jointe. Par défaut : en ligne. |
| [ConvertTo](../../aspose.pdf.facades/form/convertto) { set; } | Définit le format de fichier PDF. Le fichier de résultat sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtient la façade du document sur laquelle travaille. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames) { get; } | Obtient la liste des noms de champs sur le formulaire. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames) { get; } | Obtient tous les noms de bouton de soumission de formulaire. |
| [ImportResult](../../aspose.pdf.facades/form/importresult) { get; } | Résultat de la dernière opération d'importation. Tableau d'objets qui décrivent le résultat de l'import pour chaque champ. |
| [Response](../../aspose.pdf.facades/form/response) { get; set; } | Obtient ou définit l'objet de réponse où le résultat de l'opération sera stocké. |
| [SaveOptions](../../aspose.pdf.facades/form/saveoptions) { get; set; } | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |

## Méthodes

| Nom | La description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initialise la façade. |
| override [Close](../../aspose.pdf.facades/form/close)() | Ferme les fichiers ouverts sans aucune modification. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Dispose la façade. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf)(Stream) | Exporte le contenu des champs du pdf dans le flux fdf. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf)(Stream) | Exporte le contenu des champs du pdf dans le flux xml. La valeur du champ du bouton ne sera pas exportée. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml)(Stream) | Exporte le contenu des champs du pdf dans le flux xml. La valeur du champ du bouton ne sera pas exportée. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata)(Stream) | Extrait le paquet de données XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield)(string, string) | Remplissez un champ de code-barres en fonction de son nom de champ complet. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield)(string, bool) | Remplit le champ de la case à cocher avec une valeur booléenne. Remarque : ne s'applique qu'à la case à cocher. Veuillez noter qu'Aspose.Pdf.Facades ne prend en charge que les noms de champ complets et ne fonctionne pas avec les noms de champ partiels contrairement à Aspose.Pdf .Kit; Par exemple, si le champ a le nom complet "Form.Subform.CheckBoxField", vous devez spécifier le nom complet et non "CheckBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_1)(string, int) | Remplit le champ de la boîte radio avec une valeur d'index valide selon un nom de champ complet. Avant de remplir les champs, seul le nom du champ doit être connu. Bien que la valeur puisse être spécifiée par son index. Avis : ne s'applique qu'aux champs Radio Box, Combo Box et List Box. Veuillez noter qu'Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec les noms de champs partiels contrairement à Aspose.Pdf.Kit; Par exemple, si le champ a le nom complet "Form.Subform.ListBoxField", vous devez spécifier le nom complet et non "ListBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_2)(string, string) | Remplit le champ avec une valeur valide selon un nom de champ complet. Avant de remplir les champs, les noms de chaque champ et leurs valeurs valides correspondantes doivent être connus. Le nom et les valeurs des champs sont sensibles à la casse. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champ complets et ne fonctionne pas avec les noms de champ partiels contrairement à Aspose.Pdf.Kit; Par exemple, si le champ a le nom complet "Form.Subform.TextField", vous devez spécifier le nom complet et non "Champ de texte". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_4)(string, string[]) | Remplir un champ avec plusieurs sélections.Remarque : uniquement pour le champ de zone de liste AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield#fillfield_3)(string, string, bool) | Remplit le champ avec la valeur spécifiée. |
| [FillFields](../../aspose.pdf.facades/form/fillfields)(string[], string[], out Stream) | Remplit les champs de la zone de texte avec des valeurs de texte et enregistre le document. Pertinent pour les documents signés. Remarque : Ne s'applique qu'à la zone de texte. Le nom et les valeurs des champs sont sensibles à la casse. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield)(string, Stream) | Surcharge la fonction de FillImageField. L'entrée est un flux d'image. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield#fillimagefield_1)(string, string) | Colle une image sur le champ de bouton existant comme son apparence selon son nom de champ complet. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields)() | Aplatit tous les champs. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield)(string) | Aplatit un champ spécifié avec le nom de champ complet. Tout autre champ restera immuable. Si le fieldName est invalide, tous les champs resteront inchangeables. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue)(string) | Renvoie la valeur actuelle des champs d'option de bouton radio. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues)(string) | Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a une signification pour les groupes de boutons radio. |
| [GetField](../../aspose.pdf.facades/form/getfield)(string) | Obtient la valeur du champ en fonction de son nom de champ. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade)(string) | Renvoie l'objet FrofmFieldFacade contenant tous les attributs d'apparence. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag)(string) | Renvoie les drapeaux du champ. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit)(string) | Obtenez la limitation du champ de texte. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype)(string) | Renvoie le type de champ. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname)(string) | Obtient le nom complet du champ en fonction de son nom court. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext)(string) | Obtenir la valeur d'un champ de texte enrichi, y compris les informations de formatage de chaque caractère. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags)(string) | Renvoie les drapeaux de soumission du bouton de soumission |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf)(Stream) | Importe le contenu des champs du fichier fdf et les place dans le nouveau pdf. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf)(Stream) | Importe le contenu des champs du fichier xfdf(xml) et les place dans le nouveau pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml)(Stream) | Importe le contenu des champs du fichier xml et les place dans le nouveau pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml#importxml_1)(Stream, bool) | Importe le contenu des champs du fichier xml et les place dans le nouveau pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield)(string) | Détermine si le champ est obligatoire ou non. |
| [RenameField](../../aspose.pdf.facades/form/renamefield)(string, string) | Renomme un champ. Le champ AcroForm ou le champ XFA est OK. |
| override [Save](../../aspose.pdf.facades/form/save#save_1)(Stream) | Enregistre le document dans le flux spécifié. |
| override [Save](../../aspose.pdf.facades/form/save#save_2)(string) | Enregistre le document dans le fichier spécifié. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata)(Stream) | Remplace les données XFA par le paquet de données spécifié. Le paquet de données peut être extrait à l'aide de ExtractXfaData. |

## Autres membres

| Nom | La description |
| --- | --- |
| class [FormImportResult](form.formimportresult) | Classe qui décrit le résultat si le champ est importé. |
| enum [ImportStatus](form.importstatus) | Statut du champ importé |

### Voir également

* class [SaveableFacade](../saveablefacade)
* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
