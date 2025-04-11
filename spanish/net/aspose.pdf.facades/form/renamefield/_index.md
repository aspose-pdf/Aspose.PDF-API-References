---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Cambia el nombre de un campo. Ya sea un campo de AcroForm o un campo de XFA está bien.
type: docs
weight: 330
url: /es/net/aspose.pdf.facades/form/renamefield/
---
## Método Form.RenameField

Cambia el nombre de un campo. Ya sea un campo de AcroForm o un campo de XFA está bien.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | el antiguo nombre del campo |
| newFieldName | String | el nuevo nombre del campo |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)