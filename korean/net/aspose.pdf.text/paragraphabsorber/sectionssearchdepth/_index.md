---
title: "ParagraphAbsorber.SectionsSearchDepth"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ParagraphAbsorber 속성. 구조의 보다 세부적인 요소에 대해 순차적으로 검색을 수행할 횟수를 지정하는 값을 가져오거나 설정합니다. 기본 검색 깊이는 3이며, 이는 수평으로 구분된 섹션, 헤더, 단락 등을 세 번 검색하고, 수직으로 구분된 열에 대해서도 세 번 검색함을 의미합니다."
type: docs
weight: 50
url: /ko/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

구조의 더 세부적인 요소에 대해 순차 검색을 수행할 횟수를 지정하는 값을 가져오거나 설정합니다. 기본 검색 깊이는 3이며, 이는 수평으로 구분된 섹션(헤더, 단락 등)에 대해 세 번, 수직으로 구분된 섹션(열 등)에 대해 세 번 검색한다는 의미입니다.

```csharp
public int SectionsSearchDepth { get; set; }
```

## 비고

이 값을 증가시키면 검색 결과에 눈에 띄는 변화 없이 성능이 약간 감소할 수 있습니다. 값을 감소시키면 섹션 내 단락을 올바르게 판단하지 못할 수 있습니다. 페이지 구조의 'rough' 요소만 얻고자 하지 않는 한 기본값보다 낮게 설정하는 것은 권장하지 않습니다.

### 또 보기

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


