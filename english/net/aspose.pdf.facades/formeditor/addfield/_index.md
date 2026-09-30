---
title: "FormEditor.AddField"
linktitle: "AddField"
articleTitle: "AddField"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Add field of specified type to the form."
type: docs
weight: 110
url: "/net/aspose.pdf.facades/formeditor/addfield/"
product_version: "26.9.0"
---
## AddField([FieldType](../../../aspose.pdf.facades/fieldtype/), string, int, float, float, float, float) {#addfield}

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

### See Also

* enum [FieldType](../../../aspose.pdf.facades/fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField([FieldType](../../../aspose.pdf.facades/fieldtype/), string, string, int, float, float, float, float) {#addfield_1}

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

### See Also

* enum [FieldType](../../../aspose.pdf.facades/fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

