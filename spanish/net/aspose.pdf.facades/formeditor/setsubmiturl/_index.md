---
title: SetSubmitUrl
second_title: Referencia de API de Aspose.PDF para .NET
description: Establece la URL del botón.
type: docs
weight: 380
url: /es/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Establece la URL del botón.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | Enviar nombre del botón. |
| url | String | URL completamente calificada. |

### Valor_devuelto

true si la URL del botón se estableció correctamente.

### Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->