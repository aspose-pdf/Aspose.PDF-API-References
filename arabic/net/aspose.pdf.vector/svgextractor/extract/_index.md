---
title: "SvgExtractor.Extract"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة SvgExtractor. تستخرج صورة SVG إلى سلسلة من العناصر الرسومية التي يمثلها الماص بمرشح شرط."
type: docs
weight: 20
url: /ar/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

يستخرج صورة svg إلى سلسلة من العناصر الرسومية التي تمثلها !:absorber مع مرشح شرط.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الماص | GraphicsAbsorber | كائن GraphicsAbsorber الذي يحتوي على العناصر الرسومية. |
| مرشح | Predicate`1 | دالة شرط تُستخدم لتصفية العناصر الرسومية. |
| صفحة | صفحة | الصفحة التي يحصل فيها الماص على العناصر الرسومية. |

### قيمة الإرجاع

السلسلة التي تحتوي على محتوى SVG.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ أثناء التحويل إلى SVG. |

### انظر أيضًا

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

يستخرج صورة svg إلى ملف من العناصر الرسومية التي تمثلها !:absorber مع مرشح شرط.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| الماص | GraphicsAbsorber | كائن GraphicsAbsorber الذي يحتوي على العناصر الرسومية. |
| مرشح | Predicate`1 | دالة شرط تُستخدم لتصفية العناصر الرسومية. |
| صفحة | صفحة | الصفحة التي يحصل فيها الماص على العناصر الرسومية. |
| svgFilePath | String | مسار ملف SVG الهدف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ أثناء التحويل إلى SVG. |

### انظر أيضًا

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

يستخرج العناصر الرسومية إلى سلسلة SVG. تم تجاهل الخيارات - التجميع، الاستخراج من المستطيل.

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| العناصر | IEnumerable`1 | العناصر الرسومية للتحويل. |
| صفحة | صفحة | الصفحة التي يحصل فيها الماص على العناصر الرسومية. |

### قيمة الإرجاع

السلسلة التي تحتوي على محتوى SVG.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ أثناء التحويل إلى SVG. |

### انظر أيضًا

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

يستخرج العناصر الرسومية إلى ملف SVG واحد. تم تجاهل الخيارات - التجميع، الاستخراج من المستطيل.

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| العناصر | IEnumerable`1 | العناصر الرسومية للتحويل. |
| صفحة | صفحة | الصفحة التي يحصل فيها الماص على العناصر الرسومية. |
| svgFilePath | String | مسار ملف SVG الهدف. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ أثناء التحويل إلى SVG. |

### انظر أيضًا

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

يستخرج صور Svg من صفحة إلى سلاسل نصية.

```csharp
public List<string> Extract(Page page)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | صفحة | الصفحة لاستخراجها. |

### قيمة الإرجاع

قائمة سلاسل محتوى SVG.

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ أثناء التحويل إلى SVG. |

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

يستخرج صور Svg من صفحة إلى ملفات.

```csharp
public void Extract(Page page, string directory)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| صفحة | صفحة | الصفحة لاستخراجها. |
| دليل | String | الدليل الهدف لوضع صور SVG. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ أثناء التحويل إلى SVG. |

### انظر أيضًا

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


