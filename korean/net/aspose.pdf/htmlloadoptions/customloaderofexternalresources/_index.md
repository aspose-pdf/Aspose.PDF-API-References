---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: HtmlLoadOptions 필드. 때때로 이미지나 CSS와 같은 외부 리소스의 내부 로더 사용을 피하고 요청된 리소스를 어딘가에서 가져오는 사용자 정의 방법을 제공해야 할 필요가 있습니다. 예를 들어, Aspose.PDF를 클라우드에서 사용할 때 참조된 파일에 직접 접근하는 것이 불가능한 경우, 이 경우 특별한 메서드에 넣은 사용자 정의 코드를 사용해야 하며, 그 메서드를 참조하는 델리게이트가 이 속성에 할당되어야 합니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources 필드

때때로 외부 리소스(이미지나 CSS와 같은)의 내부 로더 사용을 피하고 요청된 리소스를 어딘가에서 가져오는 사용자 정의 방법을 제공해야 할 필요가 있습니다. 예를 들어, Aspose.PDF를 클라우드에서 사용할 때 참조된 파일에 직접 접근하는 것이 불가능합니다: 이 경우 특별한 메서드에 넣은 사용자 정의 코드를 사용해야 하며, 그 메서드를 참조하는 델리게이트가 이 속성에 할당되어야 합니다.

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### 참조

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)