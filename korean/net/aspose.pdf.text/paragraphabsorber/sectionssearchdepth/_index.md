---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: ParagraphAbsorber 속성. 구조의 더 세부적인 요소에 대한 연속 검색이 몇 번 수행될지를 지시하는 값을 가져오거나 설정합니다. 기본 검색 깊이는 3입니다. 이는 수평으로 나누어진 섹션(헤더, 단락 등)에 대해 세 번, 수직으로 나누어진 섹션(열)에 대해 세 번의 검색을 의미합니다.
type: docs
weight: 50
url: /ko/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth 속성

구조의 더 세부적인 요소에 대한 연속 검색이 몇 번 수행될지를 지시하는 값을 가져오거나 설정합니다. 기본 검색 깊이는 3입니다. 이는 수평으로 나누어진 섹션(헤더, 단락 등)에 대해 세 번, 수직으로 나누어진 섹션(열)에 대해 세 번의 검색을 의미합니다.

```csharp
public int SectionsSearchDepth { get; set; }
```

## 비고

이 값을 증가시키면 검색 결과에 눈에 띄는 변화 없이 성능이 약간 감소할 수 있습니다. 이 값을 감소시키면 섹션 내 단락의 잘못된 결정으로 이어질 수 있습니다. 페이지 구조의 '거친' 요소만 얻고자 하지 않는다면 기본값보다 낮은 값을 설정하는 것을 권장하지 않습니다.

### 참조

* 클래스 [ParagraphAbsorber](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)