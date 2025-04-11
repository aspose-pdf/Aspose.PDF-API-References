---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Aplana un campo especificado con el nombre de campo completamente calificado. Cualquier otro campo permanecerá inalterable. Si el fieldName es inválido, todos los campos permanecerán inalterables.
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/form/flattenfield/
---
## Método Form.FlattenField

Aplana un campo especificado con el nombre de campo completamente calificado. Cualquier otro campo permanecerá inalterable. Si el fieldName es inválido, todos los campos permanecerán inalterables.

```csharp
public void FlattenField(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo que se va a aplanar. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Véase también

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)