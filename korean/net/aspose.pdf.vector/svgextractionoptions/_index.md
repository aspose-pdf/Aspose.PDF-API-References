---
title: "클래스 SvgExtractionOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Vector.SvgExtractionOptions 클래스. PDF 문서 페이지에서 벡터 그래픽을 추출하기 위한 옵션 클래스를 나타냅니다."
type: docs
weight: 11430
url: /ko/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions class

PDF 문서 페이지에서 벡터 그래픽을 추출하기 위한 옵션 클래스를 나타냅니다.

```csharp
public class SvgExtractionOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | subpaths를 자동으로 이미지로 그룹화하는 옵션을 가져오거나 설정합니다. 이 옵션은 [`GroupStrength`](./groupstrength/) 옵션을 제외합니다. |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | PDF 문서에서 모든 subpath를 개별 SVG 이미지로 추출하는 옵션을 가져오거나 설정합니다. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | SVG 추출을 위한 추출 영역을 정의하는 경계 사각형을 가져오거나 설정합니다. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | subpaths를 이미지로 그룹화하는 강도를 설정하는 옵션을 가져오거나 설정합니다. subpaths의 그룹화 정도를 구성할 수 있습니다. 값 범위는 0에서 1까지입니다. 0값은 [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) 옵션이 활성화된 것을 의미하고, 1값은 페이지의 모든 벡터 경로에 대해 단일 이미지를 생성합니다. 이 옵션은 [`AutoGrouping`](./autogrouping/)이 false일 때 영향을 미칩니다. 기본값은 `0.8`입니다. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | 결과 SVG에 사용될 최소 스트로크 너비를 가져오거나 설정합니다. PDF가 더 얇은 스트로크 너비를 사용할 경우 이 너비로 대체됩니다. 기본값은 0.5입니다. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | [`ExtractionAreaBound`](./extractionareabound/)에 지정된 사각형 내에 subpaths가 포함되는지를 엄격히 검사하는 옵션을 가져오거나 설정합니다. false로 설정하면 [`ExtractionAreaBound`](./extractionareabound/)에 완전히 포함되지 않은 subpaths도 추출됩니다. 기본값은 `True`입니다. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | 페이지에서 발견된 XFrom을 풀어낼지 여부를 결정하는 플래그를 가져오거나 설정합니다. XFrom 요소는 서로 다른 SVG 파일에 포함될 수 있습니다. 페이지 내용의 Do 문에 의해 렌더링된 XForm만 풀어내며, 중첩된 XForm은 풀어내지 않습니다. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | 지정된 조건에 해당하는 XForm만 풀어내는 옵션을 가져오거나 설정합니다. |

### 또 보기

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


