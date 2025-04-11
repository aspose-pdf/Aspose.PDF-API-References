---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Cambiar un campo de texto de una sola línea a uno de múltiples líneas
type: docs
weight: 350
url: /es/net/aspose.pdf.facades/formeditor/single2multiple/
---
## Método FormEditor.Single2Multiple

Cambia un campo de texto de una sola línea a uno de múltiples líneas.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo calificado. |

### Valor de Retorno

Si tiene éxito, devuelve true; de lo contrario, false.

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)