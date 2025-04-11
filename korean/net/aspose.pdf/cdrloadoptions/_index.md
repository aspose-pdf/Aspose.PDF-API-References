---
title: Class CdrLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CdrLoadOptions 클래스. 클래스는 CDR 로드 옵션을 설명합니다.
type: docs
weight: 2960
url: /ko/net/aspose.pdf/cdrloadoptions/
---
## CdrLoadOptions 클래스

클래스는 CDR 로드 옵션을 설명합니다.

```csharp
public class CdrLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [CdrLoadOptions](cdrloadoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 비활성화하는 플래그를 가져오거나 설정합니다. `true`일 때, 이 글꼴의 라이선스에 의해 금지된 글꼴로 작업을 수행할 수 있도록 허용합니다. 예를 들어, 이 글꼴에 대한 임베딩을 비활성화하는 라이선스 규칙이 있더라도 PDF 문서에 글꼴을 임베드할 수 있도록 허용합니다. 기본값은 `false`입니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/)가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 로드 작업이 계속됩니다. 그러나 사용자가 Abort를 반환할 수도 있으며, 이 경우 로드 작업은 중단되어야 합니다. |

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)