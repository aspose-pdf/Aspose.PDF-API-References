---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ToUnicodeProcessingRules class. تصف هذه الفئة القواعد التي يمكن استخدامها لحل خطأ Adobe Preflight "لا يمكن تعيين النص إلى Unicode"
type: docs
weight: 11110
url: /ar/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

تصف هذه الفئة القواعد التي يمكن استخدامها لحل خطأ Adobe Preflight "لا يمكن تعيين النص إلى Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Constructors

| Name | Description |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Initializes a new instance of the `ToUnicodeProcessingRules` class. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Initializes a new instance of the `ToUnicodeProcessingRules` class with the specified option to remove spaces from CMap names. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Initializes a new instance of the `ToUnicodeProcessingRules` class with specified options. |

## Properties

| Name | Description |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | بعض الخطوط لا توفر معلومات حول الرموز النصية لبعض الرموز. هذه النقص في المعلومات يتسبب في حدوث خطأ "لا يمكن تعيين النص إلى Unicode". استخدم هذه العلامة لتعيين الرموز غير المرتبطة على unicode "space"(code 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | بعض الخطوط تحتوي على خرائط رموز الأحرف ToUnicode مع مسافات في الأسماء. هذه المسافات قد تتسبب في حدوث أخطاء مع تعيين نصوص Unicode. هذه العلامة تأمر بإزالة المسافات من أسماء خرائط رموز الأحرف ToUnicode. بشكل افتراضي false. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)