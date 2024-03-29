---
title: TextSegment
second_title: Aspose.PDF لمرجع .NET API
description: إنشاء كائن TextSegment .
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

إنشاء كائن TextSegment .

```csharp
public TextSegment()
```

### أمثلة

يوضح المثال كيفية إنشاء كائن جزء النص وإضافة مقطع نص إلى مجموعة أجزاء النص وإلحاقه بصفحة Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// إنشاء جزء نصي
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// تعيين خصائص النص
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// إضافة جزء واحد إلى مجموعة أجزاء جزء النص
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// إنشاء كائن TextBuilder
TextBuilder builder = new TextBuilder(page);

// إلحاق جزء النص بصفحة Pdf
builder.AppendText(tf);

// حفظ الوثيقة
doc.Save(outFile);
```

### أنظر أيضا

* class [TextSegment](../../textsegment)
* مساحة الاسم [Aspose.Pdf.Text](../../textsegment)
* المجسم [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

إنشاء كائن TextSegment .

```csharp
public TextSegment(string text)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| text | String | نص جزء النص. |

### أمثلة

يوضح المثال كيفية إنشاء كائن جزء النص وإضافة مقطع نص إلى مجموعة أجزاء النص وإلحاقه بصفحة Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// إنشاء جزء نصي
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// تعيين خصائص النص
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// إضافة جزء واحد إلى مجموعة أجزاء جزء النص
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// إنشاء كائن TextBuilder
TextBuilder builder = new TextBuilder(page);

// إلحاق جزء النص بصفحة Pdf
builder.AppendText(tf);

// حفظ الوثيقة
doc.Save(outFile);
```

### أنظر أيضا

* class [TextSegment](../../textsegment)
* مساحة الاسم [Aspose.Pdf.Text](../../textsegment)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
