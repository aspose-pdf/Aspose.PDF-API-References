---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: خاصية TextAbsorber. تحصل على النص المستخرج الذي يستخرجه TextAbsorber من مستند PDF أو صفحة
type: docs
weight: 50
url: /ar/net/aspose.pdf.text/textabsorber/text/
---
## خاصية TextAbsorber.Text

تحصل على النص المستخرج الذي يستخرجه [`TextAbsorber`](../) من مستند PDF أو صفحة.

```csharp
public virtual string Text { get; }
```

## أمثلة

توضح المثال كيفية استخراج النص من جميع صفحات مستند PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### انظر أيضًا

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)