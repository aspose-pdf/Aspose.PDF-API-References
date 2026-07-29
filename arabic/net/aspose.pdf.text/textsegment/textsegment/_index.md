---
title: "TextSegment.TextSegment"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "منشئ TextSegment. ينشئ كائن TextSegment"
type: docs
weight: 10
url: /ar/net/aspose.pdf.text/textsegment/textsegment/
---
## TextSegment() {#constructor}

ينشئ كائن TextSegment.

```csharp
public TextSegment()
```

## أمثلة

يوضح المثال كيفية إنشاء كائن مقطع نصي، إضافة مقطع نص إلى مجموعة مقاطع النص وإلحاقه بصفحة Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// إنشاء Text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// تعيين خصائص النص الخاصة به
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// إضافة مقطع آخر إلى مجموعة Segments الخاصة بـ Text fragment
TextSegment segment2 = new TextSegment();
segment2.Text = "another segment";

tf.Segments.Add(segment2);

// إنشاء كائن TextBuilder
TextBuilder builder = new TextBuilder(page);

// إضافة Text fragment إلى صفحة Pdf
builder.AppendText(tf);

//حفظ المستند
doc.Save(outFile);
```

### انظر أيضًا

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextSegment(string) {#constructor_1}

ينشئ كائن TextSegment.

```csharp
public TextSegment(string text)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| نص | String | نص مقطع النص. |

## أمثلة

يوضح المثال كيفية إنشاء كائن مقطع نصي، إضافة مقطع نص إلى مجموعة مقاطع النص وإلحاقه بصفحة Pdf.

```csharp
Document doc = new Document(inFile);
Page page = (Page)doc.Pages[1];

// إنشاء Text fragment
TextFragment tf = new TextFragment("main text");
tf.Position = new Position(100, 600);

// تعيين خصائص النص الخاصة به
tf.TextState.FontSize = 5;
tf.TextState.Font = FontRepository.FindFont("TimesNewRoman");
tf.TextState.BackgroundColor = Color.LightGray;
tf.TextState.ForegroundColor = Color.Red;

// إضافة مقطع آخر إلى مجموعة Segments الخاصة بـ Text fragment
TextSegment segment2 = new TextSegment("another segment");

tf.Segments.Add(segment2);

// إنشاء كائن TextBuilder
TextBuilder builder = new TextBuilder(page);

// إضافة Text fragment إلى صفحة Pdf
builder.AppendText(tf);

//حفظ المستند
doc.Save(outFile);
```

### انظر أيضًا

* class [TextSegment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


