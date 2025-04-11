---
title: TextFragmentAbsorber.Visit
second_title: Aspose.PDF for .NET API Reference
description: طريقة TextFragmentAbsorber. تقوم بإجراء بحث على الصفحة المحددة
type: docs
weight: 150
url: /ar/net/aspose.pdf.text/textfragmentabsorber/visit/
---
## Visit(Page) {#visit_1}

تقوم بإجراء بحث على الصفحة المحددة.

```csharp
public override void Visit(Page page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page | Page | كائن صفحة مستند PDF. |

## Examples

المثال يوضح كيفية العثور على نص في الصفحة الأولى من مستند PDF واستبدال النص.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc.Pages[1]);

// Change text of all search occurrences
foreach (TextFragment textFragment in absorber.TextFragments)
{
    textFragment.Text = "hi world";
}

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

تقوم بإجراء بحث على المستند المحدد.

```csharp
public override void Visit(Document pdf)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pdf | Document | كائن مستند PDF. |

## Examples

المثال يوضح كيفية العثور على نص في مستند PDF واستبدال نص جميع حالات البحث.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Find font that will be used to change document text font
Aspose.Pdf.Txt.Font font = FontRepository.FindFont("Arial");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
absorber.Visit(doc);

// Change text of the first text occurrence
absorber.TextFragments[1].Text = "hi world";

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

تقوم بإجراء بحث على كائن النموذج المحدد.

```csharp
public void Visit(XForm xForm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xForm | XForm | كائن نموذج PDF. |

### See Also

* class [XForm](../../../aspose.pdf/xform/)
* class [TextFragmentAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)