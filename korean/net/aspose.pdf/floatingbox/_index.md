---
title: "클래스 FloatingBox"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.FloatingBox 클래스."
type: docs
weight: 4990
url: /ko/net/aspose.pdf/floatingbox/
---
## FloatingBox class

```csharp
public class FloatingBox : BaseParagraph
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FloatingBox](floatingbox/#constructor)() | `FloatingBox` 클래스의 새 인스턴스를 초기화합니다. |
| [FloatingBox](floatingbox/#constructor_1)(float, float) | 지정된 너비와 높이를 사용하여 `FloatingBox` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackgroundColor](../../aspose.pdf/floatingbox/backgroundcolor/) { get; set; } | 플로팅 박스의 배경 색을 나타내는 [`Color`](../color/) 객체를 가져오거나 설정합니다. |
| [BackgroundImage](../../aspose.pdf/floatingbox/backgroundimage/) { get; set; } | 페이지의 배경 이미지를 가져오거나 설정합니다(생성기 전용이며 문서를 읽을 때는 채워지지 않습니다). |
| [Border](../../aspose.pdf/floatingbox/border/) { get; set; } | 플로팅 박스의 테두리 정보를 나타내는 [`BorderInfo`](../borderinfo/) 객체를 가져오거나 설정합니다. |
| [ColumnInfo](../../aspose.pdf/floatingbox/columninfo/) { get; set; } | 열 정보를 가져오거나 설정합니다. |
| [Height](../../aspose.pdf/floatingbox/height/) { get; set; } | 플로팅 박스의 높이를 나타내는 부동 소수점 값을 가져오거나 설정합니다. |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 단락의 수평 정렬을 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 가져오거나 설정합니다. 이 단락이 다음 열에 배치될지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 가져오거나 설정합니다. 단락이 인라인인지 여부입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 가져오거나 설정합니다. 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 가져오거나 설정합니다. 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsNeedRepeating](../../aspose.pdf/floatingbox/isneedrepeating/) { get; set; } | 단락이 다음 페이지에 반복되어야 하는지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다. 이 속성은 단락 자체와 ReferenceParagraphID가 참조하는 객체가 모두 RepeatingRows에 포함된 경우에만 유효합니다. |
| [Left](../../aspose.pdf/floatingbox/left/) { get; set; } | 표의 왼쪽 좌표를 가져오거나 설정합니다. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다. (pdf 생성용) |
| [Padding](../../aspose.pdf/floatingbox/padding/) { get; set; } | 플로팅 박스의 패딩을 나타내는 [`MarginInfo`](../margininfo/) 객체를 가져오거나 설정합니다. |
| [Paragraphs](../../aspose.pdf/floatingbox/paragraphs/) { get; set; } | 셀에 포함된 모든 단락을 나타내는 [`Paragraphs`](./paragraphs/) 컬렉션을 가져오거나 설정합니다. |
| [PositioningMode](../../aspose.pdf/floatingbox/positioningmode/) { get; set; } | 페이지에서 FloatingBox의 위치를 결정하기 위한 변형을 지정합니다. |
| [Top](../../aspose.pdf/floatingbox/top/) { get; set; } | 표의 상단 좌표를 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| [Width](../../aspose.pdf/floatingbox/width/) { get; set; } | 플로팅 박스의 너비를 나타내는 부동 소수점 값을 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z 순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. ZIndex가 음수인 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf/floatingbox/clone/)() | 새 `FloatingBox` 객체를 복제합니다. 플로팅 박스 내의 단락은 복제되지 않습니다. |

### 또 보기

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


