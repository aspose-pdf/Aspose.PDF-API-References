---
title: "열거형 LoadOptions.MarginsAreaUsageModes"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.LoadOptionsMarginsAreaUsageModes 열거형. HTML, EPUB 등과 같은 변환 중 여백 영역 사용 모드를 나타내며, 가져온 형식의 여백 사용과 관련된 지시문의 처리를 정의합니다."
type: docs
weight: 6270
url: /ko/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

변환 중 여백 영역 사용 모드를 나타내며(HTML, EPUB 등), 가져온 형식의 여백 사용과 관련된 지시문의 처리를 정의합니다.

```csharp
public enum MarginsAreaUsageModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | 이 모드에서는 변환기가 가져온 문서의 형식(예: 가져온 HTML의 CSS)을 여백 영역 사용에 따라 따릅니다. 따라서 가져온 문서의 형식이 렌더링을 위해 여백 영역 사용을 요구하면 변환기가 이를 허용합니다. |
| NeverPutContentOnMarginArea | `1` | 이 모드는 여백 영역 사용을 엄격히 금지하므로, CSS나 원본 문서의 형식이 허용하거나 요구하더라도 변환기는 여백 영역을 렌더링에 절대 사용하지 않습니다. |

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


