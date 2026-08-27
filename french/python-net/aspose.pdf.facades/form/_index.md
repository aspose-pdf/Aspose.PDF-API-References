---
title: "Form"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Classe représentant l'objet de formulaire Acro."
type: docs
weight: 80
url: /fr/python-net/aspose.pdf.facades/form/
---

## Form class

Classe représentant l'objet de formulaire Acro.

Le type Form expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| Form(src_stream, dest_stream) | Initialise une nouvelle instance de la classe Form |
| Form() | Constructeur de Form sans paramètres. |
| Form(src_file_name) | Initialise une nouvelle instance de la classe Form |
| Form(src_stream) | Initialise une nouvelle instance de la classe Form |
| Form(src_file_name, dest_file_name) | Initialise une nouvelle instance de la classe Form |
| Form(src_file_name, dest_stream) | Initialise une nouvelle instance de la classe Form |
| Form(src_stream, dest_file_name) | Initialise une nouvelle instance de la classe Form |
| Form(document) | Initialise une nouvelle instance de la classe Form |
| Form(document, dest_file_name) | Initialise une nouvelle instance de la classe Form |
| Form(document, dest_stream) | Initialise une nouvelle instance de la classe Form |
## Propriétés
| Nom | Description |
| :- | :- |
| document | Obtient la façade du document sur laquelle il travaille. |
| import_result | Résultat de la dernière opération d'importation. Tableau d'objets décrivant le résultat de l'importation pour chaque champ. |
| src_file_name | Obtient ou définit le nom du fichier source. |
| dest_file_name | Obtient ou définit le nom du fichier de destination. |
| src_stream | Obtient ou définit le flux source. |
| dest_stream | Obtient ou définit le flux de destination. |
| field_names | Obtient la liste des noms de champs du formulaire. |
| form_submit_button_names | Obtient tous les noms des boutons de soumission du formulaire. |
## Méthodes
| Nom | Description |
| :- | :- |
| bind_pdf(src_file) | Lie le document PDF pour l'édition. |
| bind_pdf(src_stream) | Lie le document PDF pour l'édition. |
| bind_pdf(src_doc) | Lie le document PDF pour l'édition. |
| save() | Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. |
| save(dest_file) | Enregistre le document dans le fichier spécifié. |
| save(dest_stream) | Enregistre le document dans le flux spécifié. |
| fill_field(field_name, field_value) | Remplit le champ avec une valeur valide selon un nom de champ pleinement qualifié.<br/> Avant de remplir les champs, les noms de tous les champs et leurs valeurs valides correspondantes doivent être connus.<br/> Le nom et les valeurs des champs sont sensibles à la casse.<br/> Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms partiels <br/> contrairement à Aspose.Pdf.Kit;<br/> Par exemple, si le champ a le nom complet \"Form.Subform.TextField\", vous devez spécifier le nom complet et non \"TextField\". <br/> Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| fill_field(field_name, index) | Remplit le champ de boîte radio avec une valeur d'index valide selon un nom de champ pleinement qualifié.<br/> Avant de remplir les champs, seul le nom du champ doit être connu. La valeur peut être spécifiée par son index.<br/> Remarque : applicable uniquement aux champs Boîte radio, Boîte combinée et Boîte de liste.<br/> Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms partiels <br/> contrairement à Aspose.Pdf.Kit;<br/> Par exemple, si le champ a le nom complet \"Form.Subform.ListBoxField\", vous devez spécifier le nom complet et non \"ListBoxField\". <br/> Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| fill_field(field_name, be_checked) | Remplit le champ de case à cocher avec une valeur booléenne.<br/> Remarque : applicable uniquement à la case à cocher.<br/> Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms partiels <br/> contrairement à Aspose.Pdf.Kit;<br/> Par exemple, si le champ a le nom complet \"Form.Subform.CheckBoxField\", vous devez spécifier le nom complet et non \"CheckBoxField\". <br/> Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| fill_field(field_name, field_values) | Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document.<br/> Pertinent pour les documents signés.<br/> Remarque : applicable uniquement aux zones de texte.<br/> Le nom et les valeurs des champs sont sensibles à la casse. |
| fill_field(field_name, value, fit_font_size) | Remplit le champ de case à cocher avec une valeur booléenne.<br/> Remarque : applicable uniquement à la case à cocher.<br/> Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms partiels <br/> contrairement à Aspose.Pdf.Kit;<br/> Par exemple, si le champ a le nom complet \"Form.Subform.CheckBoxField\", vous devez spécifier le nom complet et non \"CheckBoxField\". <br/> Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. |
| import_xml(input_xml_stream) | Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. |
| import_xml(input_xml_stream, ignore_form_template_changes) | Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. |
| fill_image_field(field_name, image_file_name) | Colle une image sur le champ bouton existant comme son apparence selon <br/> son nom de champ pleinement qualifié. |
| fill_image_field(field_name, image_stream) | Surcharge la fonction de FillImageField.<br/>            L'entrée est un flux d'image. |
| close() | Ferme les fichiers ouverts sans aucune modification. |
| get_field_facade(field_name) | Renvoie l'objet FrogmFieldFacade contenant tous les attributs d'apparence. |
| fill_fields(field_names, field_values, output) | Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document.<br/> Pertinent pour les documents signés.<br/> Remarque : applicable uniquement aux zones de texte.<br/> Le nom et les valeurs des champs sont sensibles à la casse. |
| get_button_option_current_value(field_name) | Renvoie la valeur actuelle des champs d'option de bouton radio. |
| get_field(field_name) | Renvoie l'objet FrogmFieldFacade contenant tous les attributs d'apparence. |
| get_full_field_name(field_name) | Obtient le nom complet du champ selon son nom court. |
| get_field_limit(field_name) | Obtenez la limitation du champ texte. |
| flatten_all_fields() | Aplatisse tous les champs. |
| flatten_field(field_name) | Aplatisse un champ spécifié avec le nom de champ pleinement qualifié.<br/>            Tout autre champ restera inchangé. Si le fieldName est invalide, <br/>            tous les champs resteront inchangés. |
| fill_barcode_field(field_name, data) | Remplit un champ code-barres selon son nom de champ pleinement qualifié. |
| import_fdf(input_fdf_stream) | Importe le contenu des champs du fichier fdf et les place dans le nouveau PDF. |
| export_fdf(output_fdf_stream) | Exporte le contenu des champs du PDF vers le flux fdf. |
| export_xml(output_xml_stream) | Exporte le contenu des champs du PDF vers le flux XML.<br/>            La valeur du champ bouton ne sera pas exportée. |
| extract_xfa_data(output_xml_stream) | Extrait le paquet de données XFA |
| set_xfa_data(input_xml_stream) | Remplace les données XFA par le paquet de données spécifié. Le paquet de données peut être extrait en utilisant ExtractXfaData. |
| import_xfdf(input_xfdf_stream) | Importe le contenu des champs du fichier xfdf(xml) et les place dans le nouveau pdf. |
| export_xfdf(output_xfdf_stream) | Exporte le contenu des champs du PDF vers le flux XML.<br/>            La valeur du champ bouton ne sera pas exportée. |
| rename_field(field_name, new_field_name) | Renomme un champ. Un champ AcroForm ou XFA convient. |
| get_rich_text(field_name) | Obtient la valeur d'un champ de texte enrichi, y compris les informations de formatage de chaque caractère. |
| get_submit_flags(field_name) | Renvoie les indicateurs de soumission du bouton d'envoi |
| get_field_type(field_name) | Renvoie le type du champ. |
| is_required_field(field_name) | Détermine si le champ est obligatoire ou non. |
| get_field_flag(field_name) | Renvoie les indicateurs du champ. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

