---
title: Delegate HtmlSaveOptions.CssSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 이 속성에 PDF를 HTML로 변환하는 동안 생성된 CSS의 일부를 처리하거나/및 저장하는 사용자 정의 전략을 할당할 수 있습니다. 이 경우 스트림이나 디스크에 저장하는 것과 같은 처리는 해당 사용자 정의 코드에서 수행되어야 합니다.
type: docs
weight: 5590
url: /ko/net/aspose.pdf/htmlsaveoptions.csssavingstrategy/
---
## HtmlSaveOptions.CssSavingStrategy delegate

이 속성에 PDF를 HTML로 변환하는 동안 생성된 CSS의 일부를 처리하거나/및 저장하는 사용자 정의 전략을 할당할 수 있습니다. 이 경우 처리(예: 스트림이나 디스크에 저장)는 해당 사용자 정의 코드에서 수행되어야 합니다.

```csharp
public delegate void CssSavingStrategy(CssSavingInfo partSavingInfo);
```

| Parameter | Type | Description |
| --- | --- | --- |
| partSavingInfo | CssSavingInfo | 제공된 CSS 부분을 저장하는 데 사용할 수 있는 데이터 집합을 나타냅니다. |

### See Also

* class [CssSavingInfo](../htmlsaveoptions.csssavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)