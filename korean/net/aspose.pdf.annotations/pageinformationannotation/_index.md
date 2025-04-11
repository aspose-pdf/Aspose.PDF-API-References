---
title: Class PageInformationAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.PageInformationAnnotation 클래스. PDF 문서에서 페이지 정보 주석을 나타냅니다. 이 주석은 파일 이름, 페이지 번호 및 주석 생성 날짜와 시간을 포함합니다.
type: docs
weight: 2260
url: /ko/net/aspose.pdf.annotations/pageinformationannotation/
---
## PageInformationAnnotation 클래스

PDF 문서에서 페이지 정보 주석을 나타냅니다. 이 주석은 파일 이름, 페이지 번호 및 주석 생성 날짜와 시간을 포함합니다.

```csharp
public sealed class PageInformationAnnotation : PrinterMarkAnnotation
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PageInformationAnnotation](pageinformationannotation/)(Page, Rectangle) | 주어진 위치의 주어진 페이지에서 `PageInformationAnnotation` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 주석 작업 목록을 가져옵니다. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 현재 주석 외관 상태를 가져오거나 설정합니다. |
| override [AnnotationType](../../aspose.pdf.annotations/pageinformationannotation/annotationtype/) { get; } | 주석의 유형을 가져옵니다. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 주석 테두리 특성을 가져오거나 설정합니다. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 주석 특성을 가져옵니다. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 주석 색상을 가져오거나 설정합니다. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 주석 텍스트를 가져오거나 설정합니다. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 주석의 플래그입니다. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 주석의 전체 자격 이름을 가져옵니다. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 주석의 높이를 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( PDF 생성기용). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다(PDF 생성용) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 주석이 최근 수정된 날짜와 시간을 가져오거나 설정합니다. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 페이지에서 주석 이름을 가져오거나 설정합니다. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 주석이 포함된 페이지의 인덱스를 가져옵니다. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 주석 사각형을 가져오거나 설정합니다. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 주석의 텍스트 정렬을 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 주석의 너비를 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/pageinformationannotation/accept/)(AnnotationSelector) | 주석 처리를 위한 방문자를 수락합니다. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 매트릭스 변환에 따라 매개변수와 외관을 업데이트합니다. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 이 인스턴스를 복제합니다. 가상 메서드입니다. 항상 null을 반환합니다. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 주석 내용을 페이지에 직접 배치하고 주석 객체를 제거합니다. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |

## 비고

이 클래스는 PDF 문서의 특정 페이지에 메타데이터를 추가하는 데 주로 사용되며, 이는 추적 및 참조 목적으로 유용할 수 있습니다. 예를 들어, 인쇄 과정에서 페이지를 표시하거나 문서를 볼 때 페이지에 대한 추가 정보를 제공하는 데 사용할 수 있습니다.

### 참조

* 클래스 [PrinterMarkAnnotation](../printermarkannotation/)
* 네임스페이스 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../)