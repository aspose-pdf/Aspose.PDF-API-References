---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establecer la bandera de envío del botón de envío
type: docs
weight: 330
url: /es/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## Método FormEditor.SetSubmitFlag

Establecer la bandera de envío del botón de envío.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del botón de envío. |
| submitFormFlag | SubmitFormFlag | Bandera de envío. |

### Valor de Retorno

true si se encontró el campo y la bandera de envío se estableció correctamente.

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Ver También

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)