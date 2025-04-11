---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establece la URL del botón
type: docs
weight: 340
url: /es/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## Método FormEditor.SetSubmitUrl

Establece la URL del botón.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del botón de envío. |
| url | String | URL completamente calificada. |

### Valor de Retorno

true si la URL del botón se estableció correctamente.

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)