---
title: "الفئة Font"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Text.Font. تمثل كائن الخط"
type: docs
weight: 10690
url: /ar/net/aspose.pdf.text/font/
---
## Font class

يمثل كائن الخط.

```csharp
public sealed class Font
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BaseFont](../../aspose.pdf.text/font/basefont/) { get; } | يحصل على قيمة BaseFont لكائن خط PDF. وتعرف أيضًا باسم PostScript للخط. |
| [DecodedFontName](../../aspose.pdf.text/font/decodedfontname/) { get; } | في بعض الأحيان قد تحتوي خطوط PDF (عادةً خطوط صينية/يابانية/كورية) على اسم خط محدد. هذا الاسم هو قيمة خاصية الخط PDF "BaseFont" وأحيانًا قد تُعرض هذه الخاصية بصيغة سداسية عشرية. إذا قرأت هذا الاسم مباشرةً قد يكون غير قابل للقراءة. للحصول على صيغة قابلة للقراءة، يلزم فك تشفير اسم الخط وفق قواعد خاصة بهذا الخط. تُعيد هذه الخاصية اسم الخط المفكوك، لذا استخدمها في الحالات التي تواجه فيها [`FontName`](./fontname/) غير قابل للقراءة. إذا كان لخاصية [`FontName`](./fontname/) صيغة قابلة للقراءة، ستكون هذه الخاصية هي نفسها كما في [`FontName`](./fontname/)، وبالتالي يمكنك استخدام هذه الخاصية في أي حالة تحتاج فيها للحصول على اسم الخط بصيغة قابلة للقراءة. |
| [FontName](../../aspose.pdf.text/font/fontname/) { get; } | يحصل على اسم الخط لكائن `Font`. |
| [FontOptions](../../aspose.pdf.text/font/fontoptions/) { get; } | خصائص مفيدة لضبط سلوك Font |
| [IsAccessible](../../aspose.pdf.text/font/isaccessible/) { get; } | يحصل على ما إذا كان الخط موجودًا (مثبتًا) في النظام. |
| [IsEmbedded](../../aspose.pdf.text/font/isembedded/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الخط مضمّنًا. الخط المستند إلى IFont سيُقسم تلقائيًا ويُضمّن. |
| [IsSubset](../../aspose.pdf.text/font/issubset/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان الخط مجموعة فرعية. الخط المستند إلى IFont سيُقسم تلقائيًا ويُضمّن. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetLastFontEmbeddingError](../../aspose.pdf.text/font/getlastfontembeddingerror/)() | هدف هذه الطريقة - إرجاع وصف الخطأ إذا فشلت محاولة تضمين الخط. إذا لم توجد حالات خطأ، تُعيد سلسلة فارغة. |
| [MeasureString](../../aspose.pdf.text/font/measurestring/)(string, float) | يقيس السلسلة. |
| [Save](../../aspose.pdf.text/font/save/)(Stream) | يحفظ الخط في الدفق. لاحظ أن الخط يُحفظ بتنسيق TTF وسيط يُقصد استخدامه فقط في نسخة محوّلة من المستند الأصلي. ملف الخط غير مخصص للاستخدام خارج سياق المستند الأصلي. |

## أمثلة

يوضح المثال كيفية البحث عن النص في الصفحة الأولى وتغيير خط أول ظهور للبحث.

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// إنشاء خط وتحديده ليتم تضمينه
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// تغيير خط أول ظهور للنص
absorber.TextFragments[1].TextState.Font = font;


// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [FontRepository](../fontrepository/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


