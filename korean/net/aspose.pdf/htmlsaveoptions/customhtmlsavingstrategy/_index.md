---
title: HtmlSaveOptions.CustomHtmlSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions 필드. 변환 결과는 하나 이상의 HTML 페이지를 포함할 수 있습니다. 이 속성에 할당할 수 있는 위임자는 변환 중에 생성된 외부 링크 파일 없이 하나의 HTML 페이지를 정확하게 처리하는 사용자 정의 메서드에서 생성됩니다. 이러한 경우 HTML 페이지를 스트림이나 디스크에 저장하는 것과 같은 처리는 해당 사용자 정의 코드에서 수행될 수 있습니다. 이 경우 HTML 페이지를 저장하기 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 어떤 이유로 이 경우의 처리가 사용자 정의 코드가 아닌 변환기 코드 자체에서 수행되어야 하는 경우, 사용자 정의 코드에서 'htmlSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오 이는 변환기에 해당 리소스의 처리를 위한 모든 필요한 단계가 변환기 자체에서 수행되어야 함을 신호합니다. 마치 외부 사용자 정의 코드가 없는 것처럼 처리됩니다.
type: docs
weight: 270
url: /ko/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy 필드

변환 결과는 하나 이상의 HTML 페이지를 포함할 수 있습니다. 이 속성에 할당할 수 있는 위임자는 변환 중에 생성된 외부 링크 파일 없이 하나의 HTML 페이지를 정확하게 처리하는 사용자 정의 메서드에서 생성됩니다. 이러한 경우 HTML 페이지의 HTML을 스트림이나 디스크에 저장하는 것과 같은 처리는 해당 사용자 정의 코드에서 수행될 수 있습니다. 이 경우 HTML 페이지를 저장하기 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 어떤 이유로 이 경우의 처리가 변환기 코드 자체에서 수행되어야 하는 경우, 사용자 정의 코드에서 'htmlSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오: 이는 변환기에 해당 리소스의 처리를 위한 모든 필요한 단계가 변환기 자체에서 수행되어야 함을 신호합니다. 마치 외부 사용자 정의 코드가 없는 것처럼 처리됩니다.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### 참조

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)