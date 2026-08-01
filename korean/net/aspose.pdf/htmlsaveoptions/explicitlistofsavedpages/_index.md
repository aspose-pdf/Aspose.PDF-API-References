---
title: "HtmlSaveOptions.ExplicitListOfSavedPages"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "HtmlSaveOptions 속성. 이 속성을 사용하면 문서의 어떤 페이지를 변환할지 명시적으로 정의할 수 있습니다. 이 목록의 페이지 번호는 1부터 시작해야 합니다. 즉, 유효한 페이지 번호는 1...NumberOfPagesInConvertedDocument 범위 내에 있어야 합니다. 목록에 나타나는 페이지 순서는 결과 HTML 페이지의 순서에 영향을 주지 않으며, 결과 페이지는 항상 원본 PDF에 존재하는 순서대로 표시됩니다. 이 목록이 null(기본값)인 경우 모든 페이지가 변환됩니다. 목록에 있는 페이지 번호가 현재 문서의 페이지 범위를 벗어나면 amountOfPagesInDocument 예외가 발생합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

이 속성을 사용하면 Document의 어떤 페이지를 변환할지 명시적으로 정의할 수 있습니다. 이 목록의 페이지는 1부터 시작하는 번호여야 합니다. 즉, 페이지 번호는 범위 (1...[NumberOfPagesInConvertedDocument]) 내에서 선택되어야 합니다. 목록에 나타나는 순서는 결과 HTML 페이지의 순서에 영향을 주지 않으며, 결과 페이지는 원본 PDF에 존재하는 순서대로 표시됩니다. 이 목록이 null(기본값)인 경우 모든 페이지가 변환됩니다. 목록에 있는 페이지 번호가 존재하는 페이지 범위(1-[amountOfPagesInDocument])를 벗어나면 예외가 발생합니다.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### 또 보기

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


