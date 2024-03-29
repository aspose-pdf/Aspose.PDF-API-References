---
title: AppendText
second_title: Aspose.PDF لمرجع .NET API
description: إلحاق جزء نصي بصفحة Pdf
type: docs
weight: 30
url: /ar/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

إلحاق جزء نصي بصفحة Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| textFragment | TextFragment | كائن جزء النص. |

### أمثلة

يوضح المثال كيفية إنشاء كائن جزء النص وتخصيص أجزاء النص وإلحاقه بصفحة Pdf.

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

* class [TextFragment](../../textfragment)
* class [TextBuilder](../../textbuilder)
* مساحة الاسم [Aspose.Pdf.Text](../../textbuilder)
* المجسم [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

إلحاق قائمة بأجزاء النص بصفحة Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| textFragments | List`1 | مجموعة من أجزاء النص |

### أنظر أيضا

* class [TextFragment](../../textfragment)
* class [TextBuilder](../../textbuilder)
* مساحة الاسم [Aspose.Pdf.Text](../../textbuilder)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
