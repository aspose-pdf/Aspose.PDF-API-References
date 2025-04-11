---
title: ComHelper.OpenFile
second_title: Aspose.PDF for .NET API Reference
description: طريقة ComHelper. فقط قم بإنشاء وإرجاع مستند باستخدام اسم الملف. نفس الشيء مثل Document
type: docs
weight: 20
url: /ar/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

فقط قم بإنشاء وإرجاع مستند باستخدام *اسم الملف*. نفس الشيء مثل [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف مستند PDF. |

### قيمة الإرجاع

كائن Document

### انظر أيضًا

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

تهيئة وإرجاع مثيل جديد من فئة [`Document`](../../document/) للعمل مع مستند مشفر.

```csharp
public Document OpenFile(string filename, string password)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف المستند. |
| password | String | كلمة مرور المستخدم أو المالك. |

### قيمة الإرجاع

كائن Document

### انظر أيضًا

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string, bool) {#openfile_3}

تهيئة مثيل جديد من فئة [`Document`](../../document/) للعمل مع مستند مشفر.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف المستند. |
| password | String | كلمة مرور المستخدم أو المالك. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق التدفق الداخلي قبل الخروج؛ خلاف ذلك، لا يتم ذلك. |

### قيمة الإرجاع

كائن Document

### انظر أيضًا

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

فتح مستند موجود من ملف مع توفير خيارات التحويل اللازمة للحصول على مستند PDF.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | ملف الإدخال للتحويل إلى مستند PDF. |
| options | LoadOptions | تمثل الخصائص لتحويل *اسم الملف* إلى مستند PDF. |

### قيمة الإرجاع

كائن Document

### انظر أيضًا

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)