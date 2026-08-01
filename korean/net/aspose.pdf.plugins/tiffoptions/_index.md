---
title: "TiffOptions 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.TiffOptions 클래스. Tiff 플러그인을 위한 Pdf를 Tiff로 변환하는 옵션을 나타냅니다."
type: docs
weight: 9570
url: /ko/net/aspose.pdf.plugins/tiffoptions/
---
## TiffOptions class

`[`Tiff`](../tiff/)` 플러그인을 위한 Pdf를 Tiff로 변환하는 옵션을 나타냅니다.

```csharp
public sealed class TiffOptions : PdfToImageOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TiffOptions](tiffoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Brightness](../../aspose.pdf.plugins/tiffoptions/brightness/) { get; set; } | 흰색과 검은색 색상 변환의 값 경계를 가져오거나 설정합니다. 이 매개변수는 EncoderValue.CompressionCCITT4, EncoderValue.CompressionCCITT3, EncoderValue.CompressionRle 또는 ColorDepth.Format1bpp == 1과 함께 적용될 수 있습니다. |
| [Compression](../../aspose.pdf.plugins/tiffoptions/compression/) { get; set; } | 압축 유형을 가져오거나 설정합니다. |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 이미지 변환 모드를 가져옵니다. |
| [CoordinateType](../../aspose.pdf.plugins/tiffoptions/coordinatetype/) { get; set; } | 페이지 좌표 유형(미디어/크롭 박스)을 가져오거나 설정합니다. 기본값으로 CropBox가 사용됩니다. |
| [Depth](../../aspose.pdf.plugins/tiffoptions/depth/) { get; set; } | 색 깊이를 가져오거나 설정합니다. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션을 반환합니다. |
| override [OperationName](../../aspose.pdf.plugins/tiffoptions/operationname/) { get; } | 작업의 이름을 반환합니다. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 결과 이미지의 해상도 값을 가져오거나 설정합니다. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 프로세스를 위한 페이지 목록을 가져오거나 설정합니다. |
| [SaveAsMultiPageTiff](../../aspose.pdf.plugins/tiffoptions/saveasmultipagetiff/) { get; set; } | 모든 페이지를 하나의 다중 페이지 tiff로 저장하도록 허용하는 플래그를 가져오고 설정합니다. |
| [Shape](../../aspose.pdf.plugins/tiffoptions/shape/) { get; set; } | 모양 유형을 가져오거나 설정합니다. |
| [SkipBlankPages](../../aspose.pdf.plugins/tiffoptions/skipblankpages/) { get; set; } | 빈 페이지를 건너뛸지 여부를 나타내는 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 새 저장 데이터 소스를 설정합니다. 이는 .만 될 수 있습니다. 이미지를 메모리 스트림에 저장하려면 매개변수로 null을 전달하십시오. |

### 또 보기

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


