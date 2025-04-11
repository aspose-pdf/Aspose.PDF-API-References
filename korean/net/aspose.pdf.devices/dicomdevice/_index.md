---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DicomDevice 클래스. PDF 문서 페이지를 Dicom 형식으로 저장하는 데 도움이 되는 이미지 장치를 나타냅니다.
type: docs
weight: 3560
url: /ko/net/aspose.pdf.devices/dicomdevice/
---
## DicomDevice 클래스

PDF 문서 페이지를 Dicom 형식으로 저장하는 데 도움이 되는 이미지 장치를 나타냅니다.

```csharp
public sealed class DicomDevice : ImageDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | 기본 해상도로 `DicomDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | 제공된 페이지 크기로 기본 해상도(=150)로 `DicomDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | `DicomDevice` 클래스의 새 인스턴스를 초기화합니다. 결과 이미지 파일의 해상도, [`Resolution`](../resolution/) 클래스를 참조하십시오. |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | 제공된 이미지 치수로 기본 해상도(=150)로 `DicomDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | 제공된 페이지 크기와 해상스로 `DicomDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | 제공된 이미지 치수와 해상스로 `DicomDevice` 클래스의 새 인스턴스를 초기화합니다. |

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
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | 페이지를 Dicom으로 변환하고 출력 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 주어진 페이지에서 일부 작업을 수행하고 결과를 파일에 저장합니다. |

### 참조

* 클래스 [ImageDevice](../imagedevice/)
* 네임스페이스 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* 어셈블리 [Aspose.PDF](../../)