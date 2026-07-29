---
title: "Document.Save"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Document. تحفظ المستند إلى دفق مع خيارات الحفظ"
type: docs
weight: 850
url: /ar/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

يحفظ المستند إلى تدفق مع خيارات الحفظ.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق حيث سيتم تخزين المستند. |
| options | SaveOptions | خيارات الحفظ. |

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

## Save(Stream) {#save_2}

يخزن المستند في تدفق.

```csharp
public void Save(Stream output)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الإخراج | Stream | الدفق حيث سيتم تخزين المستند. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

يحفظ المستند في الملف المحدد.

```csharp
public void Save(string outputFileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | المسار إلى الملف حيث سيتم تخزين المستند. |

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

حفظ المستند بشكل تدريجي (أي باستخدام تقنية التحديث التدريجي).

```csharp
public void Save()
```

## ملاحظات

من أجل حفظ المستند بشكل تدريجي يجب فتح ملف المستند للكتابة. لذلك يجب تهيئة Document باستخدام تدفق قابل للكتابة كما في المقتطف التالي: Document doc = new Document(new FileStream(\"document.pdf\", FileMode.Open, FileAccess.ReadWrite)); // قم بإجراء بعض التغييرات واحفظ المستند بشكل تدريجي doc.Save();

### انظر أيضًا

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

يحفظ المستند باستخدام خيارات الحفظ.

```csharp
public void Save(SaveOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| options | SaveOptions | خيارات الحفظ. |

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

يحفظ المستند باسم جديد مع تنسيق الملف.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | المسار إلى الملف حيث سيتم تخزين المستند. |
| format | SaveFormat | خيارات التنسيق. |

### انظر أيضًا

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

يحفظ المستند باسم جديد مع تنسيق الملف.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | دفق حيث سيتم تخزين المستند. |
| format | SaveFormat | خيارات التنسيق. |

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

## Save(string, SaveOptions) {#save_7}

يحفظ المستند باسم جديد مع تعيين خيارات الحفظ الخاصة به.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFileName | String | المسار إلى الملف حيث سيتم تخزين المستند. |
| options | SaveOptions | خيارات الحفظ. |

### انظر أيضًا

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


