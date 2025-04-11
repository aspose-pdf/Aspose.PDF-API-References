---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تضيف حقلًا إلى النموذج
type: docs
weight: 190
url: /ar/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

تضيف حقلًا إلى النموذج.

```csharp
public void Add(Field field, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | الحقل الذي يجب إضافته. |
| pageNumber | Int32 | فهرس الصفحة التي سيتم وضع الحقل المضاف عليها. |

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

تضيف حقلًا إلى النموذج.

```csharp
public void Add(Field field)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | الحقل الذي يجب إضافته. |

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

تضيف حقلًا جديدًا إلى النموذج؛ إذا كان هذا الحقل موجودًا بالفعل في نموذج آخر أو هذا النموذج، سيتم إنشاء نسخة من الحقل.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | اسم الحقل. |
| partialName | String | اسم الحقل على النموذج. |
| pageNumber | Int32 | رقم الصفحة التي سيتم إضافة الحقل عليها. |

### Return Value

تمت إعادة الحقل المضاف. إذا تم إنشاء نسخة من الحقل، فسيتم إرجاعها.

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)