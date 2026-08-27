---
title: "Classe FormDataConverter"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Facades.FormDataConverter. Représente une classe permettant de convertir des données d'un format à un autre format. Elle peut convertir les données au format fdf/xml/pdf/xfdf vers OLEDB/OdbcDB. Elle peut également convertir les données d'OLEDB/OdbcDB vers le format fdf/xml/xfdf. Elle peut convertir le fdf en xml avec une balise à nom fixe."
type: docs
weight: 4440
url: /fr/net/aspose.pdf.facades/formdataconverter/
---
## FormDataConverter class

Représente une classe permettant de convertir des données d'un format à un autre. Elle peut convertir les données au format fdf/xml/pdf/xfdf vers OLEDB/OdbcDB. Elle peut également convertir les données d'OLEDB/OdbcDB vers le format fdf/xml/xfdf. Elle peut convertir le fdf en xml avec la balise "hard-named".

```csharp
public sealed class FormDataConverter
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData effacera la table avant l'exportation des données. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable créera le champ requis s'il n'existe pas dans la Table. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase créera la table si elle n'existe pas. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase supprimera la table existante et créera une nouvelle table si cette propriété est définie sur true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Obtient ou définit le conteneur de données intermédiaire, un DataTable. Il doit être défini avant de convertir des données d'un format à un autre format. Les Columns et le TableName du DataTable doivent être définis. Le TableName est le nom de la Table dans la base de données. Le ColumnName de chaque colonne est le nom de champ qualifié du pdf. La Caption de chaque colonne est le nom de la colonne de la table dans la base de données. Si le nom du champ est identique au nom de la colonne de la table, la Caption n'a pas besoin d'être spécifiée. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Cette méthode est obsolète. Veuillez utiliser ConvertToStreams() à la place. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Convertir les fichiers de flux en table. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Convertir les données de la table en flux. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Exporte les données de la base de données vers la table. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importe les données de la table vers la base de données. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Convertir le fichier FDF en XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Convertir le fichier de données de formulaire XML d'import/export au format FDF. |

### Voir aussi

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


