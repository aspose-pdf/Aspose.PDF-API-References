---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Exporta el contenido de los campos del pdf al flujo xml. El valor de los campos de botón no será exportado
type: docs
weight: 90
url: /es/net/aspose.pdf.facades/form/exportxfdf/
---
## Método Form.ExportXfdf

Exporta el contenido de los campos del pdf al flujo xml. El valor del campo de botón no será exportado.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputXfdfStream | Stream | El flujo xml de salida. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)