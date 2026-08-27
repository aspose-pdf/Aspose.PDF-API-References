---
title: "클래스 OptimizationOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Optimization.OptimizationOptions 클래스. 문서 최적화 알고리즘을 설명하는 클래스입니다. 이 클래스의 인스턴스는 OptimizeResources 메서드의 매개변수로 사용할 수 있습니다."
type: docs
weight: 8120
url: /ko/net/aspose.pdf.optimization/optimizationoptions/
---
## OptimizationOptions class

클래스는 문서 최적화 알고리즘을 설명합니다. 이 클래스의 인스턴스는 OptimizeResources() 메서드의 매개변수로 사용할 수 있습니다.

```csharp
public class OptimizationOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | true이면 문서가 동일한 페이지에 대해 최적화될 때 페이지 내용이 재사용됩니다. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | 이 플래그가 `true`로 설정되면 Pdf 객체가 Objest Streams에 압축되어 pdf 파일 크기를 줄입니다. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | 문서의 이미지가 압축되는 방식과 압축 매개변수를 설명하는 옵션 집합입니다. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | 사용될 이미지 인코드레. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | 이 플래그가 true로 설정되면 Resource 스트림이 분석됩니다. 중복 스트림이 발견되면(예: 스트림 내용이 동일한 경우) 해당 스트림은 하나의 객체로 저장됩니다. 이는 경우에 따라 문서 크기를 줄이는 데 도움이 됩니다(예: 동일한 문서를 여러 번 연결한 경우). |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | 이미지의 최대 해상도를 지정합니다. 이미지 해상도가 더 높으면 스케일링됩니다. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | 개인 정보를 제거합니다 (페이지 조각 정보). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | 이 플래그가 true로 설정되면 모든 문서 객체가 검사되고 사용되지 않는 객체(예: 참조가 없는 객체)는 문서에서 제거됩니다. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | 이 플래그가 true로 설정되면 모든 리소스가 사용 여부에 따라 검사됩니다. 리소스가 사용되지 않으면 해당 리소스가 제거됩니다. 이는 예를 들어 페이지가 문서에서 추출된 경우와 같이 문서 크기를 감소시킬 수 있습니다. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | true로 설정하면 글꼴이 서브셋으로 변환됩니다. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | true로 설정하면 글꼴을 포함하지 않게 합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | 모든 옵션이 활성화된 최적화 전략을 생성합니다. 활성화되는 옵션은 문서의 기능을 변경하지 않는 것에 한함을 유의하십시오. 예를 들어 이미지 압축 및 글꼴 포함 해제는 활성화되지 않으며(수동으로 포함시킬 수 있습니다). |

### 또 보기

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)


