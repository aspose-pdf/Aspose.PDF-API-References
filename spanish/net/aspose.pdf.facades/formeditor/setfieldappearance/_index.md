---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establecer banderas de campo
type: docs
weight: 280
url: /es/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## Método FormEditor.SetFieldAppearance

Establecer banderas de campo

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo cuyas banderas deben ser actualizadas. |
| flags | AnnotationFlags | Bandera del campo. |

### Valor de Retorno

true si las banderas fueron actualizadas con éxito.

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### Ver También

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)