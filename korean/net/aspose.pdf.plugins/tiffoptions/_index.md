---
title: Class TiffOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TiffOptions 클래스. Tiff 플러그인을 위한 Pdf에서 Tiff 변환기 옵션을 나타냅니다.
type: docs
weight: 9420
url: /ko/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions 클래스

Tiff 플러그인을 위한 [`Tiff`](../tiff/)에서 Pdf 변환기 옵션을 나타냅니다.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TiffOptions](tiffoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | 흑백 변환의 색상 경계 값을 가져오거나 설정합니다. 이 매개변수는 EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle 또는 ColorDepth.Format1bpp == 1과 함께 적용될 수 있습니다. |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | 압축 유형을 가져오거나 설정합니다. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 이미지 변환 모드를 가져옵니다. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | 페이지 좌표 유형(미디어/크롭 박스)을 가져오거나 설정합니다. 기본적으로 CropBox 값이 사용됩니다. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | 색상 깊이를 가져오거나 설정합니다. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션을 반환합니다. |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | 작업의 이름을 반환합니다. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 결과 이미지의 해상도 값을 가져오거나 설정합니다. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 프로세스를 위한 페이지 목록을 가져오거나 설정합니다. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | 모든 페이지를 하나의 다중 페이지 tiff로 저장할 수 있는 플래그를 가져오거나 설정합니다. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | 도형의 유형을 가져오거나 설정합니다. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | 빈 페이지를 건너뛸지 여부를 나타내는 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 새로운 저장 데이터 소스를 설정합니다. 메모리 스트림에 이미지를 저장하려면 null을 매개변수로 전달하십시오. |

### 참조

* 클래스 [PdfToImageOptions](../pdftoimageoptions/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)