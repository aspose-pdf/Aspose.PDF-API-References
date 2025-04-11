---
title: Delegate HtmlSaveOptions.ResourceSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 이 속성에는 PDF에서 추출된 외부 리소스(Font 또는 Image)를 처리하는 사용자 정의 메서드에서 생성된 델리게이트를 할당할 수 있습니다. 이 리소스는 PDF를 HTML로 변환하는 동안 외부 리소스로 저장되어야 합니다. 이 경우 스트림이나 디스크에 저장하는 것과 같은 처리는 해당 사용자 정의 코드에서 수행될 수 있으며, 해당 사용자 정의 코드는 이후 생성된 HTML에 통합될 원래의 이미지 리소스 경로 대신 사용할 경로(또는 따옴표가 없는 다른 문자열)를 반환해야 합니다. 이 경우 이미지 저장을 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 어떤 이유로 이 파일에 대한 처리가 사용자 정의 코드가 아닌 변환기 코드 자체에 의해 수행되어야 하는 경우, 사용자 정의 코드에서 'resourceSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스의 처리를 위한 모든 필요한 단계가 외부 사용자 정의 코드가 없는 것처럼 변환기 자체에서 수행되어야 함을 신호합니다.
type: docs
weight: 5730
url: /ko/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

이 속성에는 PDF에서 추출된 외부 리소스(Font 또는 Image)를 처리하는 사용자 정의 메서드에서 생성된 델리게이트를 할당할 수 있습니다. 이 리소스는 PDF를 HTML로 변환하는 동안 외부 리소스로 저장되어야 합니다. 이 경우 처리(예: 스트림이나 디스크에 저장)는 해당 사용자 정의 코드에서 수행될 수 있으며, 해당 사용자 정의 코드는 이후 생성된 HTML에 통합될 원래의 이미지 리소스 경로 대신 사용할 경로(또는 따옴표가 없는 다른 문자열)를 반환해야 합니다. 이 경우 이미지 저장을 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 어떤 이유로 이 파일에 대한 처리가 사용자 정의 코드가 아닌 변환기 코드 자체에 의해 수행되어야 하는 경우, 사용자 정의 코드에서 'resourceSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스의 처리를 위한 모든 필요한 단계가 외부 사용자 정의 코드가 없는 것처럼 변환기 자체에서 수행되어야 함을 신호합니다.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | 리소스 저장을 위한 데이터 집합을 나타냅니다. |

### 반환 값

저장된 리소스의 URL을 반환해야 하며, 이는 HTML 생성 중에 사용됩니다.

### 참조

* 클래스 [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)