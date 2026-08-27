---
title: "델리게이트 HtmlSaveOptions.HtmlPageMarkupSavingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "변환 결과에는 이미지나 글꼴과 같은 외부 파일을 참조할 수 있는 하나 이상의 HTML 페이지가 포함될 수 있습니다. 이 속성에 변환 중에 생성된 HTML 페이지 자체를 처리하는 사용자 정의 메서드에서 만든 델리게이트를 할당할 수 있습니다. 이러한 경우 스트림이나 디스크에 저장하는 등의 처리를 해당 사용자 정의 코드에서 수행할 수 있습니다. 이 경우 HTML 페이지 마크업 저장을 위한 모든 필요한 작업은 제공된 메서드 코드에서 수행되어야 합니다. 변환기 코드 자체에서 결과 저장이 사용되지 않기 때문입니다. 어떤 이유로든 이 경우 처리를 변환기 코드 자체에서 수행해야 한다면, 사용자 정의 코드에서 htmlSavingInfo 매개변수 변수의 플래그 CustomProcessingCancelled 를 설정하십시오. 이는 변환기에 해당 리소스 처리를 외부 사용자 정의 저장 코드가 없었던 것처럼 변환기 자체에서 수행하도록 신호를 보냅니다."
type: docs
weight: 5810
url: /ko/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

변환 결과에는 이미지나 글꼴과 같은 외부 파일을 참조할 수 있는 하나 이상의 HTML 페이지가 포함될 수 있습니다. 이 속성에 변환 중에 생성된 HTML 페이지(HTML 자체)를 처리하는 사용자 정의 메서드에서 만든 델리게이트를 할당할 수 있습니다. 이러한 경우 스트림이나 디스크에 저장하는 등의 처리를 해당 사용자 정의 코드에서 수행할 수 있습니다. 이 경우 HTML 페이지 마크업 저장을 위한 모든 필요한 작업은 제공된 메서드 코드에서 수행되어야 합니다. 변환기 코드에서 결과 저장이 사용되지 않기 때문입니다. 어떤 이유로든 이 경우 처리를 변환기 코드 자체에서 수행해야 한다면, 사용자 정의 코드에서 'htmlSavingInfo' 매개변수 변수의 플래그 'CustomProcessingCancelled' 를 설정하십시오. 이는 변환기에 해당 리소스 처리를 외부 사용자 정의 저장 코드가 없었던 것처럼 변환기 자체에서 수행하도록 신호를 보냅니다.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | 제공된 HTML 페이지의 저장 또는 처리를 위해 사용할 수 있는 데이터를 나타냅니다. |

### 또 보기

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


