---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.FormDataConverter. Représente une classe pour convertir des données d'un format à un autre format. Elle peut convertir les données en fdf/xml/pdf/xfdf vers OLEDB/OdbcDB. Elle peut également convertir les données de OLEDB/OdbcDB vers les données en fdf/xml/xfdf. Elle peut convertir le fdf en xml avec un tag "hard-named".
type: docs
weight: 4320
url: /fr/net/aspose.pdf.facades/formdataconverter/
---
## Classe FormDataConverter

Représente une classe pour convertir des données d'un format à un autre format. Elle peut convertir les données en fdf/xml/pdf/xfdf vers OLEDB/OdbcDB. Elle peut également convertir les données de OLEDB/OdbcDB vers les données en fdf/xml/xfdf. Elle peut convertir le fdf en xml avec un tag "hard-named".

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
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData va vider la table avant l'exportation des données. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable va créer le champ requis s'il n'existe pas dans la table. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase va créer la table si elle n'existe pas. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase va supprimer la table existante et créer une nouvelle table si cette propriété est définie sur true. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Obtient ou définit le conteneur de données intermédiaire, une DataTable. Elle doit être définie avant de convertir des données d'un format à un autre format. Les colonnes et le nom de la table de la DataTable doivent être définis. Le TableName est le nom de la table dans la base de données. Chaque ColumnName de colonne est le nom de champ qualifié du pdf. Chaque Caption de colonne est le nom de la colonne de la table dans la base de données. Si le nom du champ est le même que le nom de la colonne de la table, le Caption n'a pas besoin d'être spécifié. |

## Méthodes

| Nom | Description |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Cette méthode est obsolète. Veuillez utiliser ConvertToStreams() à la place. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Convertit des fichiers de flux en table. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Convertit des données dans la table en flux. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Exporte des données de la base de données vers la table. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importe des données de la table vers la base de données. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Convertit un fichier FDF en XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Convertit un fichier de données de formulaire XML d'import/export en format FDF. |

### Voir aussi

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)