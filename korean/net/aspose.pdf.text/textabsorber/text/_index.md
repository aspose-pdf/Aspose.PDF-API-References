---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber 속성. PDF 문서 또는 페이지에서 TextAbsorber가 추출한 텍스트를 가져옵니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text 속성

[`TextAbsorber`](../)가 PDF 문서 또는 페이지에서 추출한 텍스트를 가져옵니다.

```csharp
public virtual string Text { get; }
```

## 예제

이 예제는 PDF 문서의 모든 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 참조

* 클래스 [TextAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)