---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.TiffDevice 클래스. 이 클래스는 PDF 문서를 페이지별로 하나의 TIFF 이미지로 저장하는 데 도움을 줍니다.
type: docs
weight: 3700
url: /ko/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice 클래스

이 클래스는 PDF 문서를 페이지별로 하나의 TIFF 이미지로 저장하는 데 도움을 줍니다.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | 기본 설정으로 `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | `TiffDevice` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | 양식 프레젠테이션 모드를 가져오거나 설정합니다. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | 이미지 출력 높이를 가져옵니다. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | 렌더링 옵션을 가져오거나 설정합니다. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | 이미지 해상도를 가져옵니다. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | PDF를 TIFF 이미지로 매핑하기 위한 설정을 가져옵니다. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | 이미지 출력 너비를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | 입력 스트림에 대해 브래들리 이진화를 수행합니다. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | 전체 문서를 처리하고 결과를 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | 전체 문서를 처리하고 결과를 파일에 저장합니다. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | 주어진 페이지에서 일부 작업을 수행하고 결과를 파일에 저장합니다. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | 특정 문서 페이지를 TIFF로 변환하고 출력 스트림에 저장합니다. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | 문서의 특정 페이지를 처리하고 결과를 파일에 저장합니다. |

## 예제

다음 예제는 PDF 파일을 TIFF 이미지로 변환하는 방법을 보여줍니다.

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
		
		// Create TiffSettings object
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Create TIFF device
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir + "AllPagesToTIFF_out.tif");
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
		
		' Create TiffSettings object
		Dim tiffSettings As TiffSettings = New TiffSettings With {
		  .Compression = CompressionType.None,
			.Depth = ColorDepth.[Default],
			.Shape = ShapeType.Landscape,
			.SkipBlankPages = False
		}

		' Create TIFF device
		Dim tiffDevice As TiffDevice = New TiffDevice(resolution, tiffSettings)

		' Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir & "AllPagesToTIFF_out.tif")

	End Using
```

### 참조

* 클래스 [DocumentDevice](../documentdevice/)
* 네임스페이스 [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* 어셈블리 [Aspose.PDF](../../)