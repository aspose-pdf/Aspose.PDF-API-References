---
title: "ComHelper.OpenFile"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة ComHelper. فقط إنشاء وإرجاع Document باستخدام اسم الملف. نفس Document."
type: docs
weight: 20
url: /ar/net/aspose.pdf/comhelper/openfile/
---
## OpenFile(string) {#openfile}

فقط إنشاء وإرجاع Document باستخدام *filename*. نفس [`Document`](../../document/document/).

```csharp
public Document OpenFile(string filename)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف مستند pdf. |

### قيمة الإرجاع

كائن Document

### انظر أيضًا

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, string) {#openfile_2}

تهيئة وإرجاع نسخة جديدة من فئة [`Document`](../../document/) للعمل مع مستند مشفر.

```csharp
public Document OpenFile(string filename, string password)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف Document. |
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

تهيئة نسخة جديدة من فئة [`Document`](../../document/) للعمل مع مستند مشفر.

```csharp
public Document OpenFile(string filename, string password, bool isManagedStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | اسم ملف Document. |
| password | String | كلمة مرور المستخدم أو المالك. |
| isManagedStream | Boolean | إذا تم تعيينه إلى `true` يتم إغلاق الدفق الداخلي قبل الخروج؛ وإلا، لا يتم ذلك. |

### قيمة الإرجاع

كائن Document

### انظر أيضًا

* class [Document](../../document/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## OpenFile(string, LoadOptions) {#openfile_1}

افتح مستندًا موجودًا من ملف مع توفير خيارات التحويل اللازمة للحصول على مستند pdf.

```csharp
public Document OpenFile(string filename, LoadOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| filename | String | ملف الإدخال للتحويل إلى مستند pdf. |
| options | LoadOptions | يمثل الخصائص لتحويل *filename* إلى مستند pdf. |

### قيمة الإرجاع

كائن Document

### انظر أيضًا

* class [Document](../../document/)
* class [LoadOptions](../../loadoptions/)
* class [ComHelper](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


