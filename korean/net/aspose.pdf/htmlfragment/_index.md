---
title: "클래스 HtmlFragment"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.HtmlFragment 클래스. HTML 조각을 나타냅니다."
type: docs
weight: 5650
url: /ko/net/aspose.pdf/htmlfragment/
---
## HtmlFragment class

HTML 조각을 나타냅니다.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | HtmlFragment 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 단락의 수평 정렬을 가져오거나 설정합니다. |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | 이 클래스 인스턴스로 HTML을 로드(및 렌더링)하는 데 사용될 HtmlLoadOptions를 가져오거나 설정합니다. 특정 인스턴스에 대해 HTML 가져오기 설정을 지정해야 할 경우(예: 해당 인스턴스가 가져온 HTML에 대해 특정 BasePath를 사용하거나 외부 리소스 로더를 사용해야 할 때) 사용하십시오. 매개변수가 기본값(null)인 경우 표준 HTML 로드 옵션이 사용됩니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | 단어 구분을 가져오거나 설정합니다. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 가져오거나 설정합니다. 이 단락이 다음 열에 배치될지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 가져오거나 설정합니다. 단락이 인라인인지 여부입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 가져오거나 설정합니다. 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 가져오거나 설정합니다. 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | 단락에 기본 여백이 있는지 여부를 가져오거나 설정합니다. 기본 여백이 없으면 여백은 0입니다. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다. (pdf 생성용) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | HtmlFragment의 사각형을 가져옵니다. |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | 글꼴을 가져오거나 설정합니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z 순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. ZIndex가 음수인 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | HTML 조각을 복제합니다. |

### 또 보기

* class [FormattedFragment](../formattedfragment/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


