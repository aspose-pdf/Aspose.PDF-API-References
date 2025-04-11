---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextAbsorber. الحصول على خيارات استخراج النص أو تعيينها
type: docs
weight: 30
url: /ar/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## خاصية TextAbsorber.ExtractionOptions

الحصول على خيارات استخراج النص أو تعيينها.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## ملاحظات

يسمح بتعريف وضع تنسيق النص [`TextExtractionOptions`](../../textextractionoptions/) أثناء الاستخراج. الوضع الافتراضي هو Pure

## أمثلة

توضح المثال كيفية تعيين وضع تنسيق النص Pure وإجراء استخراج النص.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### انظر أيضًا

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)