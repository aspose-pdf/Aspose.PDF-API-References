---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions 속성. 이 속성을 사용하면 변환할 문서의 페이지를 명시적으로 정의할 수 있습니다. 이 목록의 페이지는 1 기반 번호를 가져야 합니다. 즉, 유효한 페이지 번호는 (1...NumberOfPagesInConvertedDocument) 범위에서 가져와야 합니다. 이 목록에 있는 페이지의 나타나는 순서는 결과 HTML 페이지의 순서에 영향을 미치지 않습니다 - 결과 페이지는 항상 원본 PDF에 있는 순서대로 표시됩니다. 이 목록이 null인 경우(기본값으로) 모든 페이지가 변환됩니다. 이 목록의 페이지 번호가 현재 페이지의 범위를 벗어나면(1-[amountOfPagesInDocument]) 예외가 발생합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages 속성

이 속성을 사용하면 변환할 문서의 페이지를 명시적으로 정의할 수 있습니다. 이 목록의 페이지는 1 기반 번호를 가져야 합니다. 즉, 유효한 페이지 번호는 (1...[NumberOfPagesInConvertedDocument]) 범위에서 가져와야 합니다. 이 목록에 있는 페이지의 나타나는 순서는 결과 HTML 페이지의 순서에 영향을 미치지 않습니다 - 결과 페이지는 항상 원본 PDF에 있는 순서대로 표시됩니다. 이 목록이 null인 경우(기본값으로) 모든 페이지가 변환됩니다. 이 목록의 페이지 번호가 현재 페이지의 범위를 벗어나면(1-[amountOfPagesInDocument]) 예외가 발생합니다.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### 참조

* 클래스 [HtmlSaveOptions](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)