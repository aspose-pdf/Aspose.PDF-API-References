---
title: "Form.HasField"
linktitle: "HasField"
articleTitle: "HasField"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Check if the form already has specified field."
type: docs
weight: 120
url: "/net/aspose.pdf.forms/form/hasfield/"
product_version: "26.9.0"
---
## HasField([Field](../../../aspose.pdf.forms/field/)) {#hasfield}

Check if the form already has specified field.

```csharp
public bool HasField(Field field)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | Field to check. |

### Return Value

bool

`true` if the specified field name added to Form; otherwise, `false`.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Determines if the field with specified name already added to the Form.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | string | <see cref="P:Aspose.Pdf.Forms.Field.PartialName" /> or <see cref="P:Aspose.Pdf.Annotations.Annotation.FullName" /> of the field. |

### Return Value

bool

 if the specified field name added to Form; otherwise, .

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Determines if the field with specified name already added to the Form, with ability to look into children hierarchy of fields.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | string | <see cref="P:Aspose.Pdf.Forms.Field.PartialName" /> or <see cref="P:Aspose.Pdf.Annotations.Annotation.FullName" /> of the field. |
| searchChildren | bool | When set to <see langword="true" /> the whole hierarchy of form fields would be searched for the requested *fieldName*
 (note that in this case the <see cref="P:Aspose.Pdf.Annotations.Annotation.FullName" /> of the required field should be passed as *fieldName*). |

### Return Value

bool

 if the specified field name added to Form; otherwise, .

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

