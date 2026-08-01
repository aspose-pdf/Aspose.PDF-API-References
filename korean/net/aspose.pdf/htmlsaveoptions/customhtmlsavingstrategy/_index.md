---
title: "HtmlSaveOptions.CustomHtmlSavingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "HtmlSaveOptions 필드. 변환 결과는 하나 이상의 HTML 페이지를 포함할 수 있습니다. 이 속성에 변환 중에 생성된 외부 링크 파일이 없는 정확한 마크업 HTML을 처리하는 사용자 정의 메서드에서 만든 대리자를 할당할 수 있습니다. 이러한 경우 HTML 페이지를 스트림이나 디스크에 저장하는 등의 처리를 해당 사용자 정의 코드에서 수행할 수 있습니다. 따라서 HTML 페이지 저장에 필요한 모든 작업은 제공된 메서드 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 만약 어떤 경우에든 처리를 변환기 자체 코드에서 수행해야 한다면, 사용자 정의 코드에서 htmlSavingInfo 매개변수의 CustomProcessingCancelled 플래그를 설정하십시오. 이는 해당 리소스 처리를 외부 사용자 정의 코드 없이 변환기 자체에서 수행하도록 변환기에 신호를 보냅니다."
type: docs
weight: 270
url: /ko/net/aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/
---
## HtmlSaveOptions.CustomHtmlSavingStrategy field

변환 결과는 하나 이상의 HTML 페이지를 포함할 수 있습니다. 이 속성에 변환 중에 생성된 하나의 HTML 페이지(정확히는 마크업 HTML이며 외부 링크 파일이 없는 경우)를 처리하는 사용자 정의 메서드에서 만든 대리자를 할당할 수 있습니다. 이렇게 하면 페이지 HTML을 스트림이나 디스크에 저장하는 등의 처리를 해당 사용자 정의 코드에서 수행할 수 있습니다. 따라서 HTML 페이지 저장에 필요한 모든 작업은 제공된 메서드 코드에서 수행되어야 하며, 변환기의 코드에서 결과 저장이 사용되지 않습니다. 만약 어떤 이유로든 해당 처리를 변환기 자체 코드에서 수행해야 한다면, 사용자 정의 코드에서 'htmlSavingInfo' 매개변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에 외부 사용자 정의 코드가 없었던 것처럼 해당 리소스 처리를 변환기 자체에서 수행하도록 신호를 보냅니다.

```csharp
public HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy;
```

### 또 보기

* delegate [HtmlPageMarkupSavingStrategy](../../htmlsaveoptions.htmlpagemarkupsavingstrategy/)
* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


