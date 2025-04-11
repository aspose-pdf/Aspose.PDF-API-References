---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Propiedad del formulario. Obtiene la lista de nombres de campos en el formulario
type: docs
weight: 30
url: /es/net/aspose.pdf.facades/form/fieldnames/
---
## Propiedad Form.FieldNames

Obtiene la lista de nombres de campos en el formulario.

```csharp
public string[] FieldNames { get; }
```

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)