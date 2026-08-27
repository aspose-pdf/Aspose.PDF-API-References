---
title: "TextAbsorber.Text"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "TextAbsorber 속성. PDF 문서 또는 페이지에서 TextAbsorber가 추출한 텍스트를 가져옵니다."
type: docs
weight: 50
url: /ko/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

PDF 문서 또는 페이지에서 [`TextAbsorber`](../)가 추출한 텍스트를 가져옵니다.

```csharp
public virtual string Text { get; }
```

## 예제

예제는 PDF 문서의 모든 페이지에서 텍스트를 추출하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 텍스트를 추출하기 위해 TextAbsorber 객체를 생성합니다.
TextAbsorber absorber = new TextAbsorber();

// 문서의 모든 페이지에 대해 흡수기를 수락합니다.
doc.Pages.Accept(absorber);

// 추출된 텍스트를 가져옵니다.
string extractedText = absorber.Text;

```

### 또 보기

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


