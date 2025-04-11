---
title: Class TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextAbsorber class. يمثل كائن ماص للنص. يقوم باستخراج النص ويوفر الوصول إلى النتيجة عبر كائن [`Text`](./text/)
type: docs
weight: 10800
url: /ar/net/aspose.pdf.text/textabsorber/
---
## Class TextAbsorber

يمثل كائن ماص للنص. يقوم باستخراج النص ويوفر الوصول إلى النتيجة عبر كائن [`Text`](./text/).

```csharp
public class TextAbsorber
```

## Constructors

| Name | Description |
| --- | --- |
| [TextAbsorber](textabsorber/#constructor)() | يقوم بتهيئة مثيل جديد من `TextAbsorber`. |
| [TextAbsorber](textabsorber/#constructor_1)(TextExtractionOptions) | يقوم بتهيئة مثيل جديد من `TextAbsorber` مع خيارات الاستخراج. |
| [TextAbsorber](textabsorber/#constructor_3)(TextSearchOptions) | يقوم بتهيئة مثيل جديد من `TextAbsorber` مع خيارات بحث النص. |
| [TextAbsorber](textabsorber/#constructor_2)(TextExtractionOptions, TextSearchOptions) | يقوم بتهيئة مثيل جديد من `TextAbsorber` مع خيارات الاستخراج وبحث النص. |

## Properties

| Name | Description |
| --- | --- |
| [Errors](../../aspose.pdf.text/textabsorber/errors/) { get; } | قائمة من كائنات [`TextExtractionError`](../textextractionerror/). تحتوي على معلومات حول الأخطاء التي تم العثور عليها أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كانت TextSearchOptions.LogTextExtractionErrors = true; وقد يقلل ذلك من الأداء. |
| virtual [ExtractionOptions](../../aspose.pdf.text/textabsorber/extractionoptions/) { get; set; } | يحصل أو يحدد خيارات استخراج النص. |
| [HasErrors](../../aspose.pdf.text/textabsorber/haserrors/) { get; } | القيمة تشير إلى ما إذا كانت هناك أخطاء تم العثور عليها أثناء استخراج النص. سيتم البحث عن الأخطاء فقط إذا كانت TextSearchOptions.LogTextExtractionErrors = true; وقد يقلل ذلك من الأداء. |
| virtual [Text](../../aspose.pdf.text/textabsorber/text/) { get; } | يحصل على النص المستخرج الذي يقوم `TextAbsorber` باستخراجه من مستند PDF أو صفحة. |
| virtual [TextSearchOptions](../../aspose.pdf.text/textabsorber/textsearchoptions/) { get; set; } | يحصل أو يحدد خيارات بحث النص. |

## Methods

| Name | Description |
| --- | --- |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit)(Document) | يقوم باستخراج النص من المستند المحدد |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_1)(Page) | يقوم باستخراج النص من الصفحة المحددة |
| virtual [Visit](../../aspose.pdf.text/textabsorber/visit/#visit_2)(XForm) | يقوم باستخراج النص من XForm المحدد. |

## Remarks

يتم استخدام كائن `TextAbsorber` لاستخراج النص من مستند PDF أو صفحة المستند.

## Examples

المثال يوضح كيفية استخراج النص من الصفحة الأولى لمستند PDF.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for first page
doc.Pages[1].Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)