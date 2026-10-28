---
title: "클래스 PsLoadOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.PsLoadOptions 클래스. .mht 파일을 PDF 문서로 로드/가져오기 위한 옵션을 나타냅니다."
type: docs
weight: 9880
url: /ko/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

.mht 파일을 PDF Document에 로드/임포트하기 위한 옵션을 나타냅니다.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | 비 TrueType 글꼴을 TTF로 저장할지 여부를 지정합니다. 이는 PS에서 PDF로 변환할 때 결과 문서의 용량을 크게 감소시키고, 비 TrueType 글꼴에 텍스트가 많이 포함된 PS 파일을 모든 출력 형식으로 변환하는 속도를 높입니다. 그러나 PostSctipt 파일을 이미지로 변환할 때 텍스트가 약간 수직으로 이동합니다. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | 파일을 로드하는 동안 모든 글꼴에 대한 라이선스 제한을 해제하는 플래그를 가져오거나 설정합니다. `true`인 경우 해당 글꼴의 라이선스에서 금지된 작업을 수행할 수 있게 하며, 예를 들어 라이선스 규정이 임베딩을 금지하더라도 글꼴을 PDF 문서에 삽입할 수 있습니다. 기본값은 `false`입니다. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | 글꼴 폴더 경로를 가져오거나 설정합니다. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `[`LoadOptions`](../loadoptions/)`가 설명하는 파일 형식을 나타냅니다. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Load 작업이 계속 진행되지만, 사용자가 Abort를 반환하면 Load 작업이 중단됩니다. |

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


