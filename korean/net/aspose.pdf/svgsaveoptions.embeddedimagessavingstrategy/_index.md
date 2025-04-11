---
title: Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 이러한 유형의 속성에 대해 PDF에서 생성된 SVG에서 추출된 이미지를 외부 리소스로 저장해야 하는 외부 저장 처리를 구현하는 사용자 정의 메서드에서 생성된 델리게이트를 할당할 수 있습니다. 이 경우 스트림이나 디스크에 직접 저장하는 것과 같은 처리는 해당 사용자 정의 코드에서 수행될 수 있으며, 해당 사용자 정의 코드는 이후 생성된 SVG에 원래 이미지 리소스의 경로 대신 통합될 경로(또는 따옴표 없이 다른 문자열)를 반환해야 합니다. 이 경우 이미지 저장을 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 어떤 이유로 이 파일이나 저 파일의 처리가 변환기 코드 자체에서 수행되어야 하는 경우, 사용자 정의 코드에서 'imageSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스의 처리를 위한 모든 필요한 단계가 외부 사용자 정의 코드가 없는 것처럼 변환기 자체에서 수행되어야 함을 알립니다. 저장된 이미지에 대한 정보는 사용자 정의 코드에서 사용할 수 있으며, SVG에 삽입될 이미지의 URL을 나타내는 문자열을 반환해야 합니다.
type: docs
weight: 10240
url: /ko/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

이러한 유형의 속성에 대해 PDF에서 생성된 SVG에서 추출된 이미지를 외부 리소스로 저장해야 하는 외부 저장 처리를 구현하는 사용자 정의 메서드에서 생성된 델리게이트를 할당할 수 있습니다. 이 경우 처리(예: 스트림이나 디스크에 직접 저장)는 해당 사용자 정의 코드에서 수행될 수 있으며, 해당 사용자 정의 코드는 이후 생성된 SVG에 원래 이미지 리소스의 경로 대신 통합될 경로(또는 따옴표 없이 다른 문자열)를 반환해야 합니다. 이 경우 이미지 저장을 위한 모든 필요한 작업은 제공된 메서드의 코드에서 수행되어야 하며, 변환기의 코드에서 결과를 저장하는 것은 사용되지 않습니다. 어떤 이유로 이 파일이나 저 파일의 처리가 변환기 코드 자체에서 수행되어야 하는 경우, 사용자 정의 코드에서 'imageSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스의 처리를 위한 모든 필요한 단계가 외부 사용자 정의 코드가 없는 것처럼 변환기 자체에서 수행되어야 함을 알립니다. 저장된 이미지에 대한 정보는 사용자 정의 코드에서 사용할 수 있으며, SVG에 삽입될 이미지의 URL을 나타내는 문자열을 반환해야 합니다.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### See Also

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)