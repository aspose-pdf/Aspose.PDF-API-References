---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: Método de campo. Exporta el contenido del campo especificado a un flujo JSON. Los valores de los campos de botón no se exportan.
type: docs
weight: 180
url: /es/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Método Field.ExportValueToJson

Exporta el contenido del campo especificado a un flujo JSON. Los valores de los campos de botón no se exportan.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputJsonStream | Stream | El flujo JSON de salida donde se escribirán los datos del campo. |
| indented | Boolean | Opcional. Especifica si la salida JSON debe estar indentada para una mejor legibilidad. El valor predeterminado es verdadero. |

## Ejemplos

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Ver También

* clase [Field](../)
* espacio de nombres [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* ensamblaje [Aspose.PDF](../../../)