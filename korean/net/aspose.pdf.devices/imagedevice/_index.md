---
title: Class ImageDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.ImageDevice 클래스. 이미지 장치를 위한 추상 클래스
type: docs
weight: 3610
url: /ko/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

이미지 장치를 위한 추상 클래스입니다.

```csharp
public abstract class ImageDevice : PageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | `ImageDevice` 자식 클래스의 추상 초기화 함수로, 해상도를 150x150으로 설정합니다. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | 제공된 이미지 크기와 기본 해상도(=150)로 [`JpegDevice`](../jpegdevice/) 클래스의 새 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | `ImageDevice` 자식 클래스의 추상 초기화 함수입니다. 결과 이미지 파일의 해상도는 [`Resolution`](./resolution/) 클래스를 참조하십시오. |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | 제공된 이미지 크기와 기본 해상도(=150)로 [`JpegDevice`](../jpegdevice/) 클래스의 새 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | 제공된 이미지 크기와 해상도로 [`JpegDevice`](../jpegdevice/) 클래스의 새 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | 제공된 이미지 크기와 해상도로 [`JpegDevice`](../jpegdevice/) 클래스의 새 인스턴스를 초기화합니다. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 페이지 좌표 유형(Media/Crop 박스)을 가져오거나 설정합니다. 기본적으로 CropBox 값이 사용됩니다. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 양식 프레젠테이션 모드를 가져오거나 설정합니다. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 이미지 출력 높이를 가져옵니다. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 렌더링 옵션을 가져오거나 설정합니다. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 이미지 해상도를 가져옵니다. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 이미지 출력 너비를 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | 주어진 페이지에서 일부 작업을 수행합니다. 예: 페이지를 그래픽 이미지로 변환합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 주어진 페이지에서 일부 작업을 수행하고 결과를 파일에 저장합니다. |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)