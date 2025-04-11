---
title: Enum HtmlSaveOptions.AntialiasingProcessingType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType 열거형. 이 열거형은 변환 중 가능한 안티앨리어싱 조치를 설명합니다.
type: docs
weight: 5570
url: /ko/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType 열거형

이 열거형은 변환 중 가능한 안티앨리어싱 조치를 설명합니다.

```csharp
public enum AntialiasingProcessingType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | 특별한 안티앨리어싱 처리가 사용되지 않습니다. 이는 압도적인 대부분의 문서에 최적의 옵션이며 변환 중 추가 시간이 필요하지 않습니다. |
| TryCorrectResultHtml | `1` | 이 경우 변환기는 인접한 배경 그래픽 요소가 있는 위치를 감지하고 관련 방식으로 결과 HTML을 수정하려고 시도합니다. 이 옵션은 여러 인접 그래픽 요소로 구성된 배경을 포함하는 문서의 내보내기 결과를 향상시킬 수 있습니다(이러한 종류의 문서에 대해 PDF 렌더러, 예를 들어 Acrobat Reader는 일반적으로 렌더링 중 요소의 경계를 부드럽게 하려고 합니다. 이 옵션은 변환기가 PDF 렌더러의 동작을 모방하도록 합니다. 이 옵션은 특정 문서(이러한 복합 배경을 사용하는 문서)의 내보내기 결과 레이아웃을 향상시킬 수 있지만, 처리에 추가 시간이 필요합니다(일반적으로 약 10-15%의 추가 시간). 따라서 일반적인 경우 이 모드를 사용하는 것은 권장되지 않습니다. |

### 참조

* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)