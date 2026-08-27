---
title: "델리게이트 LoadOptions.ResourceLoadingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "때때로 외부 리소스(이미지나 CSS 등)의 내부 로더 사용을 피하고, 요청된 리소스를 어느 곳에서든 가져오는 사용자 정의 메서드를 제공해야 할 필요가 있습니다. 예를 들어 클라우드 환경에서 Aspose.Pdf를 사용할 때 참조된 파일에 직접 접근할 수 없으며, 특수 메서드에 넣은 일부 사용자 정의 코드를 사용해야 합니다. 이 델리게이트는 이러한 사용자 정의 메서드의 시그니처를 정의합니다."
type: docs
weight: 6300
url: /ko/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

때때로 외부 리소스(이미지나 CSS 등)의 내부 로더 사용을 피하고, 요청된 리소스를 어느 곳에서든 가져오는 사용자 정의 메서드를 제공해야 합니다. 예를 들어 클라우드 환경에서 Aspose.Pdf를 사용할 때 참조된 파일에 직접 접근할 수 없으며, 특수 메서드에 넣은 일부 사용자 정의 코드를 사용해야 합니다. 이 델리게이트는 이러한 사용자 정의 메서드의 시그니처를 정의합니다.

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resourceURI | String | 리소스 URI. |

### 반환 값

ResourceLoadingResult 객체.

### 또 보기

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


