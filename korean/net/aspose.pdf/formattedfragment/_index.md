---
title: "클래스 FormattedFragment"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.FormattedFragment 클래스. 추상 형식 조각을 나타냅니다"
type: docs
weight: 5060
url: /ko/net/aspose.pdf/formattedfragment/
---
## FormattedFragment class

추상 형식화된 조각을 나타냅니다.

```csharp
public abstract class FormattedFragment : BaseParagraph
```

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 단락의 수평 정렬을 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( pdf 생성기용). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 가져오거나 설정합니다. 이 단락이 다음 열에 배치될지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 가져오거나 설정합니다. 단락이 인라인인지 여부입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 가져오거나 설정합니다. 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 가져오거나 설정합니다. 현재 단락이 다음 단락과 함께 동일한 페이지에 남아 있는지 여부를 나타내는 bool 값입니다. 기본값은 false입니다. (pdf 생성용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다. (pdf 생성용) |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z 순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. ZIndex가 음수인 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | 이 인스턴스를 복제합니다. 가상 메서드. 항상 null을 반환합니다. |

### 또 보기

* class [BaseParagraph](../baseparagraph/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


