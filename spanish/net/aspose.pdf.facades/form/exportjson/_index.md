---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Exporta el contenido de todos los campos en el documento a un flujo JSON. Los valores de los campos de botón no se exportan
type: docs
weight: 80
url: /es/net/aspose.pdf.facades/form/exportjson/
---
## Método Form.ExportJson

Exporta el contenido de todos los campos en el documento a un flujo JSON. Los valores de los campos de botón no se exportan.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputJsonStream | Stream | El flujo JSON de salida donde se escribirán los datos de los campos del documento. |
| indented | Boolean | Opcional. Especifica si la salida JSON debe estar indentada para una mejor legibilidad. El valor predeterminado es verdadero. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Véase también

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)