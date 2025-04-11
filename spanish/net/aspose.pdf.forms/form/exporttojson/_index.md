---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Exporta los campos del formulario PDF a formato JSON y escribe el resultado en el flujo proporcionado
type: docs
weight: 240
url: /es/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporta los campos del formulario PDF a formato JSON y escribe el resultado en el flujo proporcionado.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo en el que se escribirá la salida JSON. |
| options | ExportFieldsToJsonOptions | Configuraciones opcionales para exportar los campos del formulario a JSON. |

### Valor de Retorno

Una colección de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) que indica el resultado de la operación de exportación para cada campo del formulario.

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Véase También

* clase [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* clase [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporta los campos del formulario PDF a formato JSON y escribe el resultado en el archivo especificado.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | El nombre del archivo en el que se escribirá la salida JSON. |
| options | ExportFieldsToJsonOptions | Configuraciones opcionales para exportar los campos del formulario a JSON. |

### Valor de Retorno

Una colección de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) que indica el resultado de la operación de exportación para cada campo del formulario.

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Véase También

* clase [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* clase [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblado [Aspose.PDF](../../../)