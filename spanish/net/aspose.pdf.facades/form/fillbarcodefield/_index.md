---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Rellena un campo de código de barras según su nombre de campo completamente calificado
type: docs
weight: 120
url: /es/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Método Form.FillBarcodeField

Rellena un campo de código de barras según su nombre de campo completamente calificado.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo completamente calificado. |
| data | String | El nuevo valor del código de barras. |

### Valor de retorno

Si el llenado tiene éxito, devuelve verdadero; de lo contrario, falso.

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Ver también

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)