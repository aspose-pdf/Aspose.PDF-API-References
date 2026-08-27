---
title: "클래스 ImageDevice"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Devices.ImageDevice 클래스. 이미지 장치를 위한 추상 클래스입니다."
type: docs
weight: 3730
url: /ko/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

이미지 장치를 위한 추상 클래스입니다.

```csharp
public abstract class ImageDevice : PageDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)() | `ImageDevice` 파생 클래스용 추상 초기화 메서드, 해상도를 150x150으로 설정합니다. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | 제공된 이미지 크기와 기본 해상도(=150)를 사용하여 [`JpegDevice`](../jpegdevice/) 클래스의 새 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | `ImageDevice` 파생 클래스용 추상 초기화 메서드. 결과 이미지 파일의 해상도는 [`Resolution`](./resolution/) 클래스를 참조하십시오. |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | 제공된 이미지 크기와 기본 해상도(=150)를 사용하여 [`JpegDevice`](../jpegdevice/) 클래스의 새 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | 제공된 이미지 크기와 해상도를 사용하여 [`JpegDevice`](../jpegdevice/) 클래스의 새 인스턴스를 초기화합니다. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | 제공된 이미지 크기와 해상도를 사용하여 [`JpegDevice`](../jpegdevice/) 클래스의 새 인스턴스를 초기화합니다. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | 주어진 페이지에 대해 일부 작업을 수행합니다, 예를 들어 페이지를 그래픽 이미지로 변환합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 지정된 page에 대해 일부 작업을 수행하고 결과를 파일에 저장합니다. |

### 또 보기

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


