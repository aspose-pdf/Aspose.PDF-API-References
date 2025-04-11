---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 때때로 이미지나 CSS와 같은 외부 리소스의 내부 로더 사용을 피하고 요청된 리소스를 어딘가에서 가져오는 사용자 정의 방법을 제공해야 할 필요가 있습니다. 예를 들어 Aspose.Pdf를 클라우드에서 사용할 때 참조된 파일에 직접 접근하는 것은 불가능하며, 특별한 메서드에 넣은 사용자 정의 코드를 사용해야 합니다. 이 델리게이트는 이러한 사용자 정의 메서드의 서명을 정의합니다.
type: docs
weight: 6160
url: /ko/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

때때로 외부 리소스(이미지나 CSS와 같은)의 내부 로더 사용을 피하고 요청된 리소스를 어딘가에서 가져오는 사용자 정의 방법을 제공해야 할 필요가 있습니다. 예를 들어 Aspose.Pdf를 클라우드에서 사용할 때 참조된 파일에 직접 접근하는 것은 불가능하며, 특별한 메서드에 넣은 사용자 정의 코드를 사용해야 합니다. 이 델리게이트는 이러한 사용자 정의 메서드의 서명을 정의합니다.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| Parameter | Type | Description |
| --- | --- | --- |
| resourceURI | String | 리소스 URI. |

### Return Value

ResourceLoadingResult 객체.

### See Also

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)