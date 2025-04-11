---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: طريقة الوثيقة. تخزن الوثيقة في التدفق
type: docs
weight: 840
url: /ar/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

تخزن الوثيقة في التدفق.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | Stream | التدفق الذي ستخزن فيه الوثيقة. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

يحفظ الوثيقة في الملف المحدد.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | مسار الملف الذي ستخزن فيه الوثيقة. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

يحفظ الوثيقة بشكل تدريجي (أي باستخدام تقنية التحديث التدريجي).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

## ملاحظات

لحفظ الوثيقة بشكل تدريجي يجب علينا فتح ملف الوثيقة للكتابة. لذلك يجب تهيئة Document بتدفق قابل للكتابة كما في مقتطف الشيفرة التالي: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // قم بإجراء بعض التغييرات واحفظ الوثيقة بشكل تدريجي doc.Save();

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

يحفظ الوثيقة مع خيارات الحفظ.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | SaveOptions | خيارات الحفظ. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

يحفظ الوثيقة باسم جديد مع تنسيق ملف.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | مسار الملف الذي ستخزن فيه الوثيقة. |
| format | SaveFormat | خيارات التنسيق. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### انظر أيضًا

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

يحفظ الوثيقة باسم جديد مع تنسيق ملف.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق الذي ستخزن فيه الوثيقة. |
| format | SaveFormat | خيارات التنسيق. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | ArgumentException عند تمرير [`HtmlSaveOptions`](../../htmlsaveoptions/) إلى طريقة. حفظ الوثيقة إلى تدفق HTML غير مدعوم. يرجى استخدام طريقة الحفظ إلى الملف. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

يحفظ الوثيقة باسم جديد مع تعيين خيارات الحفظ الخاصة به.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | مسار الملف الذي ستخزن فيه الوثيقة. |
| options | SaveOptions | خيارات الحفظ. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

يحفظ الوثيقة إلى تدفق مع خيارات الحفظ.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق الذي ستخزن فيه الوثيقة. |
| options | SaveOptions | خيارات الحفظ. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | ArgumentException عند تمرير [`HtmlSaveOptions`](../../htmlsaveoptions/) إلى طريقة. حفظ الوثيقة إلى تدفق HTML غير مدعوم. يرجى استخدام طريقة الحفظ إلى الملف. |

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)