---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Exporta el contenido de los campos del pdf al flujo fdf
type: docs
weight: 70
url: /es/net/aspose.pdf.facades/form/exportfdf/
---
## Método Form.ExportFdf

Exporta el contenido de los campos del pdf al flujo fdf.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFdfStream | Stream | El flujo fdf de salida. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)