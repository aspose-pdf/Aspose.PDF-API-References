---
title: Enum LoadOptions.MarginsAreaUsageModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsMarginsAreaUsageModes 열거형. HTML, EPUB 등과 같은 변환 중 여백 영역의 사용 모드를 나타내며, 여백 사용과 관련된 가져온 형식의 지침 처리를 정의합니다.
type: docs
weight: 6130
url: /ko/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes 열거형

변환 중 여백 영역의 사용 모드를 나타내며(HTML, EPUB 등과 같은), 여백 사용과 관련된 가져온 형식의 지침 처리를 정의합니다.

```csharp
public enum MarginsAreaUsageModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | 이 모드에서는 변환기가 가져온 문서의 형식(예: 가져온 HTML의 CSS)에 따라 여백 영역의 사용을 준수합니다. 따라서 가져온 문서의 형식이 렌더링을 위해 여백 영역의 사용을 요구하는 경우, 변환기는 이를 허용합니다. |
| NeverPutContentOnMarginArea | `1` | 이 모드는 여백 영역의 사용을 엄격히 금지하므로, 변환기는 소스 문서의 CSS나 형식이 이를 허용하거나 요구하더라도 여백 영역을 렌더링에 사용하지 않습니다. |

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)