---
title: "HtmlSaveOptions.SplitCssIntoPages"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "HtmlSaveOptions 속성. 멀티 페이지 모드가 선택되고(SplitIntoPages가 true)이면 이 속성은 각 결과 HTML 페이지마다 별도의 CSS 파일을 생성할지 여부를 정의합니다. 기본값은 false이며, 이 경우 모든 페이지에 대해 하나의 큰 공통 CSS가 생성됩니다. 이 모드에서 생성된 모든 CSS의 총 크기는 페이지당 하나의 CSS가 생성될 경우 일반적으로 하나의 큰 CSS 파일보다 훨씬 큽니다. 왜냐하면 이전 경우에는 CSS 클래스가 여러 페이지의 여러 CSS 파일에 중복되기 때문입니다. 따라서 이 설정은 각 HTML 페이지를 독립적으로 처리하려는 경우에만 사용하는 것이 좋으며, 각 페이지별 CSS 크기가 가장 중요한 문제일 때만 사용해야 합니다."
type: docs
weight: 190
url: /ko/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages property

멀티페이지 모드가 선택된 경우(예: 'SplitIntoPages'가 'true'인 경우), 이 속성은 각 결과 HTML 페이지마다 별도의 CSS 파일을 생성할지 여부를 정의합니다. 기본값은 false이며, 따라서 모든 생성된 페이지에 대해 하나의 큰 공통 CSS가 생성됩니다. 이 모드에서 생성되는 모든 CSS(페이지당 하나의 CSS)의 총 크기는 일반적으로 하나의 큰 CSS 파일 크기보다 훨씬 큽니다. 이는 이전 경우에 CSS 클래스가 각 페이지별 여러 CSS 파일에 중복되기 때문입니다. 따라서 이 설정은 각 HTML 페이지를 독립적으로 처리하려는 경우에만 사용하는 것이 좋으며, 각 페이지별 CSS 크기가 가장 중요한 문제일 때 사용합니다.

```csharp
public bool SplitCssIntoPages { get; set; }
```

### 또 보기

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


