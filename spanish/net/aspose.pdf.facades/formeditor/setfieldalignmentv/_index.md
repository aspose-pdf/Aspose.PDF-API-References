---
title: SetFieldAlignmentV
second_title: Referencia de API de Aspose.PDF para .NET
description: Establecer el estilo de alineación vertical de un campo de texto.
type: docs
weight: 310
url: /es/net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

Establecer el estilo de alineación vertical de un campo de texto.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo calificado. |
| alignment | Int32 | La definición del estilo de alineación, incluidos FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle y FormFieldFacade.AlignRight. |

### Valor_devuelto

verdadero si se encontró el campo y la alineación se llenó correctamente.

### Ejemplos

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
