---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXFragment 클래스. TeX 조각을 나타냅니다.
type: docs
weight: 10360
url: /ko/net/aspose.pdf/texfragment/
---
## TeXFragment 클래스

TeX 조각을 나타냅니다.

```csharp
public class TeXFragment : FormattedFragment
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | HtmlFragment 클래스의 새 인스턴스를 초기화합니다. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | HtmlFragment 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | 단락의 수평 정렬을 가져오거나 설정합니다. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | 조각 하이퍼링크를 가져오거나 설정합니다( PDF 생성기용). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | 이 단락이 다음 열에 있을지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | 단락이 인라인인지 여부를 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다.(PDF 생성용) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | 단락의 외부 여백을 가져오거나 설정합니다(PDF 생성용) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | 이 클래스의 인스턴스에서 LaTeX의 로딩(및 렌더링)에 사용될 TeXLoadOptions를 가져오거나 설정합니다. 이 인스턴스에 대해 LaTeX를 가져오는 데 특정 설정을 사용해야 할 때 사용하십시오(예: 이 인스턴스가 가져온 LaTeX에 대해 특정 BasePath를 사용해야 하거나 외부 리소스의 특정 로더를 사용해야 할 때). 매개변수가 기본값(null)인 경우 표준 LaTeX 로딩 옵션이 사용됩니다. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | 단락의 수직 정렬을 가져오거나 설정합니다. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. 더 큰 ZIndex를 가진 그래프는 더 작은 ZIndex를 가진 그래프 위에 배치됩니다. ZIndex는 음수가 될 수 있습니다. 음수 ZIndex를 가진 그래프는 페이지의 텍스트 뒤에 배치됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | 조각을 복제합니다. |

### 참조

* 클래스 [FormattedFragment](../formattedfragment/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)