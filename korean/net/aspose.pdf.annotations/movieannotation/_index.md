---
title: Class MovieAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.MovieAnnotation 클래스. 컴퓨터 화면과 스피커를 통해 표시될 애니메이션 그래픽과 사운드를 포함하는 영화 주석을 나타냅니다. 주석이 활성화되면 영화가 재생됩니다.
type: docs
weight: 2110
url: /ko/net/aspose.pdf.annotations/movieannotation/
---
## MovieAnnotation 클래스

컴퓨터 화면과 스피커를 통해 표시될 애니메이션 그래픽과 사운드를 포함하는 영화 주석을 나타냅니다. 주석이 활성화되면 영화가 재생됩니다.

```csharp
public sealed class MovieAnnotation : Annotation
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MovieAnnotation](movieannotation/#constructor)(Document, string) | 생성자, Generator와 함께 사용됩니다. |
| [MovieAnnotation](movieannotation/#constructor_1)(Page, Rectangle, string) | 지정된 페이지에 새 사운드 주석을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | 주석 작업 목록을 가져옵니다. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | 현재 주석의 외관 상태를 가져오거나 설정합니다. |
| override [AnnotationType](../../aspose.pdf.annotations/movieannotation/annotationtype/) { get; } | 주석의 유형을 가져옵니다. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [Aspect](../../aspose.pdf.annotations/movieannotation/aspect/) { get; set; } | 영화의 경계 상자의 너비와 높이를 픽셀 단위로 가져오거나 설정합니다. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | 주석 테두리 특성을 가져오거나 설정합니다. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | 주석 특성을 가져옵니다. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | 주석 색상을 가져오거나 설정합니다. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | 주석 텍스트를 가져오거나 설정합니다. |
| [File](../../aspose.pdf.annotations/movieannotation/file/) { get; set; } | 자기 설명 영화 파일을 식별하는 파일 사양을 가져오거나 설정합니다. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | 주석의 플래그입니다. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | 주석의 전체 자격 이름을 가져옵니다. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | 주석의 높이를 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( PDF 생성기용). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다(PDF 생성용) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | 주석이 최근에 수정된 날짜와 시간을 가져오거나 설정합니다. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | 페이지에서 주석 이름을 가져오거나 설정합니다. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | 주석이 포함된 페이지의 인덱스를 가져옵니다. |
| [Poster](../../aspose.pdf.annotations/movieannotation/poster/) { get; set; } | 영화의 포스터 이미지를 표시할지 여부와 방법을 지정하는 플래그 또는 스트림을 가져오거나 설정합니다. true인 경우 포스터 이미지는 영화 파일에서 가져오고, false인 경우 포스터는 표시되지 않습니다. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | 주석 사각형을 가져오거나 설정합니다. |
| [Rotate](../../aspose.pdf.annotations/movieannotation/rotate/) { get; set; } | 영화가 페이지에 대해 시계 방향으로 회전할 각도를 가져오거나 설정합니다. 값은 90의 배수여야 합니다. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | 주석의 외관 사전을 가져옵니다. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | 주석의 텍스트 정렬을 가져오거나 설정합니다. |
| [Title](../../aspose.pdf.annotations/movieannotation/title/) { get; set; } | 영화 주석의 제목을 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | 주석의 너비를 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/movieannotation/accept/)(AnnotationSelector) | 주석을 처리하기 위해 방문자 객체를 수락합니다. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | 매트릭스 변환에 따라 매개변수와 외관을 업데이트합니다. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 이 인스턴스를 복제합니다. 가상 메서드입니다. 항상 null을 반환합니다. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | 주석 내용을 페이지에 직접 배치하고 주석 객체를 제거합니다. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |

### 참조

* 클래스 [Annotation](../annotation/)
* 네임스페이스 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../)