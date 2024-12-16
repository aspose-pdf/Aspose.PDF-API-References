---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Add field of specified type to the form
type: docs
weight: 100
url: /net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Add field of specified type to the form.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Type of the field which must be added. |
| fieldName | String | Name of the field whic must be added. |
| pageNum | Int32 | Page number where new field must be placed. |
| llx | Single | Abscissa of the lower-left corner of the field. |
| lly | Single | Ordinate of the lower-left corner of the field. |
| urx | Single | Abscissa of the upper-right corner of the field. |
| ury | Single | Ordinate of the upper-right corner of the field. |

### Return Value

true if field was successfully added.

## Examples

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### See Also

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Add field of specified type to the form.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Type of the field which must be added. |
| fieldName | String | Name of the field whic must be added. |
| initValue | String | Initial value of the field. |
| pageNum | Int32 | Page number where new field must be placed. |
| llx | Single | Abscissa of the lower-left corner of the field. |
| lly | Single | Ordinate of the lower-left corner of the field. |
| urx | Single | Abscissa of the upper-right corner of the field. |
| ury | Single | Ordinate of the upper-right corner of the field. |

### Return Value

true if field was successfully added.

## Examples

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### See Also

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


