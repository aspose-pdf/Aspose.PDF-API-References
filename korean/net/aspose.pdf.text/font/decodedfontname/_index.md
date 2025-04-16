---
title: Font.DecodedFontName
second_title: Aspose.PDF for .NET API Reference
description: 글꼴 속성. 때때로 PDF 글꼴（주로 중국어/일본어/한국어 글꼴）은 특정한 글꼴 이름을 가질 수 있습니다. 이 이름은 PDF 글꼴 속성인 BaseFont의 값이며, 때때로 이 속성은 16진수 형식으로 표현될 수 있습니다. 이 이름을 직접 읽으면 읽을 수 없는 형식으로 표현될 수 있습니다. 읽을 수 있는 형식을 얻으려면 이 글꼴에 특정한 규칙에 따라 글꼴 이름을 디코딩해야 합니다. 이 속성은 디코딩된 글꼴 이름을 반환하므로 읽을 수 없는 [`FontName`](../fontname/)을 만났을 때 사용하십시오. 속성 [`FontName`](../fontname/)이 읽을 수 있는 형식을 가지면 이 속성은 [`FontName`](../fontname/)과 동일하므로 읽을 수 있는 형식의 글꼴 이름을 얻어야 할 때 이 속성을 사용할 수 있습니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.text/font/decodedfontname/
---
## Font.DecodedFontName 속성

때때로 PDF 글꼴(주로 중국어/일본어/한국어 글꼴)은 특정한 글꼴 이름을 가질 수 있습니다. 이 이름은 PDF 글꼴 속성 "BaseFont"의 값이며, 때때로 이 속성은 16진수 형식으로 표현될 수 있습니다. 이 이름을 직접 읽으면 읽을 수 없는 형식으로 표현될 수 있습니다. 읽을 수 있는 형식을 얻으려면 이 글꼴에 특정한 규칙에 따라 글꼴 이름을 디코딩해야 합니다. 이 속성은 디코딩된 글꼴 이름을 반환하므로 읽을 수 없는 [`FontName`](../fontname/)을 만났을 때 사용하십시오. 속성 [`FontName`](../fontname/)이 읽을 수 있는 형식을 가지면 이 속성은 [`FontName`](../fontname/)과 동일하므로 읽을 수 있는 형식의 글꼴 이름을 얻어야 할 때 이 속성을 사용할 수 있습니다.

```csharp
public string DecodedFontName { get; }
```

### 참조

* 클래스 [Font](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)