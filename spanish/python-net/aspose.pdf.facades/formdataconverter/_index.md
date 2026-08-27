---
title: "FormDataConverter"
second_title: "Referencia de API de Aspose.PDF para Python vía .NET"
description: "Representa una clase para convertir datos de un formato a otro.<br/>            Puede convertir los datos en fdf/xml/pdf/xfdf al OLEDB/OdbcDB.<br/>            También puede convertir los datos en el OLEDB/OdbcDB a los datos en fdf/xml/xfdf.<br/>            Puede convertir el fdf al xml con la etiqueta \"hard-named\"."
type: docs
weight: 100
url: /es/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Representa una clase para convertir datos de un formato a otro.<br/>            Puede convertir los datos en fdf/xml/pdf/xfdf al OLEDB/OdbcDB.<br/>            También puede convertir los datos en el OLEDB/OdbcDB a los datos en fdf/xml/xfdf.<br/>            Puede convertir el fdf al xml con la etiqueta "hard-named".

El tipo FormDataConverter expone los siguientes miembros:
## Constructores
| Nombre | Descripción |
| :- | :- |
| FormDataConverter() | Inicializa una nueva instancia de la clase FormDataConverter |
## Propiedades
| Nombre | Descripción |
| :- | :- |
| create_missing_field | ConvertToDataTable creará el campo requerido si no existe en la tabla. |
| replace_existing_table | ImportIntoDatabase eliminará la tabla existente y creará una nueva tabla si esta propiedad está establecida en verdadero. |
| clear_table_before_export | ExportFromData limpiará la tabla antes de la exportación de datos. |
| create_missing_table | ImportIntoDatabase creará la tabla si no existe. |
## Métodos
| Nombre | Descripción |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | Convertir archivo XML de importación/exportación de datos de formulario al formato FDF. |
| convert_fdf_to_xml(source_fdf, dest_xml) | Convertir archivo FDF a XML. |
| convert_to_data_table(source_streams, source_type) | Convertir archivos de flujos en tabla. |
| import_into_data_base(connect_string, db_type) | Importa datos de la tabla a la base de datos. |
| export_from_data_base(connect_string, db_type) | Exporta datos de la base de datos a la tabla. |
| convert_to_streams(dest_stream, dest_type) | Convertir datos en tabla en flujos. |
| conver_to_streams(dest_stream, dest_type) | Este método está obsoleto. Por favor, use ConvertToStreams() en su lugar. |

### Ver también

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

