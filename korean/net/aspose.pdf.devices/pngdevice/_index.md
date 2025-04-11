---
title: Class PngDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.PngDevice 클래스. PDF 문서 페이지를 PNG로 저장하는 데 도움이 되는 이미지 장치를 나타냅니다.
type: docs
weight: 3650
url: /ko/net/aspose.pdf.devices/pngdevice/
---
## PngDevice 클래스

PDF 문서 페이지를 PNG로 저장하는 데 도움이 되는 이미지 장치를 나타냅니다.

```csharp
public sealed class PngDevice : ImageDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | 기본 해상도로 `PngDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | 제공된 페이지 크기로 `PngDevice` 클래스의 새 인스턴스를 초기화하며, 기본 해상도(=150)를 사용합니다. |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | `PngDevice` 클래스의 새 인스턴스를 초기화합니다. 결과 이미지 파일의 해상도, [`Resolution`](../resolution/) 클래스를 참조하십시오. |
| [PngDevice](pngdevice/#constructor_4)(int, int) | 제공된 이미지 크기로 `PngDevice` 클래스의 새 인스턴스를 초기화하며, 기본 해상도(=150)를 사용합니다. |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | 제공된 페이지 크기와 해상스로 `PngDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | 제공된 이미지 크기와 해상스로 `PngDevice` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | 페이지 좌표 유형(Media/Crop 박스)을 가져오거나 설정합니다. 기본적으로 CropBox 값이 사용됩니다. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | 양식 프레젠테이션 모드를 가져오거나 설정합니다. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | 이미지 출력 높이를 가져옵니다. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | 렌더링 옵션을 가져오거나 설정합니다. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | 이미지 해상도를 가져옵니다. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | 이미지에 투명 배경이 있는지 여부를 가져오거나 설정합니다. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | 이미지 출력 너비를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | 페이지를 PNG로 변환하고 출력 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 주어진 페이지에서 일부 작업을 수행하고 결과를 파일에 저장합니다. |

## 예제

다음 예제는 PDF 파일을 PNG 이미지로 변환하는 방법을 보여줍니다.

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

		// Initialize PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Close stream
				pngStream.Close();
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
		' initialize PngDevice  

		Dim pngDevice As PngDevice = New PngDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using pngStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.png", FileMode.Create)
				' Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages(pageCount), pngStream)

				' Close stream
				pngStream.Close()
			End Using
		Next
	End Using
```

### 참조

* 클래스 [ImageDevice](../imagedevice/)
* 네임스페이스 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* 어셈블리 [Aspose.PDF](../../)