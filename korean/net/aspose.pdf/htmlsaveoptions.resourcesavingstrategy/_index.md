---
title: "델리게이트 HtmlSaveOptions.ResourceSavingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "이 속성에는 PDF에서 추출되어 PDF를 HTML로 변환하는 동안 외부 리소스로 저장되어야 하는 외부 리소스 Font 또는 Image를 처리하는 사용자 정의 메서드에서 만든 델리게이트를 할당할 수 있습니다. 이러한 경우 스트림이나 디스크에 저장하는 등의 처리는 해당 사용자 정의 코드에서 수행할 수 있으며, 해당 코드에서는 따옴표 없이 경로 또는 다른 문자열을 반환해야 합니다. 반환된 문자열은 원래 이미지 리소스의 경로 대신 생성된 HTML에 삽입됩니다. 또한 이미지 저장을 위한 모든 필요한 작업은 제공된 메서드 코드에서 수행되어야 하며, 변환기 코드에서 결과를 저장하는 것은 사용되지 않습니다. 특정 파일에 대한 처리를 변환기 코드 자체에서 수행해야 하는 경우(사용자 정의 코드가 아닌) 사용자 정의 코드에서 resourceSavingInfo 매개변수의 CustomProcessingCancelled 플래그를 설정하십시오. 이는 변환기에게 해당 리소스 처리를 외부 사용자 정의 코드 없이 변환기 자체에서 수행하도록 신호를 보냅니다."
type: docs
weight: 5860
url: /ko/net/aspose.pdf/htmlsaveoptions.resourcesavingstrategy/
---
## HtmlSaveOptions.ResourceSavingStrategy delegate

이 속성에는 PDF에서 추출되어 PDF를 HTML로 변환하는 동안 외부 리소스로 저장되어야 하는 외부 리소스 (Font 또는 Image)를 처리하는 사용자 정의 메서드에서 만든 델리게이트를 할당할 수 있습니다. 이러한 경우 스트림이나 디스크에 저장하는 등과 같은 처리는 해당 사용자 정의 코드에서 수행할 수 있으며, 해당 코드는 경로(또는 따옴표 없이 다른 문자열)를 반환해야 합니다. 반환된 문자열은 원래 이미지 리소스의 경로 대신 생성된 HTML에 삽입됩니다. 또한 이미지 저장을 위한 모든 필요한 작업은 제공된 메서드 코드에서 수행되어야 하며, 변환기 코드에서 결과를 저장하는 것은 사용되지 않습니다. 특정 파일에 대한 처리를 변환기 코드 자체에서 수행해야 하는 경우(사용자 정의 코드가 아닌) 사용자 정의 코드에서 'resourceSavingInfo' 매개변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스 처리를 외부 사용자 정의 코드 없이 변환기 자체에서 수행하도록 신호를 보냅니다.

```csharp
public delegate string ResourceSavingStrategy(ResourceSavingInfo resourceSavingInfo);
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| resourceSavingInfo | ResourceSavingInfo | 리소스 저장을 위한 데이터 집합을 나타냅니다. |

### 반환 값

HTML 생성 중에 사용될 저장된 리소스의 URL을 반환해야 합니다.

### 또 보기

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


