---
title: "TextBuilder.AppendText"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة TextBuilder. تُضيف جزء النص إلى صفحة Pdf"
type: docs
weight: 30
url: /ar/net/aspose.pdf.text/textbuilder/appendtext/
---
## AppendText(TextFragment) {#appendtext}

يُضيف مقطع نص إلى صفحة Pdf

```csharp
public void AppendText(TextFragment textFragment)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| textFragment | TextFragment | كائن Text fragment. |

## أمثلة

يوضح المثال كيفية إنشاء كائن Text fragment، وتخصيص مقاطع النص الخاصة به وإضافته إلى صفحة Pdf.

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

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## AppendText(List&lt;TextFragment&gt;) {#appendtext_1}

يُضيف قائمة من مقاطع النص إلى صفحة Pdf.

```csharp
public void AppendText(List<TextFragment> textFragments)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| textFragments | List`1 | مجموعة من Text fragments |

### انظر أيضًا

* class [TextFragment](../../textfragment/)
* class [TextBuilder](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


