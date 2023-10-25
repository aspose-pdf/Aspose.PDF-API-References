---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Form method. Determines if the field with specified name already added to the Form
type: docs
weight: 270
url: /net/aspose.pdf.forms/form/hasfield/
---
## HasField(string) {#hasfield_1}

Determines if the field with specified name already added to the Form.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) or [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) of the field. |

### Return Value

`true` if the specified field name added to Form; otherwise, `false`.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Determines if the field with specified name already added to the Form, with ability to look into children hierarchy of fields.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) or [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) of the field. |
| searchChildren | Boolean | When set to `true` the whole hierarchy of form fields would be searched for the requested *fieldName* (note that in this case the [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) of the required field should be passed as *fieldName*). |

### Return Value

`true` if the specified field name added to Form; otherwise, `false`.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(Field) {#hasfield}

Check if the form already has specified field.

```csharp
public bool HasField(Field field)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | Field to check. |

### Return Value

`true` if the specified field name added to Form; otherwise, `false`.

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


