---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsResourceLoadingResult 클래스. 리소스의 사용자 정의 로딩 결과
type: docs
weight: 6150
url: /ko/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult 클래스

리소스의 사용자 정의 로딩 결과

```csharp
public class ResourceLoadingResult
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | 로딩 결과의 인스턴스를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | 사용자 정의 로더로 로드된 이진 데이터 - 로딩 후 설정해야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | 때때로 리소스의 인코딩은 로딩 후 또는 로딩 중에 알려집니다. 이 경우 사용자 정의 코드는 이 매개변수를 통해 변환기에 해당 정보를 제공할 수 있습니다. 인코딩이 알려지지 않았거나 중요하지 않은 경우 이 매개변수를 null로 두어도 됩니다. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | 때때로 요청된 리소스를 어떤 이유로 로드할 수 없습니다. 리소스의 불가용성은 종종 변환의 충돌로 이어지지 않으며 결과 문서는 여전히 생성될 수 있습니다(하지만 이미지 없이 약간 품질이 떨어질 수 있습니다). 로딩 중 예외가 발생한 경우, 이를 포착하여 이 매개변수에 넣으십시오 - 때때로 이 정보는 결과 렌더링을 위한 변환기에 유용합니다. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | 때때로 어떤 이유로 로딩이 사용자 정의 코드에서 발생하지 않아야 합니다. 이 경우 이 플래그를 True로 설정하십시오. 이 경우 변환기는 내부 기본 리소스 로더를 사용하여 결과를 얻으려고 시도합니다(사용자 정의 전략이 제공되지 않은 상황에서의 동작과 같습니다). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | 때때로 로드된 리소스의 MIME 유형에 대한 정보는 변환기에 유용합니다. 이 매개변수에 MIME 유형(로딩 후 알려진 경우)을 제공할 수 있습니다. MIME 유형이 알려지지 않았거나 제공할 필요가 없는 경우 매개변수를 null로 두십시오. |

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)