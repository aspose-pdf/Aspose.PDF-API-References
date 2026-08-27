---
title: "TextFragment.Text"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "خاصية TextFragment. يحصل على أو يعيّن كائن نص من نوع String الذي يمثله كائن TextFragment"
type: docs
weight: 130
url: /ar/net/aspose.pdf.text/textfragment/text/
---
## TextFragment.Text property

يحصل على أو يعيّن كائن نص من نوع String الذي يمثله كائن [`TextFragment`](../).

```csharp
public string Text { get; set; }
```

## أمثلة

يوضح المثال كيفية البحث عن نص واستبدال أول ظهور ممثل بكائن [`TextFragment`](../).

```csharp
// فتح المستند
Document doc = new Document(@"D:\Tests\input.pdf");

// إنشاء كائن TextFragmentAbsorber للعثور على جميع تكرارات النص "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// قبول الماص للصفحة الأولى
doc.Pages[1].Accept(absorber);

// تغيير خط أول ظهور للنص
absorber.TextFragments[1].Text = "hi world";

// حفظ المستند
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


