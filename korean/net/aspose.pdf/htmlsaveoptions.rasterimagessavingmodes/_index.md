---
title: Enum HtmlSaveOptions.RasterImagesSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes 열거형. 변환된 PDF는 래스터 이미지（.png, .jpeg 등）를 포함할 수 있습니다. 이 열거형은 PDF를 HTML로 변환하는 동안 래스터 이미지를 처리하는 방법을 정의합니다.
type: docs
weight: 5720
url: /ko/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes 열거형

변환된 PDF는 래스터 이미지(.png, *.jpeg 등)를 포함할 수 있습니다. 이 열거형은 PDF를 HTML로 변환하는 동안 래스터 이미지를 처리하는 방법을 정의합니다.

```csharp
public enum RasterImagesSavingModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | 각 고유한 래스터 파일에 대해 래퍼 SVG 이미지가 생성되며, 래스터 이미지는 해당 SVG 이미지에 Base64 인코딩된 문자열로 포함됩니다. |
| AsExternalPngFilesReferencedViaSvg | `1` | 고유한 래스터 이미지는 PNG 파일로 분리되어 저장되지만, 래핑된 SVG 이미지를 통해 참조됩니다. 즉, 각 래스터 이미지에 대해 하나의 PNG 파일과 하나의 SVG가 생성되며, 각 SVG는 관련 PNG 파일에 대한 링크를 포함합니다. |
| AsEmbeddedPartsOfPngPageBackground | `2` | 각 결과 페이지에 대해 하나의 큰 PNG 배경 파일이 생성됩니다. 래스터 이미지는 해당 파일에 포함되어 그 이미지의 영역으로 렌더링됩니다. 각 이미지에 대한 외부 PNG 파일은 생성되지 않으며, 페이지당 하나의 PNG 파일만 변환 결과 파일 세트에 존재합니다. |
| DontSave | `3` | 고정 레이아웃에 대한 이미지를 저장하지 않습니다. |

### 참조

* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)