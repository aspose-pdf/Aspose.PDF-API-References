---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: طريقة SvgExtractor. تستخرج صورة SVG إلى سلسلة من العناصر الرسومية التي تمثلها الممتص مع فلتر شرط.
type: docs
weight: 20
url: /ar/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

تستخرج صورة SVG إلى سلسلة من العناصر الرسومية التي تمثلها !:absorber مع فلتر شرط.

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| absorber | GraphicsAbsorber | كائن GraphicsAbsorber الذي يحتوي على العناصر الرسومية. |
| filter | Predicate`1 | دالة شرطية تستخدم لتصفية العناصر الرسومية. |
| page | Page | الصفحة التي يحصل فيها الممتص على العناصر الرسومية. |

### Return Value

السلسلة التي تحتوي على محتوى SVG.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ عند التحويل إلى SVG. |

### See Also

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

تستخرج صورة SVG إلى ملف من العناصر الرسومية التي تمثلها !:absorber مع فلتر شرط.

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| absorber | GraphicsAbsorber | كائن GraphicsAbsorber الذي يحتوي على العناصر الرسومية. |
| filter | Predicate`1 | دالة شرطية تستخدم لتصفية العناصر الرسومية. |
| page | Page | الصفحة التي يحصل فيها الممتص على العناصر الرسومية. |
| svgFilePath | String | مسار ملف SVG المستهدف. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ عند التحويل إلى SVG. |

### See Also

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

تستخرج العناصر الرسومية إلى سلسلة SVG. الخيارات غير معتمدة - التجميع، الاستخراج من المستطيل.

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| elements | IEnumerable`1 | العناصر الرسومية التي سيتم تحويلها. |
| page | Page | الصفحة التي يحصل فيها الممتص على العناصر الرسومية. |

### Return Value

السلسلة التي تحتوي على محتوى SVG.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ عند التحويل إلى SVG. |

### See Also

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

تستخرج العناصر الرسومية إلى ملف SVG واحد. الخيارات غير معتمدة - التجميع، الاستخراج من المستطيل.

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| elements | IEnumerable`1 | العناصر الرسومية التي سيتم تحويلها. |
| page | Page | الصفحة التي يحصل فيها الممتص على العناصر الرسومية. |
| svgFilePath | String | مسار ملف SVG المستهدف. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ عند التحويل إلى SVG. |

### See Also

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

تستخرج صور SVG من صفحة إلى سلاسل.

```csharp
public List<string> Extract(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | الصفحة التي سيتم استخراجها. |

### Return Value

قائمة بسلاسل محتوى SVG.

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ عند التحويل إلى SVG. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

تستخرج صور SVG من صفحة إلى ملفات.

```csharp
public void Extract(Page page, string directory)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | الصفحة التي سيتم استخراجها. |
| directory | String | الدليل المستهدف لوضع صور SVG. |

### Exceptions

| exception | condition |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | إذا حدث خطأ عند التحويل إلى SVG. |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)