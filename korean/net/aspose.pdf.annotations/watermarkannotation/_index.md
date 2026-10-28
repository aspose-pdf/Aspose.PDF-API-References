---
title: "클래스 WatermarkAnnotation"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations.WatermarkAnnotation 클래스. Watermark 주석 객체를 설명하는 클래스"
type: docs
weight: 2810
url: /ko/net/aspose.pdf.annotations/watermarkannotation/
---
## WatermarkAnnotation class

클래스는 워터마크 주석 객체를 설명합니다.

```csharp
public class WatermarkAnnotation : Annotation
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [WatermarkAnnotation](watermarkannotation/)(Page, Rectangle) | Watermark 주석 클래스의 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 주석 작업 목록을 가져옵니다. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 현재 주석 외관 상태를 가져오거나 설정합니다. |
| override [AnnotationType](../../aspose.pdf.annotations/watermarkannotation/annotationtype/) { get; } | 주석 유형을 가져옵니다. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 주석 테두리 특성을 가져오거나 설정합니다. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 주석 특성을 가져옵니다. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 주석 색상을 가져오거나 설정합니다. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 주석 텍스트를 가져오거나 설정합니다. |
| [FixedPrint](../../aspose.pdf.annotations/watermarkannotation/fixedprint/) { get; } | Watermark 주석의 고정 인쇄 객체. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 주석의 플래그. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 주석의 전체 자격 이름을 가져옵니다. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 주석의 높이를 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 가져오거나 설정합니다. 이 단락이 다음 열에 배치될지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 가져오거나 설정합니다. 단락이 인라인인지 여부입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 가져오거나 설정합니다. 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 가져오거나 설정합니다. 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다. (pdf 생성용) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Annotation이 최근 수정된 날짜와 시간을 가져오거나 설정합니다. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Page 상의 Annotation 이름을 가져오거나 설정합니다. |
| [Opacity](../../aspose.pdf.annotations/watermarkannotation/opacity/) { get; set; } | 주석의 불투명도를 가져오거나 설정합니다. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 주석이 포함된 페이지의 인덱스를 가져옵니다. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 주석 사각형을 가져오거나 설정합니다. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Annotation의 외관 사전을 가져옵니다. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Annotation의 텍스트 정렬을 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 주석의 너비를 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z 순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. ZIndex가 음수인 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/watermarkannotation/accept/)(AnnotationSelector) | 주석에 방문자를 적용합니다. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/watermarkannotation/changeafterresize/)(Matrix) | 기본 클래스의 정의를 빈 본문으로 재정의합니다. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 이 인스턴스를 복제합니다. 가상 메서드. 항상 null을 반환합니다. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 주석 내용을 페이지에 직접 배치하고, 주석 객체는 제거됩니다. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |
| [SetText](../../aspose.pdf.annotations/watermarkannotation/settext/)(FormattedText) | 주석의 텍스트를 설정합니다. |
| [SetTextAndState](../../aspose.pdf.annotations/watermarkannotation/settextandstate/)(string[], TextState) | 주석의 텍스트를 설정합니다. |

### 또 보기

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


