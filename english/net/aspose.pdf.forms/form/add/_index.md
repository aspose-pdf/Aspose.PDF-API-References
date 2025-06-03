---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: Form method. Adds field on the form
type: docs
weight: 210
url: /net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Adds field on the form.

```csharp
public void Add(Field field, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | Field which must be added. |
| pageNumber | Int32 | Page index where added field will be placed. |

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Adds field on the form.

```csharp
public void Add(Field field)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | Field which must be added. |

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Adds new field to the form; If this field is already placed on other or this form, the copy of field is created.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | Field name. |
| partialName | String | Name of field on the form. |
| pageNumber | Int32 | Page number where field will be added. |

### Return Value

Added field returned. If copy of the field was created it will be returned.

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


