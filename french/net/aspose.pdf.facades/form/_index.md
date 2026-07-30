---
title: "Classe Form"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Facades.Form class. Classe représentant l'objet de formulaire Acro"
type: docs
weight: 4410
url: /fr/net/aspose.pdf.facades/form/
---
## Form class

Classe représentant l'objet de formulaire Acro.

```csharp
public sealed class Form : SaveableFacade
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Form](form/#constructor)() | Constructeur de Form sans paramètres. |
| [Form](form/#constructor_1)(Document) | Initialise un nouvel objet `Form` sur la base du *document*. |
| [Form](form/#constructor_4)(Stream) | Constructeur pour le formulaire. |
| [Form](form/#constructor_7)(string) | Constructeur de Form. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Définit le format du fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtient la façade du document sur laquelle travaille. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Obtient la liste des noms de champs du formulaire. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Obtient tous les noms des boutons de soumission du formulaire. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Résultat de la dernière opération d'importation. Tableau d'objets décrivant le résultat de l'importation pour chaque champ. |

## Méthodes

| Nom | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initialise la façade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initialise la façade. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Ferme les fichiers ouverts sans aucune modification. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Libère la façade. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Exporte le contenu des champs du pdf vers le flux fdf. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Exporte le contenu de tous les champs du document vers un flux JSON. Les valeurs des champs bouton ne sont pas exportées. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Exporte le contenu des champs du pdf vers le flux xml. La valeur du champ bouton ne sera pas exportée. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Exporte le contenu des champs du pdf vers le flux xml. La valeur du champ bouton ne sera pas exportée. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Extrait le paquet de données XFA |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Remplit un champ de code-barres selon son nom de champ entièrement qualifié. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Remplit le champ case à cocher avec une valeur booléenne. Remarque : applicable uniquement aux cases à cocher. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.CheckBoxField", vous devez spécifier le nom complet et non "CheckBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Remplit le champ boîte radio avec une valeur d'index valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, seul le nom du champ doit être connu. La valeur peut être spécifiée par son index. Remarque : applicable uniquement aux champs Boîte radio, Boîte combinée et Boîte de liste. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.ListBoxField", vous devez spécifier le nom complet et non "ListBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, le nom de chaque champ et ses valeurs valides correspondantes doivent être connus. Les noms et les valeurs des champs sont sensibles à la casse. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.TextField", vous devez spécifier le nom complet et non "TextField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Remplit un champ avec plusieurs sélections. Remarque : uniquement pour le champ Boîte de liste AcroForm. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Remplit le champ avec la valeur spécifiée. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document. Pertinent pour les documents signés. Remarque : applicable uniquement aux zones de texte. Les noms et les valeurs des champs sont sensibles à la casse. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Surcharge la fonction FillImageField. L'entrée est un flux d'image. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Aplatisse tous les champs. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Aplatisse un champ spécifié avec le nom de champ entièrement qualifié. Tout autre champ restera inchangé. Si le fieldName est invalide, tous les champs resteront inchangés. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Renvoie la valeur actuelle des champs d'option de bouton radio. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a une utilité pour les groupes de boutons radio. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Obtient la valeur du champ selon son nom de champ. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Renvoie l'objet FrofmFieldFacade contenant tous les attributs d'apparence. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Renvoie les indicateurs du champ. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Obtient la limitation du champ texte. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Renvoie le type du champ. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Obtient le nom complet du champ selon son nom court. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Obtient la valeur d'un champ de texte enrichi, incluant les informations de formatage de chaque caractère. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Renvoie les indicateurs de soumission du bouton d'envoi |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Importe le contenu des champs du fichier fdf et les place dans le nouveau pdf. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Importe toutes les données de champ d'un flux JSON dans les champs du document, en faisant correspondre les champs par leurs noms complets. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Importe le contenu des champs du fichier xfdf(xml) et les place dans le nouveau pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Importe le contenu des champs du fichier xml et les place dans le nouveau pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Importe le contenu des champs du fichier xml et les place dans le nouveau pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Détermine si le champ est requis ou non. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Renomme un champ. Un champ AcroForm ou XFA convient. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Enregistre le document dans le flux spécifié. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Enregistre le document dans le fichier spécifié. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Remplace les données XFA par le paquet de données spécifié. Le paquet de données peut être extrait en utilisant ExtractXfaData. |

## Autres membres

| Nom | Description |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Classe qui décrit le résultat de l'importation de champ. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Statut du champ importé |

### Voir aussi

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


