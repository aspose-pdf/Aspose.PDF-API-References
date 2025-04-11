---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes 열거형. 주의 이 기능은 구현되었지만 샘플 문서에 대한 OSHARED 레이어에서 발견된 차단 문제로 인해 아직 공개 API에 포함되지 않았습니다. 변환 중 페이지 크기 사용 모드를 나타냅니다. HTML, EPUB 등과 같은 형식은 일반적으로 플로트 디자인을 가지고 있어 필요한 페이지 크기에 맞출 수 있습니다. 그러나 때때로 콘텐츠는 수평 위치나 크기를 지정하여 필요한 페이지 크기에 콘텐츠를 넣을 수 없게 합니다. 이러한 경우 콘텐츠의 크기가 결과 PDF 문서의 초기 페이지 크기에 맞지 않을 때 무엇을 해야 하는지를 정의할 수 있습니다.
type: docs
weight: 6140
url: /ko/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes 열거형

주의! 이 기능은 구현되었지만 샘플 문서에 대한 OSHARED 레이어에서 발견된 차단 문제로 인해 아직 공개 API에 포함되지 않았습니다. 변환 중 페이지 크기 사용 모드를 나타냅니다. 형식(HTML, EPUB 등)은 일반적으로 플로트 디자인을 가지고 있어 필요한 페이지 크기에 맞출 수 있습니다. 그러나 때때로 콘텐츠는 수평 위치나 크기를 지정하여 필요한 페이지 크기에 콘텐츠를 넣을 수 없게 합니다. 이러한 경우 콘텐츠의 크기가 결과 PDF 문서의 초기 페이지 크기에 맞지 않을 때 무엇을 해야 하는지를 정의할 수 있습니다.

```csharp
public enum PageSizeAdjustmentModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | 이 모드에서는 결과 페이지가 LoadOptions에 정의된 필요한 페이지 크기를 가지며, 변환 후 콘텐츠가 페이지 경계를 넘어가더라도 상관 없습니다. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | 이 모드는 다음과 같은 동작을 정의합니다: 변환 결과를 얻고 일부 콘텐츠가 잘렸다는 사실을 감지한 후, 콘텐츠에 맞추기 위해 포트뷰의 너비가 확장되고 변환이 반복됩니다. 이 모드는 이러한 경우 결과에서 페이지 수를 줄일 수 있지만 반복 렌더링(따라서 더 많은 처리 시간)이 필요합니다. |

### 참조

* 클래스 [LoadOptions](../loadoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)