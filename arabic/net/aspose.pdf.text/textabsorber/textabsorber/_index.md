---
title: TextAbsorber
second_title: Aspose.PDF لمرجع .NET API
description: يقوم بتهيئة مثيل جديد لملفTextAbsorberaspose.pdf.text/textabsorber .
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

يقوم بتهيئة مثيل جديد لملف[`TextAbsorber`](../../textabsorber) .

```csharp
public TextAbsorber()
```

### ملاحظات

يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر[`Text`](../text) الكائن .

### أمثلة

يوضح المثال كيفية استخراج النص من كافة صفحات مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص
TextAbsorber absorber = new TextAbsorber();

// قبول الامتصاص لجميع صفحات المستند
doc.Pages.Accept(absorber);

// احصل على النص المستخرج
string extractedText = absorber.Text;

```

### أنظر أيضا

* class [TextAbsorber](../../textabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

يقوم بتهيئة مثيل جديد لملف[`TextAbsorber`](../../textabsorber) مع خيارات الاستخراج.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | خيارات استخراج النص |

### ملاحظات

يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر[`Text`](../text) الكائن .

### أمثلة

يوضح المثال كيفية استخراج النص من كافة صفحات مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص بالتنسيق
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// قبول الامتصاص لجميع صفحات المستند
doc.Pages.Accept(absorber);

// احصل على النص المستخرج
string extractedText = absorber.Text;

```

### أنظر أيضا

* class [TextExtractionOptions](../../textextractionoptions)
* class [TextAbsorber](../../textabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

يقوم بتهيئة مثيل جديد لملف[`TextAbsorber`](../../textabsorber) مع خيارات الاستخراج والبحث عن النص.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | خيارات استخراج النص |
| textSearchOptions | TextSearchOptions | خيارات البحث عن النص |

### ملاحظات

يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر[`Text`](../text) الكائن .

### أنظر أيضا

* class [TextExtractionOptions](../../textextractionoptions)
* class [TextSearchOptions](../../textsearchoptions)
* class [TextAbsorber](../../textabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textabsorber)
* المجسم [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

يقوم بتهيئة مثيل جديد لملف[`TextAbsorber`](../../textabsorber) مع خيارات البحث عن النص.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | خيارات البحث عن النص |

### ملاحظات

يقوم باستخراج النص ويوفر الوصول إلى النص المستخرج عبر[`Text`](../text) الكائن .

### أنظر أيضا

* class [TextSearchOptions](../../textsearchoptions)
* class [TextAbsorber](../../textabsorber)
* مساحة الاسم [Aspose.Pdf.Text](../../textabsorber)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
