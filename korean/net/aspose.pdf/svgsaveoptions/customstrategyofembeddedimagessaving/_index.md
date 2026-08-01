---
title: "SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "SvgSaveOptions 필드. 이 필드는 변환 중에 존재할 경우 사용해야 하는 저장 전략을 포함할 수 있으며, 저장된 SVG에 포함된 BMP 또는 JPEG와 같은 외부 이미지 파일을 사용자 정의 방식으로 처리하기 위해 사용됩니다. 해당 전략은 리소스를 처리하고 생성된 SVG에서 저장된 리소스의 원하는 URI를 나타내는 문자열을 반환해야 합니다. 특정 파일에 대한 처리를 변환기 코드 자체에서 수행해야 하고 사용자 정의 코드에서 수행되지 않아야 하는 경우, 사용자 정의 코드 플래그 CustomProcessingCancelled를 imageSavingInfo 매개변수 변수에 설정하십시오. 이는 변환기에 해당 리소스 처리를 외부 사용자 정의 코드 없이 변환기 자체에서 수행해야 함을 알립니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving field

이 필드는 변환 중에 생성된 외부 이미지 파일(예: 임베드된 BMP 또는 JPEG)의 맞춤형 처리를 위해 사용해야 하는 저장 전략을 포함할 수 있습니다(존재하는 경우). 해당 전략은 리소스를 처리하고 생성된 SVG에서 저장된 리소스의 원하는 URI를 나타내는 문자열을 반환해야 합니다. 어떤 이유로 이 파일 또는 저 파일에 대한 처리를 변환기 코드 자체에서 수행해야 하고 사용자 정의 코드에서 수행하지 않아야 하는 경우, 사용자 정의 코드에서 'imageSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에 해당 리소스 처리를 외부 사용자 정의 코드 없이 변환기 자체에서 수행해야 함을 알립니다.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### 또 보기

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


