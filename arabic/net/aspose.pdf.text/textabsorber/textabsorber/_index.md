---
title: "TextAbsorber.TextAbsorber"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "TextAbsorber المُنشئ. يهيئ مثيلاً جديدًا من TextAbsorber"
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

يهيئ مثيلاً جديدًا من [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## ملاحظات

ينفّذ استخراج النص ويتيح الوصول إلى النص المستخرج عبر كائن [`Text`](../text/).

## أمثلة

يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص
TextAbsorber absorber = new TextAbsorber();

// قبول الـ absorber لجميع صفحات المستند
doc.Pages.Accept(absorber);

// احصل على النص المستخرج
string extractedText = absorber.Text;

```

### انظر أيضًا

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

يهيئ مثيلاً جديدًا من [`TextAbsorber`](../) مع خيارات الاستخراج.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | خيارات استخراج النص |

## ملاحظات

ينفّذ استخراج النص ويتيح الوصول إلى النص المستخرج عبر كائن [`Text`](../text/).

## أمثلة

يوضح المثال كيفية استخراج النص من جميع صفحات مستند PDF.

```csharp
// فتح المستند
Document doc = new Document(inFile);

// إنشاء كائن TextAbsorber لاستخراج النص مع التنسيق
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// قبول الـ absorber لجميع صفحات المستند
doc.Pages.Accept(absorber);

// احصل على النص المستخرج
string extractedText = absorber.Text;

```

### انظر أيضًا

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

يهيئ مثيلاً جديدًا من [`TextAbsorber`](../) مع خيارات الاستخراج والبحث عن النص.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | خيارات استخراج النص |
| textSearchOptions | TextSearchOptions | خيارات البحث النصي |

## ملاحظات

ينفّذ استخراج النص ويتيح الوصول إلى النص المستخرج عبر كائن [`Text`](../text/).

### انظر أيضًا

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

يهيئ مثيلاً جديدًا من [`TextAbsorber`](../) مع خيارات البحث عن النص.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | خيارات البحث النصي |

## ملاحظات

ينفّذ استخراج النص ويتيح الوصول إلى النص المستخرج عبر كائن [`Text`](../text/).

### انظر أيضًا

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


