---
title: Delegate HtmlSaveOptions.HtmlPageMarkupSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 변환 결과는 하나 이상의 HTML 페이지를 포함할 수 있으며, 이 페이지는 이미지나 글꼴과 같은 외부 파일을 참조할 수도 있습니다. 이 속성에 할당할 수 있는 위임자는 변환 중에 생성된 HTML 페이지(HTML 자체)의 처리를 구현하는 사용자 정의 메서드에서 생성됩니다. 이 경우 스트림이나 디스크에 저장하는 것과 같은 처리는 해당 사용자 정의 코드에서 수행될 수 있습니다. 이 경우 HTML 페이지 마크업을 저장하기 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 어떤 이유로 인해 이 경우의 처리가 변환기의 코드 자체에서 수행되어야 한다면, 사용자 정의 코드에서 'htmlSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오: 이는 변환기에 해당 리소스의 처리를 위한 모든 필요한 단계가 변환기 자체에서 수행되어야 한다는 신호를 보냅니다. 외부 사용자 정의 저장 코드가 없었던 것처럼 말입니다.
type: docs
weight: 5680
url: /ko/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavingstrategy/
---
## HtmlSaveOptions.HtmlPageMarkupSavingStrategy delegate

변환 결과는 하나 이상의 HTML 페이지(외부 파일인 이미지나 글꼴을 참조할 수 있음)를 포함할 수 있습니다. 이 속성에 할당할 수 있는 위임자는 변환 중에 생성된 HTML 페이지(HTML 자체)의 처리를 구현하는 사용자 정의 메서드에서 생성됩니다. 이 경우 스트림이나 디스크에 저장하는 것과 같은 처리는 해당 사용자 정의 코드에서 수행될 수 있습니다. 이 경우 HTML 페이지의 마크업을 저장하기 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 어떤 이유로 인해 이 경우의 처리가 변환기의 코드 자체에서 수행되어야 한다면, 사용자 정의 코드에서 'htmlSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오: 이는 변환기에 해당 리소스의 처리를 위한 모든 필요한 단계가 변환기 자체에서 수행되어야 한다는 신호를 보냅니다. 외부 사용자 정의 저장 코드가 없었던 것처럼 말입니다.

```csharp
public delegate void HtmlPageMarkupSavingStrategy(HtmlPageMarkupSavingInfo htmlSavingInfo);
```

| Parameter | Type | Description |
| --- | --- | --- |
| htmlSavingInfo | HtmlPageMarkupSavingInfo | 제공된 HTML 페이지를 저장하거나 처리하는 데 사용할 수 있는 데이터를 나타냅니다. |

### See Also

* class [HtmlPageMarkupSavingInfo](../htmlsaveoptions.htmlpagemarkupsavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)