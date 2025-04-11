---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Exporta el contenido de los campos del pdf al flujo xml. El valor de los campos de botón no será exportado
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/form/exportxml/
---
## Método Form.ExportXml

Exporta el contenido de los campos del pdf al flujo xml. El valor del campo de botón no será exportado.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputXmlStream | Stream | Flujo Xml de salida. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)