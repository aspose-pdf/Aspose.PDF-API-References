---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes 열거형. 이 열거형은 HTML에서 참조된 파일의 가능한 포함 모드를 나열합니다. 이는 참조된 파일（HTML, 글꼴, 이미지, CSS）이 주요 HTML 파일에 포함될지 또는 별도의 이진 엔티티로 생성될지를 제어할 수 있게 해줍니다.
type: docs
weight: 5710
url: /ko/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes 열거형

이 열거형은 HTML에서 참조된 파일의 가능한 포함 모드를 나열합니다. 이는 참조된 파일(HTML, 글꼴, 이미지, CSS)이 주요 HTML 파일에 포함될지 또는 별도의 이진 엔티티로 생성될지를 제어할 수 있게 해줍니다.

```csharp
public enum PartsEmbeddingModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | 모든 참조된 파일(CSS, 이미지, 글꼴)을 생성된 HTML 마크업(즉, HTML 자체)에 포함하도록 강제합니다. 이 접근 방식은 하나의 HTML 파일을 생성하지만, 출력의 총 크기가 커집니다(바이너리의 Base64 인코딩이 사용되기 때문입니다) 그리고 모든 브라우저(특히 레거시 브라우저)가 HTML에 포함된 바이너리를 성공적으로 처리하지는 않습니다. 그러나 이는 추가 파일 없이 전체 결과를 포함하는 HTML을 얻을 수 있게 해줍니다. |
| EmbedCssOnly | `1` | CSS를 제외한 모든 참조된 파일(이미지 및 글꼴)을 별도로 두도록 강제합니다. 즉, CSS는 결과 HTML에 포함되고, 모든 다른 참조된 파일(이미지 및 글꼴)은 외부 부분으로 처리됩니다. 이는 다양한 브라우저에 적합한 HTML을 생성합니다. |
| NoEmbedding | `2` | 참조된 파일(CSS, 이미지, 글꼴)을 별도로 두도록 강제합니다. 이 접근 방식은 파일 세트를 생성하지만, 출력의 총 크기가 작아집니다(바이너리의 Base64 인코딩이 사용되지 않기 때문입니다). 또한 이러한 접근 방식은 다양한 브라우저에 적합한 HTML을 생성합니다. |

### 참조

* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)