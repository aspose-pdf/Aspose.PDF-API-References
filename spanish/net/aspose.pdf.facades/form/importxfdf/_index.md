---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Importa el contenido de los campos del archivo xfdfxml y los coloca en el nuevo pdf
type: docs
weight: 300
url: /es/net/aspose.pdf.facades/form/importxfdf/
---
## Método Form.ImportXfdf

Importa el contenido de los campos del archivo xfdf(xml) y los coloca en el nuevo pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputXfdfStream | Stream | El flujo xfdf(xml) de entrada. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)