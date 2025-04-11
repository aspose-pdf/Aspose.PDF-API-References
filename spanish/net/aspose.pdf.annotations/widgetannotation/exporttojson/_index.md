---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Método WidgetAnnotation. Exporta el campo de formulario PDF especificado a formato JSON y escribe el resultado en el flujo proporcionado
type: docs
weight: 120
url: /es/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporta el campo de formulario PDF especificado a formato JSON y escribe el resultado en el flujo proporcionado.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo en el que se escribirá la salida JSON. |
| options | ExportFieldsToJsonOptions | Configuraciones opcionales para exportar el campo de formulario a JSON. |

### Valor de Retorno

Una colección de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) que indica el resultado de la operación de exportación para el campo de formulario especificado y sus elementos secundarios, si están presentes.

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### Véase También

* clase [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* clase [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* clase [WidgetAnnotation](../)
* espacio de nombres [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* ensamblado [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporta el campo de formulario PDF especificado a formato JSON y escribe el resultado en el archivo especificado.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | El nombre del archivo en el que se escribirá la salida JSON. |
| options | ExportFieldsToJsonOptions | Configuraciones opcionales para exportar el campo de formulario a JSON. |

### Valor de Retorno

Una colección de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) que indica el resultado de la operación de exportación para el campo de formulario especificado y sus elementos secundarios, si están presentes.

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Véase También

* clase [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* clase [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* clase [WidgetAnnotation](../)
* espacio de nombres [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* ensamblado [Aspose.PDF](../../../)