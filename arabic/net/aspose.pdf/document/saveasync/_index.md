---
title: "Document.SaveAsync"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Document. تحفظ المستند إلى دفق مع خيارات الحفظ"
type: docs
weight: 860
url: /ar/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

يحفظ المستند إلى تدفق مع خيارات الحفظ.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق حيث سيتم تخزين المستند. |
| options | SaveOptions | خيارات الحفظ. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | ArgumentException عندما يتم تمرير [`HtmlSaveOptions`](../../htmlsaveoptions/) إلى طريقة. حفظ المستند إلى تدفق html غير مدعوم. يرجى استخدام طريقة الحفظ إلى الملف. |

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_3}

يخزن المستند في تدفق.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الإخراج | Stream | الدفق حيث سيتم تخزين المستند. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

يحفظ المستند في الملف المحدد.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | المسار إلى الملف حيث سيتم تخزين المستند. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

حفظ المستند بشكل تدريجي (أي باستخدام تقنية التحديث التدريجي).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

## ملاحظات

من أجل حفظ المستند بشكل تدريجي يجب فتح ملف المستند للكتابة. لذلك يجب تهيئة Document باستخدام تدفق قابل للكتابة كما في المقتطف التالي: Document doc = new Document(new FileStream(\"document.pdf\", FileMode.Open, FileAccess.ReadWrite)); // قم بإجراء بعض التغييرات واحفظ المستند بشكل تدريجي doc.Save();

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

يحفظ المستند باستخدام خيارات الحفظ.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
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

يحفظ المستند باسم جديد مع تنسيق الملف.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | المسار إلى الملف حيث سيتم تخزين المستند. |
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

يحفظ المستند باسم جديد مع تنسيق الملف.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق حيث سيتم تخزين المستند. |
| format | SaveFormat | خيارات التنسيق. |
| cancellationToken | CancellationToken | رمز الإلغاء |

### قيمة الإرجاع

مهمة غير متزامنة.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | ArgumentException عندما يتم تمرير [`HtmlSaveOptions`](../../htmlsaveoptions/) إلى طريقة. حفظ المستند إلى تدفق html غير مدعوم. يرجى استخدام طريقة الحفظ إلى الملف. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

يحفظ المستند باسم جديد مع تعيين خيارات الحفظ الخاصة به.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | المسار إلى الملف حيث سيتم تخزين المستند. |
| options | SaveOptions | خيارات الحفظ. |
| cancellationToken | CancellationToken | رمز الإلغاء. |

### قيمة الإرجاع

مهمة غير متزامنة.

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


