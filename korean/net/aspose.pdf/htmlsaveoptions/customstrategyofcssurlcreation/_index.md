---
title: "HtmlSaveOptions.CustomStrategyOfCssUrlCreation"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "HtmlSaveOptions 필드. 이 필드는 다중 페이지 생성이 활성화된 경우 URL 또는 URL 템플릿을 반환하는 사용자 정의 메서드를 포함할 수 있습니다. 아래에서 설명하는 CSS가 생성된 HTML 결과에 어떻게 삽입되어야 하는지에 대한 자세한 내용을 확인하십시오. 예를 들어 변환기가 표준 CSS 파일 이름 대신 특정 URL을 생성된 CSS에 넣도록 하려면 원하는 URL을 생성하는 메서드를 만들고 이 속성에 지정하면 됩니다. SplitCssIntoPages 플래그가 설정된 경우 이 사용자 정의 전략은 CSS의 정확한 URL이 아니라 페이지 번호 자리표시자를 문자열.Format 함수로 대체하여 해당 페이지의 CSS URL로 변환할 수 있는 템플릿 문자열을 반환해야 합니다. 이러한 경우 예상되는 반환 문자열 예시는 SomeTargetLocationpage_0.css../PartHandlers/GetCss.aspxDocumentId45654CssPage0 입니다."
type: docs
weight: 300
url: /ko/net/aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/
---
## HtmlSaveOptions.CustomStrategyOfCssUrlCreation field

이 필드는 생성된 결과 HTML에 삽입될 CSS의 URL(또는 멀티페이지 생성이 활성화된 경우 URL 템플릿—아래 세부 사항 참조)을 반환하는 사용자 정의 메서드를 포함할 수 있습니다. 예를 들어 변환기가 표준 CSS 파일 이름 대신 특정 URL을 삽입하도록 하려면 원하는 URL을 생성하는 메서드를 만들고 이 속성에 할당하면 됩니다. 'SplitCssIntoPages' 플래그가 설정된 경우, 이 사용자 정의 전략(있는 경우)은 CSS의 정확한 URL이 아니라 페이지 번호를 자리표시자로 대체한 후(string.Format() 함수 사용) 각 페이지의 CSS URL로 해석될 수 있는 템플릿 문자열을 반환해야 합니다. 이러한 경우 예상되는 반환 문자열 예시는 다음과 같습니다: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}')

```csharp
public CssUrlMakingStrategy CustomStrategyOfCssUrlCreation;
```

### 또 보기

* delegate [CssUrlMakingStrategy](../../htmlsaveoptions.cssurlmakingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


