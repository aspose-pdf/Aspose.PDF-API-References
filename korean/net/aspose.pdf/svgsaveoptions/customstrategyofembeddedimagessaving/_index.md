---
title: SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions 필드. 이 필드는 변환 중에 존재하는 경우 사용해야 하는 저장 전략을 포함할 수 있으며, 저장된 SVG에 내장된 BMP 또는 JPEG와 같은 생성된 참조 외부 이미지 파일의 맞춤형 처리를 위해 사용됩니다. 이 전략은 리소스를 처리하고 생성된 SVG에서 저장된 리소스의 바람직한 URI를 나타내는 문자열을 반환해야 합니다. 어떤 이유로 이 파일이나 저 파일의 처리가 사용자 정의 코드가 아닌 변환기 코드 자체에 의해 수행되어야 하는 경우, 사용자 정의 코드에서 'imageSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스의 처리를 위한 모든 필요한 단계가 외부 사용자 정의 코드가 없는 것처럼 변환기 자체에서 수행되어야 함을 신호합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/
---
## SvgSaveOptions.CustomStrategyOfEmbeddedImagesSaving 필드

이 필드는 변환 중에 존재하는 경우 사용해야 하는 저장 전략을 포함할 수 있으며, 저장된 SVG에 내장된 BMP 또는 JPEG와 같은 생성된 참조 외부 이미지 파일의 맞춤형 처리를 위해 사용됩니다. 이 전략은 리소스를 처리하고 생성된 SVG에서 저장된 리소스의 바람직한 URI를 나타내는 문자열을 반환해야 합니다. 어떤 이유로 이 파일이나 저 파일의 처리가 변환기의 코드 자체에 의해 수행되어야 하는 경우, 사용자 정의 코드에서 'imageSavingInfo' 매개변수 변수의 'CustomProcessingCancelled' 플래그를 설정하십시오. 이는 변환기에게 해당 리소스의 처리를 위한 모든 필요한 단계가 외부 사용자 정의 코드가 없는 것처럼 변환기 자체에서 수행되어야 함을 신호합니다.

```csharp
public EmbeddedImagesSavingStrategy CustomStrategyOfEmbeddedImagesSaving;
```

### 참조

* delegate [EmbeddedImagesSavingStrategy](../../svgsaveoptions.embeddedimagessavingstrategy/)
* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)