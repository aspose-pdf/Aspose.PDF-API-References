---
title: Class Font
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Text.Font. تمثل كائن الخط
type: docs
weight: 10510
url: /ar/net/aspose.pdf.text/font/
---
## فئة الخط

تمثل كائن الخط.

```csharp
public sealed class Font
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | يحصل على قيمة BaseFont لكائن الخط PDF. يُعرف أيضًا باسم اسم PostScript للخط. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | أحيانًا قد تحتوي خطوط PDF (عادةً الخطوط الصينية/اليابانية/الكورية) على اسم خط محدد. هذا الاسم هو قيمة خاصية الخط PDF "BaseFont" وأحيانًا يمكن تمثيل هذه الخاصية بشكل سداسي. إذا تم قراءة هذا الاسم مباشرة، فقد يتم تمثيله بشكل غير قابل للقراءة. للحصول على شكل قابل للقراءة، من الضروري فك تشفير اسم الخط وفقًا للقواعد المحددة لهذا الخط. تعيد هذه الخاصية اسم الخط المفكوك، لذا استخدمها في الحالات التي تواجه فيها اسم [`FontName`](./fontname/) غير قابل للقراءة. إذا كانت الخاصية [`FontName`](./fontname/) لها شكل قابل للقراءة، فستكون هذه الخاصية هي نفسها [`FontName`](./fontname/)، لذا يمكنك استخدام هذه الخاصية في أي حالات تحتاج فيها إلى الحصول على اسم الخط بشكل قابل للقراءة. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | يحصل على اسم الخط لكائن `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | خصائص مفيدة لضبط سلوك الخط |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | يحصل على مؤشر يوضح ما إذا كان الخط موجودًا (مثبتًا) في النظام. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان الخط مضمنًا. سيتم تلقائيًا تقسيم الخط القائم على IFont وإدراجه |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | يحصل أو يحدد قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. سيتم تلقائيًا تقسيم الخط القائم على IFont وإدراجه |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | الهدف من هذه الطريقة هو إرجاع وصف الخطأ إذا فشلت محاولة تضمين الخط. إذا لم تكن هناك حالات خطأ، فإنها تعيد سلسلة فارغة. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | يقيس السلسلة. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | يحفظ الخط في الدفق. لاحظ أن الخط يتم حفظه في تنسيق TTF الوسيط الذي يهدف إلى استخدامه في نسخة محولة من الوثيقة الأصلية فقط. ملف الخط غير مخصص للاستخدام خارج سياق الوثيقة الأصلية. |

## أمثلة

توضح المثال كيفية البحث عن نص في الصفحة الأولى وتغيير خط أول ظهور للبحث.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;


// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* فئة [TextFragmentAbsorber](../textfragmentabsorber/)
* فئة [FontRepository](../fontrepository/)
* فئة [Document](../../aspose.pdf/document/)
* مساحة الأسماء [Aspose.Pdf.Text](../../aspose.pdf.text/)
* التجميع [Aspose.PDF](../../)