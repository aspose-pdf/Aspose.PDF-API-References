---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establecer el estilo de alineación de un campo de texto
type: docs
weight: 260
url: /es/net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## Método FormEditor.SetFieldAlignment

Establecer el estilo de alineación de un campo de texto.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo calificado. |
| alignment | Int32 | La definición del estilo de alineación, incluyendo FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter y FormFieldFacade.AlignRight. |

### Valor de Retorno

true si se encontró el campo y se estableció la alineación.

## Ejemplos

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)