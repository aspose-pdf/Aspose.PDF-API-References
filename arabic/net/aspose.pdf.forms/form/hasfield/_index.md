---
title: "Form.HasField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تحقق مما إذا كان النموذج يحتوي بالفعل على الحقل المحدد."
type: docs
weight: 300
url: /ar/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

تحقق مما إذا كان النموذج يحتوي بالفعل على الحقل المحدد.

```csharp
public bool HasField(Field field)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| حقل | حقل | الحقل للتحقق منه. |

### قيمة الإرجاع

`true` إذا تم إضافة اسم الحقل المحدد إلى النموذج؛ وإلا، `false`.

### انظر أيضًا

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

يحدد ما إذا كان الحقل بالاسم المحدد قد أُضيف بالفعل إلى النموذج.

```csharp
public bool HasField(string fieldName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) أو [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) للحقل. |

### قيمة الإرجاع

`true` إذا تم إضافة اسم الحقل المحدد إلى النموذج؛ وإلا، `false`.

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

يحدد ما إذا كان الحقل بالاسم المحدد قد أُضيف بالفعل إلى النموذج، مع القدرة على النظر في تسلسل هرمي للأطفال من الحقول.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) أو [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) للحقل. |
| searchChildren | Boolean | عند تعيينه إلى `true` سيتم البحث في كامل تسلسل حقول النموذج عن *fieldName* المطلوب (لاحظ أنه في هذه الحالة يجب تمرير [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) للحقل المطلوب كـ *fieldName*). |

### قيمة الإرجاع

`true` إذا تم إضافة اسم الحقل المحدد إلى النموذج؛ وإلا، `false`.

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


