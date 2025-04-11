---
title: Class FormDataConverter
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Facades.FormDataConverter. Representa una clase para convertir datos de un formato a otro. Puede convertir los datos en fdf/xml/pdf/xfdf a OLEDB/OdbcDB. También puede convertir los datos en OLEDB/OdbcDB a los datos en fdf/xml/xfdf. Puede convertir el fdf a xml con una etiqueta "hard-named".
type: docs
weight: 4320
url: /es/net/aspose.pdf.facades/formdataconverter/
---
## Clase FormDataConverter

Representa una clase para convertir datos de un formato a otro. Puede convertir los datos en fdf/xml/pdf/xfdf a OLEDB/OdbcDB. También puede convertir los datos en OLEDB/OdbcDB a los datos en fdf/xml/xfdf. Puede convertir el fdf a xml con una etiqueta "hard-named".

```csharp
public sealed class FormDataConverter
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [FormDataConverter](formdataconverter/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ClearTableBeforeExport](../../aspose.pdf.facades/formdataconverter/cleartablebeforeexport/) { get; set; } | ExportFromData limpiará la tabla antes de la exportación de datos. |
| [CreateMissingField](../../aspose.pdf.facades/formdataconverter/createmissingfield/) { get; set; } | ConvertToDataTable creará el campo requerido si no existe en la tabla. |
| [CreateMissingTable](../../aspose.pdf.facades/formdataconverter/createmissingtable/) { get; set; } | ImportIntoDatabase creará la tabla si no existe. |
| [ReplaceExistingTable](../../aspose.pdf.facades/formdataconverter/replaceexistingtable/) { get; set; } | ImportIntoDatabase eliminará la tabla existente y creará una nueva tabla si esta propiedad está establecida en verdadero. |
| [Table](../../aspose.pdf.facades/formdataconverter/table/) { get; set; } | Obtiene o establece el contenedor de datos intermedio, una DataTable. Debe definirse antes de convertir datos de un formato a otro. Las columnas y el nombre de la tabla de la DataTable deben definirse. El TableName es el nombre de la tabla en la base de datos. El ColumnName de cada columna es el nombre de campo calificado del pdf. El Caption de cada columna es el nombre de la columna de la tabla en la base de datos. Si el nombre del campo es el mismo que el nombre de la columna de la tabla, no es necesario especificar el Caption. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ConverToStreams](../../aspose.pdf.facades/formdataconverter/convertostreams/)(Stream[], DataType) | Este método está obsoleto. Por favor, use ConvertToStreams() en su lugar. |
| [ConvertToDataTable](../../aspose.pdf.facades/formdataconverter/converttodatatable/)(Stream[], DataType) | Convierte archivos de flujos en una tabla. |
| [ConvertToStreams](../../aspose.pdf.facades/formdataconverter/converttostreams/)(Stream[], DataType) | Convierte datos en la tabla en flujos. |
| [ExportFromDataBase](../../aspose.pdf.facades/formdataconverter/exportfromdatabase/)(string, DataType) | Exporta datos de la base de datos a la tabla. |
| [ImportIntoDataBase](../../aspose.pdf.facades/formdataconverter/importintodatabase/)(string, DataType) | Importa datos de la tabla a la base de datos. |
| static [ConvertFdfToXml](../../aspose.pdf.facades/formdataconverter/convertfdftoxml/)(Stream, Stream) | Convierte un archivo FDF en XML. |
| static [ConvertXmlToFdf](../../aspose.pdf.facades/formdataconverter/convertxmltofdf/)(Stream, Stream) | Convierte un archivo de datos de formulario XML de importación/exportación en formato FDF. |

### Véase también

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)