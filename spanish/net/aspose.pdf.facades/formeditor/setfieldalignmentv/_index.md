---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establecer el estilo de alineación vertical de un campo de texto
type: docs
weight: 270
url: /es/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## Método FormEditor.SetFieldAlignmentV

Establecer el estilo de alineación vertical de un campo de texto.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo calificado. |
| alignment | Int32 | La definición del estilo de alineación, incluyendo FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle y FormFieldFacade.AlignRight. |

### Valor de Retorno

true si se encontró el campo y la alineación se completó con éxito.

## Ejemplos

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)