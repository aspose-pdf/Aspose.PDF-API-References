---
title: "열거형 LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes 열거형. ATTENTION 구현된 기능이지만 샘플 문서에서 OSHARED 레이어의 차단 이슈가 발견되어 아직 public API에 제공되지 않았습니다. 변환 중 page size 사용 모드를 나타냅니다. HTML, EPUB 등과 같은 형식은 일반적으로 플로트 디자인을 가지고 있어 필요한 페이지 크기에 맞출 수 있습니다. 그러나 때때로 콘텐츠가 수평 위치나 크기를 지정하여 필요한 페이지 크기에 맞추지 못하는 경우가 있습니다. 이런 경우, 즉 콘텐츠 크기가 결과 PDF 문서의 초기 페이지 크기에 맞지 않을 때 수행할 작업을 정의할 수 있습니다."
type: docs
weight: 6280
url: /ko/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ATTENTION! 구현된 기능이지만 샘플 문서에서 OSHARED 레이어의 차단 이슈가 발견되어 아직 public API에 제공되지 않았습니다. 변환 중 page size 사용 모드를 나타냅니다. HTML, EPUB 등과 같은 형식은 일반적으로 플로트 디자인을 가지고 있어 필요한 페이지 크기에 맞출 수 있습니다. 그러나 때때로 콘텐츠가 수평 위치나 크기를 지정하여 필요한 페이지 크기에 맞추지 못하는 경우가 있습니다. 이런 경우(예: 콘텐츠 크기가 결과 PDF 문서의 초기 페이지 크기에 맞지 않을 때) 수행할 작업을 정의할 수 있습니다.

```csharp
public enum PageSizeAdjustmentModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | 이 모드에서는 결과 pages가 LoadOptions에 정의된 필요한 페이지 크기를 갖게 되며, 변환 후 콘텐츠가 page 경계를 벗어나든 벗어나지 않든 관계없이 적용됩니다. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | 이 모드는 다음과 같은 동작을 정의합니다: 변환 결과를 얻은 후 일부 콘텐츠가 잘렸음을 감지하면, 포트뷰의 너비를 확대하여 콘텐츠에 맞추고 변환을 다시 수행합니다. 이 모드는 결과에서 페이지 수를 줄일 수 있지만, 반복 렌더링이 필요하므로 처리 시간이 더 많이 소요됩니다. |

### 또 보기

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


