---
title: "클래스 FreeTextAnnotation"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations.FreeTextAnnotation class. Page에 직접 텍스트를 표시하는 자유 텍스트 주석을 나타냅니다. 일반 텍스트 주석과 달리 자유 텍스트 주석은 열림 또는 닫힘 상태가 없으며 팝업 창에 표시되는 대신 텍스트가 항상 표시됩니다."
type: docs
weight: 1900
url: /ko/net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

페이지에 직접 텍스트를 표시하는 자유 텍스트 주석을 나타냅니다. 일반 텍스트 주석과 달리 자유 텍스트 주석은 열림 또는 닫힘 상태가 없으며, 팝업 창에 표시되는 대신 텍스트가 항상 보입니다.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FreeTextAnnotation](freetextannotation/#constructor)(Document, DefaultAppearance) | Generator와 함께 사용할 생성자. |
| [FreeTextAnnotation](freetextannotation/#constructor_1)(Page, Rectangle, DefaultAppearance) | 지정된 Page에 새로운 FreeText 주석을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 주석 작업 목록을 가져옵니다. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 현재 주석 외관 상태를 가져오거나 설정합니다. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype/) { get; } | 주석 유형을 가져옵니다. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 주석 테두리 특성을 가져오거나 설정합니다. [`Border`](../annotation/border/) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout/) { get; set; } | 콜아웃 라인을 지정하는 점 배열. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 주석 특성을 가져옵니다. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 주석 색상을 가져오거나 설정합니다. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 주석 텍스트를 가져오거나 설정합니다. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | 주석이 생성된 날짜와 시간을 가져옵니다. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance/) { get; set; } | 텍스트 형식 지정에 사용되는 기본 외관 문자열을 가져오거나 설정합니다. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject/) { get; } | FreeText Annotation의 기본 외관을 나타내는 객체입니다. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle/) { get; set; } | 기본 스타일 문자열을 가져오거나 설정합니다. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle/) { get; set; } | 끝점에 대한 선 종료 스타일을 가져오거나 설정합니다. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 주석의 플래그. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 주석의 전체 자격 이름을 가져옵니다. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 주석의 높이를 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | 이 주석이 "답변하는" 주석에 대한 참조입니다. 두 주석은 문서의 같은 페이지에 있어야 합니다. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent/) { get; set; } | FreeText Annotation의 의도를 가져오거나 설정합니다. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 가져오거나 설정합니다. 이 단락이 다음 열에 배치될지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 가져오거나 설정합니다. 단락이 인라인인지 여부입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 가져오거나 설정합니다. 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 가져오거나 설정합니다. 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification/) { get; set; } | Annotation의 텍스트 표시 시 사용되는 정렬(좌우 맞춤) 형태를 지정하는 코드를 가져오거나 설정합니다. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다. (pdf 생성용) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Annotation이 최근 수정된 날짜와 시간을 가져오거나 설정합니다. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Page 상의 Annotation 이름을 가져오거나 설정합니다. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | 주석을 그릴 때 사용할 상수 불투명도 값을 가져오거나 설정합니다. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 주석이 포함된 페이지의 인덱스를 가져옵니다. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | 이 주석과 연결된 텍스트를 입력하거나 편집하기 위한 팝업 주석. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 주석 사각형을 가져오거나 설정합니다. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | 이 주석과 InReplyTo에 의해 지정된 주석 사이의 관계("reply type")를 지정하는 문자열입니다. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | 주석이 열릴 때 팝업 창에 표시될 리치 텍스트 문자열을 가져오거나 설정합니다. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate/) { get; set; } | Annotation 회전 각도. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle/) { get; set; } | 끝점에 대한 선 종료 스타일을 가져오거나 설정합니다. 이 속성은 더 이상 사용되지 않으며, EndingStyle를 사용하십시오. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Annotation의 외관 사전을 가져옵니다. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | 객체의 설명을 나타내는 텍스트를 가져옵니다. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Annotation의 텍스트 정렬을 가져오거나 설정합니다. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle/) { get; set; } | 두 개의 Rectangle 사이의 수치적 차이를 설명하는 Rectangle: Annotation의 Rect 항목과 그 안에 포함된 Rectangle입니다. 내부 Rectangle은 Annotation의 텍스트가 표시되어야 하는 영역입니다. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle/) { get; set; } | 외관에서 텍스트 스타일을 가져오거나 설정합니다. 텍스트 스타일이 변경되면 텍스트 외관이 업데이트됩니다. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | 열려 있고 활성화된 주석 팝업 창의 제목 표시줄에 표시될 텍스트 레이블을 가져오거나 설정합니다. 이 항목은 주석을 추가한 사용자를 식별합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 주석의 너비를 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z 순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. ZIndex가 음수인 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept/)(AnnotationSelector) | Annotation을 처리하기 위해 방문자 객체를 받아들입니다. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 행렬 변환에 따라 매개변수와 모양을 업데이트합니다. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | 주석의 상태와 상태 모델을 지웁니다. 예를 들어, 주석의 검토 상태를 지웁니다. 참고: state 및 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태는 그대로 유지됩니다. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 이 인스턴스를 복제합니다. 가상 메서드. 항상 null을 반환합니다. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 주석 내용을 페이지에 직접 배치하고, 주석 객체는 제거됩니다. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | 주석의 상태를 가져옵니다. 참고: state 및 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태는 그대로 유지됩니다. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | 주석의 상태 모델을 가져옵니다. 참고: state 및 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태는 그대로 유지됩니다. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | 주석에 대해 Marked 및 Unmarked 상태를 설정합니다. 참고: state 및 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태는 그대로 유지됩니다. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | 주석의 검토 상태를 설정합니다. Marked 및 Unmarked 상태는 Review StateModel에 속하지 않으므로 무시됩니다. 상태는 대상 주석을 만든 사용자가 설정하며, 값은 대상 주석의 Title 속성에서 가져옵니다. 참고: state 및 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태는 그대로 유지됩니다. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | 주석의 검토 상태를 설정합니다. Marked 및 Unmarked 상태는 Review StateModel에 속하지 않으므로 무시됩니다. 참고: state 및 statemodel 키를 가진 다른 텍스트 주석에 저장된 상태는 그대로 유지됩니다. |
| [SetTextStyle](../../aspose.pdf.annotations/freetextannotation/settextstyle/#settextstyle_1)(int, int, RichTextFontStyles) | textStyle 매개변수에 의해 결정된 서식을 fromInd 인덱스부터 toInd 인덱스까지의 텍스트 조각에 적용합니다. |
| [SetTextStyle](../../aspose.pdf.annotations/freetextannotation/settextstyle/#settextstyle)(RichTextFontStyles, string, double, Color) | textStyle 매개변수에 의해 결정된 서식을 모든 Annotation 텍스트에 적용합니다. |

### 또 보기

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


