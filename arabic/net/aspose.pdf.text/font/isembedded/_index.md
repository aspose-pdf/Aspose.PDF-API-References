---
title: Font.IsEmbedded
second_title: Aspose.PDF for .NET API Reference
description: خاصية الخط. تحصل أو تعين قيمة تشير إلى ما إذا كان الخط مضمنًا. سيتم تلقائيًا تقسيم الخط القائم على IFont وإدراجه
type: docs
weight: 60
url: /ar/net/aspose.pdf.text/font/isembedded/
---
## خاصية Font.IsEmbedded

تحصل أو تعين قيمة تشير إلى ما إذا كان الخط مضمنًا. سيتم تلقائيًا تقسيم الخط القائم على IFont وإدراجه

```csharp
public bool IsEmbedded { get; set; }
```

## أمثلة

المثال التالي يوضح كيفية العثور على خط، ووسمه كمضمن، والبحث عن نص في صفحة الوثيقة واستبدال خط النص.

```csharp
// Create font and mark it to be embedded
Font font = FontRepository.FindFont("Arial");
font.IsEmbedded = true;

// open document
Document doc = new Document(@"D:\Tests\input.pdf");

// create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");
// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// change font for the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### انظر أيضًا

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [FontRepository](../../fontrepository/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)