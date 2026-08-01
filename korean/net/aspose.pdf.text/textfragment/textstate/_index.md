---
title: "TextFragment.TextState"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextFragment 속성. TextFragment 객체가 나타내는 텍스트의 텍스트 상태를 가져오거나 설정합니다."
type: docs
weight: 150
url: /ko/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState property

[`TextFragment`](../) 객체가 나타내는 텍스트의 텍스트 상태를 가져오거나 설정합니다.

```csharp
public TextFragmentState TextState { get; }
```

## 비고

텍스트의 다음 속성을 변경할 수 있는 방법을 제공합니다: Font, FontSize, FontStyle, ForegroundColor, BackgroundColor

## 예제

이 예제는 `TextState` 객체를 사용하여 텍스트의 색상과 글꼴 크기를 변경하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 전경색을 변경합니다.
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// 첫 번째 텍스트 발생의 글꼴 크기를 변경합니다
absorber.TextFragments[1].TextState.FontSize = 15;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf");  
```

### 또 보기

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [TextFragmentState](../../textfragmentstate/)
* class [TextFragment](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


