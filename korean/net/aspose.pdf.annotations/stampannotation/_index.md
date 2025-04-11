---
title: Class StampAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.StampAnnotation 클래스. 고무 도장 주석을 나타냅니다. 이 유형의 주석은 페이지에 고무 도장으로 찍힌 것처럼 보이도록 텍스트 또는 그래픽을 표시합니다.
type: docs
weight: 2610
url: /ko/net/aspose.pdf.annotations/stampannotation/
---
## StampAnnotation 클래스

고무 도장 주석을 나타냅니다. 이 유형의 주석은 페이지에 고무 도장으로 찍힌 것처럼 보이도록 텍스트 또는 그래픽을 표시합니다.

```csharp
public sealed class StampAnnotation : MarkupAnnotation
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StampAnnotation](stampannotation/#constructor)(Document) | 생성자 |
| [StampAnnotation](stampannotation/#constructor_1)(Page, Rectangle) | 지정된 페이지에 새 Stamp 주석을 만듭니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 주석 작업 목록을 가져옵니다. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 현재 주석 외관 상태를 가져오거나 설정합니다. |
| override [AnnotationType](../../aspose.pdf.annotations/stampannotation/annotationtype/) { get; } | 주석 유형을 가져옵니다. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 주석 테두리 특성을 가져오거나 설정합니다. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 주석 특성을 가져옵니다. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 주석 색상을 가져오거나 설정합니다. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 주석 텍스트를 가져오거나 설정합니다. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | 주석이 생성된 날짜와 시간을 가져옵니다. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 주석의 플래그입니다. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 주석의 전체 자격 이름을 가져옵니다. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 주석의 높이를 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [Icon](../../aspose.pdf.annotations/stampannotation/icon/) { get; set; } | 고무 도장을 위한 아이콘을 가져오거나 설정합니다. |
| [Image](../../aspose.pdf.annotations/stampannotation/image/) { get; set; } | 주석의 이미지를 가져오거나 설정합니다. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | 이 주석이 "답변하는" 주석에 대한 참조입니다. 두 주석은 문서의 동일한 페이지에 있어야 합니다. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다.(pdf 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(pdf 생성용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다( pdf 생성용) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 주석이 최근에 수정된 날짜와 시간을 가져오거나 설정합니다. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 페이지에서 주석 이름을 가져오거나 설정합니다. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | 주석을 그릴 때 사용할 불투명도 상수 값을 가져오거나 설정합니다. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 주석이 포함된 페이지의 인덱스를 가져옵니다. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | 이 주석과 관련된 텍스트를 입력하거나 편집하기 위한 팝업 주석입니다. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 주석 사각형을 가져오거나 설정합니다. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | 이 주석과 InReplyTo로 지정된 주석 간의 관계( "답변 유형")를 지정하는 문자열입니다. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | 주석이 열릴 때 팝업 창에 표시될 리치 텍스트 문자열을 가져오거나 설정합니다. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | 객체의 설명을 나타내는 텍스트를 가져오거나 설정합니다. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 주석의 텍스트 정렬을 가져오거나 설정합니다. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 주석의 제목 표시줄에 표시될 텍스트를 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 주석의 너비를 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/stampannotation/accept/)(AnnotationSelector) | 주석 컬렉션을 탐색할 때 [`AnnotationSelector`](../annotationselector/) 방문자를 수락합니다. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 매트릭스 변환에 따라 매개변수와 외관을 업데이트합니다. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | 주석의 상태 및 상태 모델을 지웁니다. 예를 들어, 주석의 검토 상태를 지웁니다. 상태는 상태 및 상태 모델 키가 있는 다른 텍스트 주석에 저장됩니다. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 이 인스턴스를 복제합니다. 가상 메서드. 항상 null을 반환합니다. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 주석 내용을 페이지에 직접 배치하고 주석 객체를 제거합니다. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | 주석의 상태를 가져옵니다. 상태는 상태 및 상태 모델 키가 있는 다른 텍스트 주석에 저장됩니다. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | 주석의 상태 모델을 가져옵니다. 상태는 상태 및 상태 모델 키가 있는 다른 텍스트 주석에 저장됩니다. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | 주석에 대해 표시된 및 표시되지 않은 상태를 설정합니다. 상태는 상태 및 상태 모델 키가 있는 다른 텍스트 주석에 저장됩니다. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | 주석에 대한 검토 상태를 설정합니다. 표시된 및 표시되지 않은 상태는 검토 상태 모델에 속하지 않으므로 무시됩니다. 상태는 대상 주석을 생성한 사용자에 의해 설정됩니다. 값은 대상 주석의 Title 속성에서 가져옵니다. 상태는 상태 및 상태 모델 키가 있는 다른 텍스트 주석에 저장됩니다. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | 주석에 대한 검토 상태를 설정합니다. 표시된 및 표시되지 않은 상태는 검토 상태 모델에 속하지 않으므로 무시됩니다. 상태는 상태 및 상태 모델 키가 있는 다른 텍스트 주석에 저장됩니다. |

## 예제

다음 코드 조각은 첫 번째 pdf 문서 페이지에 2개의 스탬프를 추가하는 방법을 보여줍니다. 입력 문서는 inFile에서 가져오고 변경 사항은 outFile에 저장됩니다. 첫 번째 스탬프는 아이콘 NotForPublicRelease를 가지고 있으며 두 번째는 rubber.jpg에서 이미지를 가져옵니다.

```csharp
Document document = new Document(inFile);
StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease);
stamp1.Rect = new Rectangle(100, 100, 120, 120)
document.Pages[1].Annotations.Add(stamp1);
StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open));
stamp2.Rect = new Rectangle(200, 200, 220, 220)
document.Pages[1].Annotations.Add(stamp2);
document.Save(outFile);
```

### 참조

* 클래스 [MarkupAnnotation](../markupannotation/)
* 네임스페이스 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../)