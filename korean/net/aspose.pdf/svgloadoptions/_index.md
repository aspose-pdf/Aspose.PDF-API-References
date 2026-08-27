---
title: "클래스 SvgLoadOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.SvgLoadOptions 클래스. SVG 파일을 PDF Document에 로드/임포트하기 위한 옵션을 나타냅니다."
type: docs
weight: 10390
url: /ko/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

SVG 파일을 PDF 문서에 로드/임포트하기 위한 옵션을 나타냅니다.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | PDF Page 크기를 SVG 크기에 맞게 조정합니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 해제하는 플래그를 가져오거나 설정합니다. `true`인 경우 해당 글꼴의 라이선스에서 금지된 작업을 수행할 수 있게 하며, 예를 들어 라이선스 규정이 임베딩을 금지하더라도 글꼴을 PDF 문서에 삽입할 수 있습니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `[`LoadOptions`](../loadoptions/)`가 설명하는 파일 형식을 나타냅니다. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Document 로드 중에 적용될 Page 정보를 가져오거나 설정합니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환하면 Load 작업이 중단됩니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | 변환 중에 사용할 변환 엔진을 선택하도록 허용합니다. 현재 새 엔진은 B-테스트 단계에 있으므로 기본값은 ConversionEngines.LegacyEngine으로 설정됩니다. |

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


