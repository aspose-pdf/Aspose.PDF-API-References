---
title: Class SvgExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Vector.SvgExtractionOptions 클래스. PDF 문서 페이지에서 벡터 그래픽을 추출하기 위한 옵션 클래스를 나타냅니다.
type: docs
weight: 11240
url: /ko/net/aspose.pdf.vector/svgextractionoptions/
---
## SvgExtractionOptions 클래스

PDF 문서 페이지에서 벡터 그래픽을 추출하기 위한 옵션 클래스를 나타냅니다.

```csharp
public class SvgExtractionOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SvgExtractionOptions](svgextractionoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoGrouping](../../aspose.pdf.vector/svgextractionoptions/autogrouping/) { get; set; } | 하위 경로를 이미지로 자동 그룹화하는 옵션을 가져오고 설정합니다. 이 옵션은 [`GroupStrength`](./groupstrength/) 옵션을 제외합니다. |
| [ExtractEverySubPathToSvg](../../aspose.pdf.vector/svgextractionoptions/extracteverysubpathtosvg/) { get; set; } | PDF 문서에서 모든 하위 경로를 별도의 SVG 이미지로 추출하는 옵션을 가져오고 설정합니다. |
| [ExtractionAreaBound](../../aspose.pdf.vector/svgextractionoptions/extractionareabound/) { get; set; } | SVG 추출을 위한 추출 영역을 정의하는 경계 사각형을 가져오고 설정합니다. |
| [GroupStrength](../../aspose.pdf.vector/svgextractionoptions/groupstrength/) { get; set; } | 하위 경로를 이미지로 그룹화하는 강도를 설정하는 옵션을 가져오고 설정합니다. 하위 경로의 그룹화 정도를 구성할 수 있습니다. 값의 범위는 0에서 1까지입니다. 0의 값은 [`ExtractEverySubPathToSvg`](./extracteverysubpathtosvg/) 옵션이 활성화된 것에 해당합니다. 1의 값은 페이지의 모든 벡터 경로에 대해 단일 이미지를 생성합니다. 이 옵션은 [`AutoGrouping`](./autogrouping/)이 false일 때 효과가 있습니다. 기본값은 `0.8`입니다. |
| [MinStrokeWidth](../../aspose.pdf.vector/svgextractionoptions/minstrokewidth/) { get; set; } | 결과 SVG에서 사용될 최소 스트로크 너비를 가져오거나 설정합니다. PDF가 더 얇은 스트로크 너비를 사용하는 경우 이 너비로 대체됩니다. 기본값은 0.5입니다. |
| [StrictExtractionAreaBoundCheck](../../aspose.pdf.vector/svgextractionoptions/strictextractionareaboundcheck/) { get; set; } | 하위 경로가 [`ExtractionAreaBound`](./extractionareabound/)에 지정된 사각형 내에 있는지 엄격하게 확인하는 옵션을 가져오고 설정합니다. false로 설정하면 [`ExtractionAreaBound`](./extractionareabound/)에 완전히 포함되지 않은 하위 경로도 추출됩니다. 기본값은 `True`입니다. |
| [UnpackPageContentXForm](../../aspose.pdf.vector/svgextractionoptions/unpackpagecontentxform/) { get; set; } | 페이지에서 발견된 XForm을 풀어야 하는지 여부를 결정하는 플래그를 가져오고 설정합니다. XForm 요소는 서로 다른 SVG 파일에 포함될 수 있습니다. 페이지 콘텐츠의 Do 문에 의해 렌더링된 XForms만 풀립니다. 중첩된 XForms는 풀리지 않습니다. |
| [UnpackXFormPredicate](../../aspose.pdf.vector/svgextractionoptions/unpackxformpredicate/) { get; set; } | 지정된 조건에 해당하는 XForm만 풀기 위한 옵션을 가져오고 설정합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* 어셈블리 [Aspose.PDF](../../)