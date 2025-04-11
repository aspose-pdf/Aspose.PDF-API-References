---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgLoadOptions 클래스. PDF 문서에 SVG 파일을 로드/가져오기 위한 옵션을 나타냅니다.
type: docs
weight: 10210
url: /ko/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions 클래스

PDF 문서에 SVG 파일을 로드/가져오기 위한 옵션을 나타냅니다.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | PDF 페이지 크기를 SVG 크기에 맞춥니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 비활성화하는 플래그를 가져오거나 설정합니다. `true`일 때, 이 글꼴의 라이선스에 의해 금지된 글꼴로 작업을 수행할 수 있도록 허용합니다. 예를 들어, 이 글꼴에 대한 임베딩을 비활성화하는 라이선스 규칙이 있더라도 PDF 문서에 글꼴을 임베드할 수 있도록 허용합니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/)가 설명하는 파일 형식을 나타냅니다. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | 문서를 로드하는 동안 적용해야 하는 페이지 정보를 가져오거나 설정합니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속되지만, 사용자가 Abort를 반환할 경우 Load 작업은 중단되어야 합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | 변환 중 사용할 변환 엔진을 선택할 수 있습니다. 현재 새로운 엔진은 B-테스트 단계에 있으므로 이 값은 기본적으로 ConversionEngines.LegacyEngine으로 설정됩니다. |

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)