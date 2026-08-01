---
title: "클래스 ThumbnailDevice"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Devices.ThumbnailDevice 클래스. PDF 문서 페이지를 Thumbnail 이미지로 저장하는 이미지 장치를 나타냅니다."
type: docs
weight: 3810
url: /ko/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

pdf 문서 페이지를 썸네일 이미지로 저장하는 이미지 장치를 나타냅니다.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | `ThumbnailDevice` 클래스의 새 인스턴스를 기본 썸네일 이미지 크기(200x200 픽셀)로 초기화합니다. |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | `ThumbnailDevice` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 페이지 좌표 유형(미디어/크롭 박스)을 가져오거나 설정합니다. 기본값으로 CropBox가 사용됩니다. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 폼 프레젠테이션 모드를 가져오거나 설정합니다. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 이미지 출력 높이를 가져옵니다. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 렌더링 옵션을 가져오거나 설정합니다. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 이미지 해상도를 가져옵니다. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 이미지 출력 너비를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | 페이지를 Bitmap으로 변환합니다. |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | 페이지를 썸네일 이미지 png로 변환하고 출력 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 지정된 page에 대해 일부 작업을 수행하고 결과를 파일에 저장합니다. |

### 또 보기

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


