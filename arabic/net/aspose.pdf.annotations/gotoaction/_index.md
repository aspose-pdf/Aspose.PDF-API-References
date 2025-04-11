---
title: Class GoToAction
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.GoToAction. تمثل إجراء الانتقال الذي يغير العرض إلى موقع صفحة وجهة محددة وعامل تكبير
type: docs
weight: 1830
url: /ar/net/aspose.pdf.annotations/gotoaction/
---
## GoToAction class

تمثل إجراء الانتقال الذي يغير العرض إلى وجهة محددة (صفحة، موقع، وعامل تكبير).

```csharp
public class GoToAction : PdfAction
```

## Constructors

| Name | Description |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | المُنشئ. |
| [GoToAction](gotoaction/#constructor_3)(Page) | مُنشئ لفئة GoToAction. |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | إجراء مرتبط بالوجهة المسماة. |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | مُنشئ لفئة GoToAction. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | يحصل أو يحدد الوجهة التي يتم الانتقال إليها. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | الإجراءات التالية في التسلسل. |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | يحصل على سلسلة لإجراء ECMAScript. |

### See Also

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)