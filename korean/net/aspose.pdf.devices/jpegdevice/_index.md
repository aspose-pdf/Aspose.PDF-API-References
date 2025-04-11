---
title: Class JpegDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.JpegDevice 클래스. PDF 문서 페이지를 JPEG로 저장하는 데 도움이 되는 이미지 장치를 나타냅니다.
type: docs
weight: 3620
url: /ko/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice 클래스

PDF 문서 페이지를 JPEG로 저장하는 데 도움이 되는 이미지 장치를 나타냅니다.

```csharp
public sealed class JpegDevice : ImageDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | 기본 해상도와 최대 품질로 `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | 제공된 페이지 크기, 기본 해상도(=150) 및 최대 품질로 `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. 결과 이미지 파일의 해상도, [`Resolution`](../resolution/) 클래스를 참조하십시오. |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | 제공된 이미지 크기, 기본 해상도(=150) 및 최대 품질로 `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | 제공된 페이지 크기, 해상도 및 최대 품질로 `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | 제공된 이미지 크기, 해상도 및 최대 품질로 `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | 제공된 페이지 크기, 해상도 및 품질로 `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | 제공된 이미지 크기, 해상도 및 품질로 `JpegDevice` 클래스의 새 인스턴스를 초기화합니다. |

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
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | 페이지를 JPEG로 변환하고 출력 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 주어진 페이지에서 일부 작업을 수행하고 결과를 파일에 저장합니다. |

## 예제

다음 예제는 PDF 파일을 JPEG 이미지로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// The path to your PDF Directory
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The file name of the PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// Initialize instance of Document class
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Create Resolution object 	
		Resolution resolution = new Resolution(300);

		// Initialize JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Close stream
				jpegStream.Close();
			}
		}
	}
```

```csharp
[VB.NET]

    ' The path to your PDF Directory
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    
	' The file name of the PDF
    Dim pdfFile As String = "YOUR_PDF_FILE"
 
    ' Initialize instance of Document class 
    Using pdfDocument As Document = New Document(Path.Combine(dataDir, pdfFile))
	
		' Create Resolution object  
		Dim resolution As Resolution = New Resolution(300)
		
		' Initialize JpegDevice
		Dim jpegDevice As JpegDevice = New JpegDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using jpegStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.jpeg", FileMode.Create)
				
				' Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages(pageCount), jpegStream)

				' Close stream
				jpegStream.Close()
			End Using
		Next
    End Using
```

### 참조

* 클래스 [ImageDevice](../imagedevice/)
* 네임스페이스 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* 어셈블리 [Aspose.PDF](../../)