---
title: "열거형 HtmlSaveOptions.RasterImagesSavingModes"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.HtmlSaveOptionsRasterImagesSavingModes 열거형. 변환된 PDF에는 래스터 이미지(.png, .jpeg 등)가 포함될 수 있습니다. 이 열거형은 PDF를 HTML로 변환하는 동안 래스터 이미지를 처리하는 방법을 정의합니다."
type: docs
weight: 5850
url: /ko/net/aspose.pdf/htmlsaveoptions.rasterimagessavingmodes/
---
## HtmlSaveOptions.RasterImagesSavingModes enumeration

변환된 PDF에는 래스터 이미지(.png, *.jpeg 등)가 포함될 수 있습니다. 이 열거형은 PDF를 HTML로 변환하는 동안 래스터 이미지를 처리하는 방법을 정의합니다.

```csharp
public enum RasterImagesSavingModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| AsPngImagesEmbeddedIntoSvg | `0` | 각 개별 래스터 파일마다 래퍼 SVG 이미지가 생성되며, 래스터 이미지는 Base64 인코딩 문자열로 해당 SVG 이미지에 삽입됩니다. |
| AsExternalPngFilesReferencedViaSvg | `1` | 개별 래스터 이미지는 PNG 파일로 분리되지만 래핑 SVG 이미지를 통해 참조됩니다. 즉, 각 래스터 이미지마다 하나의 PNG 파일과 하나의 SVG가 생성되며, 해당 SVG에는 관련 PNG 파일에 대한 링크가 포함됩니다. |
| AsEmbeddedPartsOfPngPageBackground | `2` | 각 결과 페이지마다 큰 PNG 배경 파일이 하나 생성됩니다. 래스터 이미지는 해당 파일에 삽입되어 이미지의 영역으로 렌더링됩니다. 각 이미지에 대한 별도의 외부 PNG 파일은 생성되지 않으며, 페이지당 하나의 PNG 파일만 변환 결과 파일 집합에 포함됩니다. |
| DontSave | `3` | 고정 레이아웃에 대해 이미지를 저장하지 않음 |

### 또 보기

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


