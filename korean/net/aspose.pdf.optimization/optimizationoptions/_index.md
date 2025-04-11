---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Optimization.OptimizationOptions 클래스. 문서 최적화 알고리즘을 설명하는 클래스. 이 클래스의 인스턴스는 OptimizeResources 메서드의 매개변수로 사용될 수 있습니다.
type: docs
weight: 7980
url: /ko/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions 클래스

문서 최적화 알고리즘을 설명하는 클래스. 이 클래스의 인스턴스는 OptimizeResources() 메서드의 매개변수로 사용될 수 있습니다.

```csharp
public class OptimizationOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | true인 경우 문서가 동일한 페이지에 대해 최적화될 때 페이지 내용이 재사용됩니다. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | 이 플래그가 `true`로 설정되면 Pdf 객체가 Objest Streams에 패킹되고 압축되어 pdf 파일 크기가 줄어듭니다. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | 문서의 이미지가 압축될지 여부와 압축 매개변수를 설명하는 옵션 세트입니다. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | 사용될 이미지 인코더입니다. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | 이 플래그가 true로 설정되면 리소스 스트림이 분석됩니다. 중복 스트림이 발견되면(즉, 스트림 내용이 동일한 경우) 이러한 스트림은 하나의 객체로 저장됩니다. 이는 동일한 문서가 여러 번 연결된 경우와 같이 문서 크기를 줄이는 데 도움이 될 수 있습니다. |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | 스캔 수준입니다. 더 깊은 스캔(더 높은 값)은 시간이 더 걸리지만 더 작은 결과 파일을 생성할 수 있습니다. 기본값: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | 이미지의 최대 해상도를 지정합니다. 이미지의 해상도가 더 높으면 크기가 조정됩니다. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | 개인 정보(페이지 조각 정보)를 제거합니다. |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | 이 플래그가 true로 설정되면 모든 문서 객체가 확인되고 사용되지 않는 객체(즉, 참조가 없는 객체)가 문서에서 제거됩니다. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | 이 플래그가 true로 설정되면 모든 리소스의 사용 여부가 확인됩니다. 리소스가 사용되지 않으면 리소스가 제거됩니다. 이는 페이지가 문서에서 추출된 경우 문서 크기를 줄일 수 있습니다. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | true로 설정되면 글꼴이 서브셋으로 변환됩니다. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | true로 설정되면 글꼴이 포함되지 않도록 합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | 모든 옵션이 활성화된 최적화 전략을 생성합니다. 문서의 기능을 변경하지 않는 활성화된 옵션만 주의하십시오. 즉, 이미지 압축 및 글꼴 비포함은 활성화되지 않으며(수동으로 포함할 수 있음) 가능합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* 어셈블리 [Aspose.PDF](../../)