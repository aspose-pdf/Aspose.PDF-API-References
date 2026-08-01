---
title: "Font.IsAccessible"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Font 속성. 시스템에 글꼴이 설치되어 있는지 여부를 나타냅니다."
type: docs
weight: 50
url: /ko/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible property

시스템에 글꼴이 존재(설치)하는지 여부를 가져옵니다.

```csharp
public bool IsAccessible { get; }
```

## 비고

시스템에서 찾을 수 없는 글꼴에 대해서는 일부 작업을 사용할 수 없습니다.

## 예제

이 예제는 첫 페이지에서 텍스트를 검색하고 글꼴이 시스템에 설치되어 있는지 여부를 나타내는 값을 가져오는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 글꼴 IsSubset 값을 확인합니다.
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### 또 보기

* class [TextFragmentAbsorber](../../textfragmentabsorber/)
* class [Document](../../../aspose.pdf/document/)
* class [Font](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


