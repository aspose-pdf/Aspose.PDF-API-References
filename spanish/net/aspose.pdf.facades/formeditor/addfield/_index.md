---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Agregar campo del tipo especificado al formulario
type: docs
weight: 100
url: /es/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Agregar campo del tipo especificado al formulario.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldType | FieldType | Tipo del campo que debe ser agregado. |
| fieldName | String | Nombre del campo que debe ser agregado. |
| pageNum | Int32 | Número de página donde se debe colocar el nuevo campo. |
| llx | Single | Abscisa de la esquina inferior izquierda del campo. |
| lly | Single | Ordenada de la esquina inferior izquierda del campo. |
| urx | Single | Abscisa de la esquina superior derecha del campo. |
| ury | Single | Ordenada de la esquina superior derecha del campo. |

### Valor de Retorno

true si el campo fue agregado exitosamente.

## Ejemplos

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### Ver También

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Agregar campo del tipo especificado al formulario.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldType | FieldType | Tipo del campo que debe ser agregado. |
| fieldName | String | Nombre del campo que debe ser agregado. |
| initValue | String | Valor inicial del campo. |
| pageNum | Int32 | Número de página donde se debe colocar el nuevo campo. |
| llx | Single | Abscisa de la esquina inferior izquierda del campo. |
| lly | Single | Ordenada de la esquina inferior izquierda del campo. |
| urx | Single | Abscisa de la esquina superior derecha del campo. |
| ury | Single | Ordenada de la esquina superior derecha del campo. |

### Valor de Retorno

true si el campo fue agregado exitosamente.

## Ejemplos

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### Ver También

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)