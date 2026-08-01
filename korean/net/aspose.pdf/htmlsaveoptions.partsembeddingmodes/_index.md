---
title: "열거형 HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes 열거형. 이 열거형은 HTML에서 참조되는 파일들의 임베드 가능한 모드를 나열합니다. 참조된 파일 HTML, FontsImages, CSSes가 메인 HTML 파일에 포함될지 별도의 바이너리 엔터티로 생성될지를 제어할 수 있습니다."
type: docs
weight: 5840
url: /ko/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

이 열거형은 HTML에서 참조되는 파일들의 임베드 가능한 모드를 나열합니다. 참조된 파일(HTML, Fonts, Images, CSSes)이 메인 HTML 파일에 포함될지 별도의 바이너리 엔터티로 생성될지를 제어할 수 있습니다.

```csharp
public enum PartsEmbeddingModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | 모든 참조 파일(Css, Images, Fonts)을 생성된 HTML 마크업(즉, HTML 자체)에 포함하도록 강제합니다. 이 방식은 하나의 HTML 파일을 생성하지만, 출력 전체 크기가 Base64 인코딩으로 인해 커집니다. 또한 모든 브라우저(특히 레거시 브라우저)가 HTML에 포함된 바이너리를 정상적으로 처리하지 못할 수 있습니다. 하지만 추가 파일 없이 전체 결과를 포함하는 HTML을 얻을 수 있습니다. |
| EmbedCssOnly | `1` | CSS를 제외한 모든 참조 파일(Images 및 Fonts)을 별도로 배치하도록 강제합니다. 즉, CSS는 결과 HTML에 포함되고, 다른 참조 파일(Images 및 Fonts)은 외부 파트로 처리됩니다. 이 방식은 다양한 브라우저에서 호환되는 HTML을 생성합니다. |
| NoEmbedding | `2` | 참조 파일(Css, Images, Fonts)을 별도로 배치하도록 강제합니다. 이 방식은 파일 집합을 생성하지만, 바이너리의 Base64 인코딩이 없기 때문에 출력 전체 크기가 작아집니다. 또한 이러한 방식은 다양한 브라우저에 적합한 HTML을 생성합니다. |

### 또 보기

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


