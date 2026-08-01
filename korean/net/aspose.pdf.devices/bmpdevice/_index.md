---
title: "클래스 BmpDevice"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Devices.BmpDevice 클래스. PDF 문서 페이지를 bmp로 저장하는 데 도움이 되는 이미지 장치를 나타냅니다."
type: docs
weight: 3640
url: /ko/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

pdf 문서 페이지를 bmp 형식으로 저장하는 데 도움이 되는 이미지 장치를 나타냅니다.

```csharp
public sealed class BmpDevice : ImageDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | 기본 해상도로 `BmpDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | 제공된 페이지 크기와 기본 해상도 (=150)로 `BmpDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | `BmpDevice` 클래스의 새 인스턴스를 초기화합니다. 결과 이미지 파일의 해상도는 [`Resolution`](../resolution/) 클래스를 참조하십시오. |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | 제공된 이미지 차원과 기본 해상도 (=150)로 `BmpDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | 제공된 페이지 크기와 해상도로 `BmpDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | 제공된 이미지 차원과 해상도로 `BmpDevice` 클래스의 새 인스턴스를 초기화합니다. |

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
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | 페이지를 bmp로 변환하고 출력 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 지정된 page에 대해 일부 작업을 수행하고 결과를 파일에 저장합니다. |

## 예제

다음 예제는 PDF 파일을 BMP 이미지로 변환하는 방법을 보여줍니다.

```csharp
[C#]
	// PDF 디렉터리 경로
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// PDF 파일 이름
	string pdfFile = @"YOUR_PDF_FILE";

	// Document 클래스의 인스턴스를 초기화합니다.
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Resolution 객체를 생성합니다 	
		Resolution resolution = new Resolution(300);

		// BmpDevice를 초기화합니다.
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// 특정 페이지를 변환하고 이미지를 스트림에 저장합니다.
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// 스트림 닫기
				bmpStream.Close();
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
		
		' Initialize BmpDevice  
		Dim bmpDevice As BmpDevice = New BmpDevice(resolution)
		
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using bmpStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.bmp", FileMode.Create)
				
				' Convert a particular page and save the image to stream
				bmpDevice.Process(pdfDocument.Pages(pageCount), bmpStream)

				' Close stream
				bmpStream.Close()
			End Using
		Next
	End Using
```

### 또 보기

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


