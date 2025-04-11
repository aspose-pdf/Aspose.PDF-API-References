---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: طريقة الوثيقة. تخزن الوثيقة في الدفق
type: docs
weight: 830
url: /ar/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

تخزن الوثيقة في الدفق.

```csharp
public void Save(Stream output)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| output | Stream | الدفق الذي ستخزن فيه الوثيقة. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

تخزن الوثيقة في الملف المحدد.

```csharp
public void Save(string outputFileName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | مسار الملف الذي ستخزن فيه الوثيقة. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

تخزن الوثيقة بشكل تدريجي (أي باستخدام تقنية التحديث التدريجي).

```csharp
public void Save()
```

## ملاحظات

من أجل تخزين الوثيقة بشكل تدريجي، يجب علينا فتح ملف الوثيقة للكتابة. لذلك يجب تهيئة Document مع دفق قابل للكتابة كما في مقتطف الكود التالي: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // إجراء بعض التغييرات وتخزين الوثيقة بشكل تدريجي doc.Save();

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

تخزن الوثيقة مع خيارات الحفظ.

```csharp
public void Save(SaveOptions options)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| options | SaveOptions | خيارات الحفظ. |

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

تخزن الوثيقة باسم جديد مع تنسيق ملف.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | مسار الملف الذي ستخزن فيه الوثيقة. |
| format | SaveFormat | خيارات التنسيق. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

تخزن الوثيقة باسم جديد مع تنسيق ملف.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق الذي ستخزن فيه الوثيقة. |
| format | SaveFormat | خيارات التنسيق. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | ArgumentException عند تمرير [`HtmlSaveOptions`](../../htmlsaveoptions/) إلى طريقة. حفظ الوثيقة إلى دفق html غير مدعوم. يرجى استخدام طريقة الحفظ إلى الملف. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

تخزن الوثيقة باسم جديد مع تعيين خيارات الحفظ الخاصة بها.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | مسار الملف الذي ستخزن فيه الوثيقة. |
| options | SaveOptions | خيارات الحفظ. |

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

تخزن الوثيقة إلى دفق مع خيارات الحفظ.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | الدفق الذي ستخزن فيه الوثيقة. |
| options | SaveOptions | خيارات الحفظ. |

### الاستثناءات

| الاستثناء | الشرط |
| --- | --- |
| ArgumentException | ArgumentException عند تمرير [`HtmlSaveOptions`](../../htmlsaveoptions/) إلى طريقة. حفظ الوثيقة إلى دفق html غير مدعوم. يرجى استخدام طريقة الحفظ إلى الملف. |

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)