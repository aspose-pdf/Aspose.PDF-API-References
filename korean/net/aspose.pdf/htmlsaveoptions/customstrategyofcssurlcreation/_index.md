---
title: HtmlSaveOptions.CustomStrategyOfCssUrlCreation
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions 필드. 이 필드는 URL 또는 다중 페이지 생성이 활성화된 경우 URL 템플릿을 반환하는 사용자 정의 메서드를 포함할 수 있습니다. 생성된 결과 HTML에 포함되어야 하는 주제 CSS의 세부 사항은 아래를 참조하십시오. 예를 들어, 변환기가 생성된 CSS에 표준 CSS 파일 이름 대신 특정 URL을 넣기를 원한다면, 원하는 URL을 생성하는 메서드를 생성하여 이 속성에 넣기만 하면 됩니다. 'SplitCssIntoPages' 플래그가 설정된 경우, 이 사용자 정의 전략（있는 경우）은 CSS의 정확한 URL이 아니라, 자리 표시자를 페이지 번호로 대체한 후 변환기 내부의 string.Format（） 함수로 해결될 수 있는 템플릿 문자열을 반환해야 합니다.
type: docs
weight: 300
url: /ko/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation 필드

이 필드는 URL(또는 다중 페이지 생성이 활성화된 경우 - 아래 세부 사항 참조)을 반환하는 사용자 정의 메서드를 포함할 수 있습니다. 생성된 결과 HTML에 포함되어야 하는 주제 CSS의 예를 들어, 변환기가 생성된 CSS에 표준 CSS 파일 이름 대신 특정 URL을 넣기를 원한다면, 원하는 URL을 생성하는 메서드를 생성하여 이 속성에 넣기만 하면 됩니다. 'SplitCssIntoPages' 플래그가 설정된 경우, 이 사용자 정의 전략(있는 경우)은 CSS의 정확한 URL이 아니라, 자리 표시자를 페이지 번호로 대체한 후 string.Format() 함수로 해결될 수 있는 템플릿 문자열을 반환해야 합니다. 이러한 경우 예상되는 반환 문자열의 예는: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')입니다.

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### 참조

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)