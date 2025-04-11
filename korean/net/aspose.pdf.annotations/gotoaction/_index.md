---
title: Class GoToAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.GoToAction 클래스. 지정된 목적지 페이지 위치와 확대 배율로 뷰를 변경하는 이동 작업을 나타냅니다.
type: docs
weight: 1830
url: /ko/net/aspose.pdf.annotations/gotoaction/
---
## GoToAction class

지정된 목적지(페이지, 위치 및 확대 배율)로 뷰를 변경하는 이동 작업을 나타냅니다.

```csharp
public class GoToAction : PdfAction
```

## Constructors

| Name | Description |
| --- | --- |
| [GoToAction](gotoaction/#constructor_1)(ExplicitDestination) | 생성자. |
| [GoToAction](gotoaction/#constructor_3)(Page) | GoToAction 클래스의 생성자. |
| [GoToAction](gotoaction/#constructor_2)(Document, string) | 명명된 목적지와 연결된 작업. |
| [GoToAction](gotoaction/#constructor_4)(Page, ExplicitDestinationType, params double[]) | GoToAction 클래스의 생성자. |

## Properties

| Name | Description |
| --- | --- |
| virtual [Destination](../../aspose.pdf.annotations/gotoaction/destination/) { get; set; } | 점프할 목적지를 가져오거나 설정합니다. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | 순서대로 다음 작업. |

## Methods

| Name | Description |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | ECMAScript 작업에 대한 문자열을 가져옵니다. |

### See Also

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)