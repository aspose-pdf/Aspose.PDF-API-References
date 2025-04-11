---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber 속성. 텍스트 추출 옵션을 가져오거나 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions 속성

텍스트 추출 옵션을 가져오거나 설정합니다.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## 비고

추출 중에 텍스트 형식 모드 [`TextExtractionOptions`](../../textextractionoptions/)를 정의할 수 있습니다. 기본 모드는 Pure입니다.

## 예제

이 예제는 Pure 텍스트 형식 모드를 설정하고 텍스트 추출을 수행하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### 참조

* 클래스 [TextExtractionOptions](../../textextractionoptions/)
* 클래스 [TextAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)