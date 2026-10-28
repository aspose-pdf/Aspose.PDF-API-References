---
title: "Delegate SvgSaveOptions.EmbeddedImagesSavingStrategy"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "이와 같은 유형의 속성에 대해, PDF에서 생성된 SVG에서 추출된 이미지를 외부 리소스로 저장해야 하는 경우를 처리하는 사용자 정의 메서드에서 만든 대리자를 할당할 수 있습니다. 이렇게 하면 스트림이나 디스크에 직접 저장하는 작업을 사용자 코드에서 수행할 수 있으며, 해당 코드는 따옴표 없이 경로나 다른 문자열을 반환해야 합니다. 반환된 문자열은 원래 이미지 리소스 경로 대신 생성된 SVG에 삽입됩니다. 이미지 저장을 위한 모든 필요한 작업은 제공된 메서드 코드에서 수행되어야 하며, 변환기 코드에서 결과를 저장하는 것은 사용되지 않습니다. 특정 파일에 대한 처리를 변환기 코드 자체에서 수행해야 하는 경우(사용자 코드가 아닌) 사용자 코드에서 `CustomProcessingCancelled` 플래그를 `imageSavingInfo` 매개변수 변수에 설정하십시오. 이는 변환기에게 해당 리소스 처리를 외부 사용자 코드 없이 변환기 자체에서 수행하도록 신호를 보냅니다. 저장된 이미지에 대한 정보는 사용자 코드에서 사용할 수 있으며, 이미지의 URL을 나타내는 문자열을 반환해야 SVG에 삽입됩니다."
type: docs
weight: 10420
url: /ko/net/aspose.pdf/svgsaveoptions.embeddedimagessavingstrategy/
---
## SvgSaveOptions.EmbeddedImagesSavingStrategy delegate

이와 같은 유형의 속성에 대해, PDF에서 생성된 SVG에서 추출된 이미지를 외부 리소스로 저장해야 하는 경우를 처리하는 사용자 정의 메서드에서 만든 대리자를 할당할 수 있습니다. 이렇게 하면 스트림이나 디스크에 직접 저장하는 작업을 사용자 코드에서 수행할 수 있으며, 해당 코드는 경로(또는 따옴표 없이 다른 문자열)를 반환해야 합니다. 반환된 문자열은 원래 이미지 리소스 경로 대신 생성된 SVG에 삽입됩니다. 이미지 저장을 위한 모든 필요한 작업은 제공된 메서드 코드에서 수행되어야 하며, 변환기 코드에서 결과를 저장하는 것은 사용되지 않습니다. 특정 파일에 대한 처리를 변환기 코드 자체에서 수행해야 하는 경우(사용자 코드가 아닌), 사용자 코드에서 'CustomProcessingCancelled' 플래그를 'imageSavingInfo' 매개변수 변수에 설정하십시오. 이는 변환기에게 해당 리소스 처리를 외부 사용자 코드 없이 변환기 자체에서 수행하도록 신호를 보냅니다. 저장된 이미지에 대한 정보는 사용자 코드에서 사용할 수 있으며, 이미지의 URL을 나타내는 문자열을 반환해야 SVG에 삽입됩니다.

```csharp
public delegate string EmbeddedImagesSavingStrategy(SvgImageSavingInfo imageSavingInfo);
```

### 또 보기

* class [SvgImageSavingInfo](../svgsaveoptions.svgimagesavinginfo/)
* class [SvgSaveOptions](../svgsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


