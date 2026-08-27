---
title: "TextAbsorber.ExtractionOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextAbsorber 속성. 텍스트 추출 옵션을 가져오거나 설정합니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

텍스트 추출 옵션을 가져오거나 설정합니다.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## 비고

추출 중에 텍스트 서식 모드 [`TextExtractionOptions`](../../textextractionoptions/)를 정의할 수 있습니다. 기본 모드는 Pure입니다.

## 예제

예제는 Pure 텍스트 서식 모드를 설정하고 텍스트 추출을 수행하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 서식이 포함된 텍스트를 추출하기 위해 TextAbsorber 객체를 생성합니다.
TextAbsorber absorber = new TextAbsorber();

// Pure 텍스트 서식 모드를 설정합니다.
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// 문서의 모든 페이지에 대해 흡수기를 수락합니다.
doc.Pages.Accept(absorber);

// 추출된 텍스트를 가져옵니다.
string extractedText = absorber.Text;
```

### 또 보기

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


