---
title: "클래스 RenderingOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.RenderingOptions 클래스. 렌더링 옵션을 나타냅니다"
type: docs
weight: 9910
url: /ko/net/aspose.pdf/renderingoptions/
---
## RenderingOptions class

렌더링 옵션을 나타냅니다.

```csharp
public sealed class RenderingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | 텍스트의 모든 문자를 표시할 수 있도록 필요에 따라 글꼴을 교체합니다. 글꼴 대체 알고리즘은 다음 단계에 따라 수행됩니다: 1. 사용자가 DefaultFontName 속성을 명시적으로 설정한 경우, 지정된 글꼴이 원하는 문자를 표시할 수 있는지 확인합니다. 2. 사용자 정의 글꼴이 설정되지 않은 경우, !:FontRepository.Sources를 통해 추가된 글꼴을 검색합니다. 3. 텍스트를 분석하여 알파벳 또는 스크립트를 식별하고 이에 따라 글꼴 이름을 제안합니다. 시스템에서 이러한 글꼴을 찾아 사용을 시도합니다. 4. 대체 방안으로, 시스템에서 필요한 문자를 표시할 수 있는 모든 글꼴을 검색합니다. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | 바코드 최적화 모드를 가져오거나 설정합니다. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | 모든 글꼴이 TTF 유니코드 버전으로 변환됨을 나타냅니다. 이는 호환성 및 글꼴 사용 최적화를 위해 유용합니다. 새로운 TTF 글꼴은 원본 글꼴의 모든 기호가 아니라 텍스트에서 사용된 기호만 포함하게 됩니다. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | 누락된 글꼴을 대체하는 데 사용되는 기본 글꼴 이름을 가져오거나 설정합니다. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | AppendRectangle 연산자의 사각형 너비를 늘리거나 줄이는 데 사용되는 값을 가져오거나 설정합니다. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | 폰트가 없을 때 발생하는 오류를 무시하도록 표시하는 값을 가져오거나 설정합니다. true - 폰트가 없을 때 발생하는 오류를 무시함을 의미합니다. 잘못된 리소스를 참조하는 텍스트 세그먼트는 처리 중에 건너뛰어집니다. 기본값은 false입니다. |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | 보간을 위한 고품질 모드를 가져오거나 설정합니다. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | 글꼴 캐시의 최대 글꼴 수입니다. 기본값은 10입니다. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | 심볼 캐시의 최대 심볼 수입니다. 기본값은 100입니다. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | 차원 최적화 모드를 가져오거나 설정합니다. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | 시스템 글꼴이 기본적으로 렌더링되는 모드를 가져오거나 설정합니다. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | 이 플래그를 사용하면 글꼴 힌팅 메커니즘이 활성화됩니다. 글꼴 힌팅은 윤곽 글꼴의 표시를 조정하기 위해 수학적 명령을 사용하는 것입니다. 경우에 따라 이 플래그를 켜면 텍스트 가독성 문제를 해결할 수 있습니다. 현재 이 플래그의 사용은 소스 Document에 이러한 글꼴이 사용된 경우에만 TTF 글꼴에 영향을 줄 수 있습니다. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | AppendRectangle 연산자의 사각형 너비를 늘리거나 줄이는 데 사용되는 값을 가져오거나 설정합니다. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


