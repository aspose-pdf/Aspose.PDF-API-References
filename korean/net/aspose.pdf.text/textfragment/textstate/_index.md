---
title: TextFragment.TextState
second_title: Aspose.PDF for .NET API Reference
description: TextFragment 속성. TextFragment 객체가 나타내는 텍스트의 텍스트 상태를 가져오거나 설정합니다.
type: docs
weight: 150
url: /ko/net/aspose.pdf.text/textfragment/textstate/
---
## TextFragment.TextState 속성

[`TextFragment`](../) 객체가 나타내는 텍스트의 텍스트 상태를 가져오거나 설정합니다.

```csharp
public TextFragmentState TextState { get; }
```

## 비고

텍스트의 다음 속성을 변경하는 방법을 제공합니다: 글꼴 FontSize FontStyle 전경색 배경색

## 예제

이 예제는 `TextState` 객체를 사용하여 텍스트의 색상과 글꼴 크기를 변경하는 방법을 보여줍니다.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);

// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");  
```

### 참조

* 클래스 [TextFragmentAbsorber](../../textfragmentabsorber/)
* 클래스 [Document](../../../aspose.pdf/document/)
* 클래스 [TextFragmentState](../../textfragmentstate/)
* 클래스 [TextFragment](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)