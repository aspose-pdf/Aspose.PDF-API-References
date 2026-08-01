---
title: "열거형 HtmlSaveOptions.AntialiasingProcessingType"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.HtmlSaveOptionsAntialiasingProcessingType 열거형. 이 열거형은 변환 중 가능한 안티앨리어싱 조치를 설명합니다."
type: docs
weight: 5700
url: /ko/net/aspose.pdf/htmlsaveoptions.antialiasingprocessingtype/
---
## HtmlSaveOptions.AntialiasingProcessingType enumeration

이 열거형은 변환 중 가능한 안티앨리어싱 조치를 설명합니다.

```csharp
public enum AntialiasingProcessingType
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| NoAdditionalProcessing | `0` | 특별한 안티앨리어싱 처리를 사용하지 않습니다. 이는 대부분의 문서에 최적의 옵션이며 변환 중 추가 시간이 필요하지 않습니다. |
| TryCorrectResultHtml | `1` | 이 경우 변환기는 인접한 배경 그래픽 요소가 있는 위치를 감지하고 결과 HTML을 적절히 수정하려고 시도합니다. 이 옵션은 여러 인접 그래픽 요소로 구성된 배경을 포함하는 문서의 내보내기 결과를 향상시킬 수 있습니다(이러한 문서의 경우 PDF 렌더러, 예: Acrobat Reader는 일반적으로 렌더링 시 요소 경계를 부드럽게 처리하려고 합니다. 이 옵션을 사용하면 변환기가 PDF 렌더러의 동작을 모방합니다). 이 옵션은 복합 배경을 사용하는 특정 문서의 내보내기 레이아웃을 향상시킬 수 있지만, 처리에 추가 시간이 필요합니다(보통 추가 시간의 10~15% 정도). 따라서 일반적인 경우 이 모드의 사용은 권장되지 않습니다. |

### 또 보기

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


