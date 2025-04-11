---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ThumbnailDevice 클래스. PDF 문서 페이지를 썸네일 이미지로 저장하는 이미지 장치를 나타냅니다.
type: docs
weight: 3690
url: /ko/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice 클래스

PDF 문서 페이지를 썸네일 이미지로 저장하는 이미지 장치를 나타냅니다.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | 기본 썸네일 이미지 크기(200x200 픽셀)로 `ThumbnailDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | `ThumbnailDevice` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 페이지 좌표 유형(Media/Crop 박스)을 가져오거나 설정합니다. 기본적으로 CropBox 값이 사용됩니다. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 양식 프레젠테이션 모드를 가져오거나 설정합니다. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 이미지 출력 높이를 가져옵니다. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 렌더링 옵션을 가져오거나 설정합니다. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 이미지 해상도를 가져옵니다. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 이미지 출력 너비를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | 페이지를 썸네일 이미지 PNG로 변환하고 출력 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 주어진 페이지에서 일부 작업을 수행하고 결과를 파일에 저장합니다. |

### 참조

* 클래스 [ImageDevice](../imagedevice/)
* 네임스페이스 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* 어셈블리 [Aspose.PDF](../../)