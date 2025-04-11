---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf
type: docs
weight: 280
url: /es/net/aspose.pdf.facades/form/importfdf/
---
## Método Form.ImportFdf

Importa el contenido de los campos del archivo fdf y los coloca en el nuevo pdf.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFdfStream | Stream | El flujo fdf de entrada. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)