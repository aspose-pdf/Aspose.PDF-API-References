---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Agregar botón de envío en el formulario
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## Método FormEditor.AddSubmitBtn

Agregar botón de envío en el formulario.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del nuevo botón. |
| page | Int32 | Página donde se colocará el botón. |
| label | String | Texto del botón. |
| url | String | URL del botón de envío. |
| llx | Single | Abscisa de la esquina inferior izquierda. |
| lly | Single | Ordenada de la esquina inferior izquierda. |
| urx | Single | Abscisa de la esquina superior derecha. |
| ury | Single | Ordenada de la esquina superior derecha. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)