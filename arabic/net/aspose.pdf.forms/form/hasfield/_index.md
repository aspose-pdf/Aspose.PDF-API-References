---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تحقق مما إذا كان النموذج يحتوي بالفعل على الحقل المحدد
type: docs
weight: 280
url: /ar/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

تحقق مما إذا كان النموذج يحتوي بالفعل على الحقل المحدد.

```csharp
public bool HasField(Field field)
```

| Parameter | Type | Description |
| --- | --- | --- |
| field | Field | الحقل للتحقق. |

### Return Value

`true` إذا تم إضافة اسم الحقل المحدد إلى النموذج؛ خلاف ذلك، `false`.

### See Also

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

يحدد ما إذا كان الحقل بالاسم المحدد قد تم إضافته بالفعل إلى النموذج.

```csharp
public bool HasField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) أو [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) للحقل. |

### Return Value

`true` إذا تم إضافة اسم الحقل المحدد إلى النموذج؛ خلاف ذلك، `false`.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

يحدد ما إذا كان الحقل بالاسم المحدد قد تم إضافته بالفعل إلى النموذج، مع القدرة على البحث في تسلسل الحقول الفرعية.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) أو [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) للحقل. |
| searchChildren | Boolean | عند تعيينه إلى `true`، سيتم البحث في التسلسل الكامل لحقول النموذج عن *fieldName* المطلوب (لاحظ أنه في هذه الحالة يجب تمرير [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) للحقل المطلوب كـ *fieldName*). |

### Return Value

`true` إذا تم إضافة اسم الحقل المحدد إلى النموذج؛ خلاف ذلك، `false`.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)