---
title: "FormDataConverter"
second_title: "Référence de l'API Aspose.PDF pour Python via .NET"
description: "Représente une classe permettant de convertir des données d'un format à un autre.<br/>            Elle peut convertir les données au format fdf/xml/pdf/xfdf vers OLEDB/OdbcDB.<br/>            Elle peut également convertir les données d'OLEDB/OdbcDB vers fdf/xml/xfdf.<br/>            Elle peut convertir le fdf en xml avec une balise \\\"hard-named\\\"."
type: docs
weight: 100
url: /fr/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Représente une classe permettant de convertir des données d'un format à un autre.<br/>            Elle peut convertir les données au format fdf/xml/pdf/xfdf vers OLEDB/OdbcDB.<br/>            Elle peut également convertir les données d'OLEDB/OdbcDB vers fdf/xml/xfdf.<br/>            Elle peut convertir le fdf en xml avec une balise \"hard-named\".

Le type FormDataConverter expose les membres suivants :
## Constructeurs
| Nom | Description |
| :- | :- |
| FormDataConverter() | Initialise une nouvelle instance de la classe FormDataConverter |
## Propriétés
| Nom | Description |
| :- | :- |
| create_missing_field | ConvertToDataTable créera le champ requis s'il n'existe pas dans la table. |
| replace_existing_table | ImportIntoDatabase supprimera la table existante et créera une nouvelle table si cette propriété est définie sur true. |
| clear_table_before_export | ExportFromData effacera la table avant l'exportation des données. |
| create_missing_table | ImportIntoDatabase créera la table si elle n'existe pas. |
## Méthodes
| Nom | Description |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | Convertit le fichier de données de formulaire XML d'import/export au format FDF. |
| convert_fdf_to_xml(source_fdf, dest_xml) | Convertit le fichier FDF en XML. |
| convert_to_data_table(source_streams, source_type) | Convertit les fichiers de flux en tableau. |
| import_into_data_base(connect_string, db_type) | Importe les données de la table dans la base de données. |
| export_from_data_base(connect_string, db_type) | Exporte les données de la base de données vers la table. |
| convert_to_streams(dest_stream, dest_type) | Convertir les données du tableau en flux. |
| conver_to_streams(dest_stream, dest_type) | Cette méthode est obsolète. Veuillez utiliser ConvertToStreams() à la place. |

### Voir aussi

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

