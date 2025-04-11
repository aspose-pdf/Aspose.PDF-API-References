---
title: RenderingOptions.AnalyzeFonts
second_title: Aspose.PDF for .NET API Reference
description: RenderingOptions 속성. 텍스트의 모든 문자가 표시될 수 있도록 필요에 따라 글꼴을 교체합니다. 글꼴 대체 알고리즘은 다음 단계를 따릅니다. 1. 사용자가 DefaultFontName 속성을 명시적으로 설정한 경우, 지정된 글꼴이 원하는 문자를 표시할 수 있는지 확인합니다. 2. 사용자 정의 글꼴이 설정되지 않은 경우, !:FontRepository.Sources를 통해 추가된 글꼴을 검색합니다. 3. 텍스트를 분석하여 해당 알파벳 또는 스크립트를 식별하고 그에 따라 글꼴 이름을 제안합니다. 이러한 글꼴을 시스템에서 찾고 사용하려고 시도합니다. 4. 대체로, 필요한 문자를 표시할 수 있는 글꼴을 시스템에서 검색합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf/renderingoptions/analyzefonts/
---
## RenderingOptions.AnalyzeFonts 속성

필요에 따라 글꼴을 교체하여 텍스트의 모든 문자가 표시될 수 있도록 합니다. 글꼴 대체 알고리즘은 다음 단계를 따릅니다: 1. 사용자가 DefaultFontName 속성을 명시적으로 설정한 경우, 지정된 글꼴이 원하는 문자를 표시할 수 있는지 확인합니다. 2. 사용자 정의 글꼴이 설정되지 않은 경우, !:FontRepository.Sources를 통해 추가된 글꼴을 검색합니다. 3. 텍스트를 분석하여 해당 알파벳 또는 스크립트를 식별하고 그에 따라 글꼴 이름을 제안합니다. 이러한 글꼴을 시스템에서 찾고 사용하려고 시도합니다. 4. 대체로, 필요한 문자를 표시할 수 있는 글꼴을 시스템에서 검색합니다.

```csharp
public bool AnalyzeFonts { get; set; }
```

### 참조

* 클래스 [RenderingOptions](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)