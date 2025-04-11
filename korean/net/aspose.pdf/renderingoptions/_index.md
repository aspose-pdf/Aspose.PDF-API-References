---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.RenderingOptions 클래스. 렌더링 옵션을 나타냅니다.
type: docs
weight: 9760
url: /ko/net/aspose.pdf/renderingoptions/
---
## RenderingOptions 클래스

렌더링 옵션을 나타냅니다.

```csharp
public sealed class RenderingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | 텍스트의 모든 문자가 표시될 수 있도록 필요에 따라 글꼴을 교체합니다. 글꼴 대체 알고리즘은 다음 단계를 따릅니다: 1. 사용자가 DefaultFontName 속성을 명시적으로 설정한 경우, 지정된 글꼴이 원하는 문자를 표시할 수 있는지 확인합니다. 2. 사용자 정의 글꼴이 설정되지 않은 경우, !:FontRepository.Sources를 통해 추가된 글꼴을 검색합니다. 3. 텍스트를 분석하여 알파벳 또는 스크립트를 식별하고 그에 따라 글꼴 이름을 제안합니다. 이러한 글꼴을 시스템에서 찾고 사용하려고 시도합니다. 4. 대체로, 필요한 문자를 표시할 수 있는 글꼴을 시스템에서 검색합니다. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | 바코드 최적화 모드를 가져오거나 설정합니다. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | 모든 글꼴이 TTF 유니코드 버전으로 변환될 것임을 나타냅니다. 이는 호환성 이유와 글꼴 사용 최적화를 위해 유용합니다. 모든 새로운 TTF 글꼴은 원본 글꼴의 모든 기호를 포함하지 않고, 텍스트에서 사용되는 기호만 포함합니다. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | 누락된 글꼴을 대체하는 데 사용되는 기본 글꼴 이름을 가져오거나 설정합니다. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | AppendRectangle 연산자를 위한 사각형의 너비를 증가시키거나 감소시키는 데 사용되는 값을 가져오거나 설정합니다. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | 글꼴의 부재와 관련된 오류를 무시할 것임을 나타내는 값을 가져오거나 설정합니다. true - 글꼴의 부재로 인한 오류가 무시됨을 의미합니다. 잘못된 리소스를 참조하는 텍스트 세그먼트는 처리 중에 건너뜁니다. 기본값은 false입니다. |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | 보간을 위한 고품질 모드를 가져오거나 설정합니다. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | 글꼴 캐시의 최대 글꼴 수입니다. 기본값은 10입니다. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | 기호 캐시의 최대 기호 수입니다. 기본값은 100입니다. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | 최적화된 치수 모드를 가져오거나 설정합니다. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | 시스템 글꼴이 네이티브로 렌더링되는 모드를 가져오거나 설정합니다. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | 이 플래그의 사용은 글꼴 힌팅 메커니즘을 활성화합니다. 글꼴 힌팅은 윤곽 글꼴의 표시를 조정하기 위해 수학적 지침을 사용하는 것입니다. 이 플래그를 켜면 텍스트 가독성 문제를 해결할 수 있습니다. 현재 이 플래그의 사용은 TTF 글꼴에만 효과가 있으며, 이러한 글꼴이 원본 문서에서 사용될 때만 적용됩니다. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | AppendRectangle 연산자를 위한 사각형의 너비를 증가시키거나 감소시키는 데 사용되는 값을 가져오거나 설정합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)