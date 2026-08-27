---
title: "LoadOptions.ResourceLoadingResult 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.LoadOptionsResourceLoadingResult 클래스. 리소스의 사용자 지정 로딩 결과"
type: docs
weight: 6290
url: /ko/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

리소스의 사용자 지정 로딩 결과

```csharp
public class ResourceLoadingResult
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | 로드 결과의 인스턴스를 생성합니다 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | 사용자 지정 로더로 로드된 바이너리 데이터 - 로드 후에 설정해야 합니다 |

## 필드

| 이름 | 설명 |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | 리소스의 인코딩이 로드 후 또는 로드 중에 알려지는 경우가 있습니다. 이러한 경우 사용자 지정 코드는 이 매개변수를 통해 변환기에 해당 정보를 제공할 수 있습니다. 인코딩을 알 수 없거나 중요하지 않은 경우 이 매개변수에 null을 그대로 두세요. |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | 때때로 요청된 리소스를 어떤 이유로든 로드할 수 없는 경우가 있습니다. 리소스가 없더라도 변환이 중단되지 않고 결과 문서를 생성할 수 있습니다(다만 품질이 다소 낮아지고 이미지 등이 누락될 수 있습니다). 로드 중 예외가 발생하면 해당 예외를 잡아 이 매개변수에 넣으세요 - 이 정보가 변환기의 결과 렌더링에 유용하게 사용될 수 있습니다. |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | 때때로 특정 이유로 로딩이 사용자 지정 코드에서 발생하지 않아야 할 때가 있습니다. 이 경우 이 플래그를 True 로 설정하세요. 그러면 변환기가 내부 기본 리소스 로더를 사용하여 결과를 얻으려고 시도합니다(사용자 지정 전략이 제공되지 않은 상황과 동일하게 동작합니다). |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | 로드된 리소스의 MIME 타입에 대한 정보가 변환기에 유용할 때가 있습니다. 이 매개변수에 MIME 타입을 제공할 수 있습니다(로드 후에 알려진 경우). MIME 타입을 알 수 없거나 제공할 필요가 없을 경우 이 매개변수를 null으로 두세요. |

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


