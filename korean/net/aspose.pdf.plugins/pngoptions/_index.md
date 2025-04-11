---
title: Class PngOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PngOptions 클래스. Png 플러그인을 위한 Pdf에서 Png 변환기 옵션을 나타냅니다.
type: docs
weight: 9180
url: /ko/net/aspose.pdf.plugins/pngoptions/
---
## PngOptions class

Png 플러그인을 위한 [`Pdf`](../png/)에서 Png 변환기 옵션을 나타냅니다.

```csharp
public sealed class PngOptions : PdfToImageOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PngOptions](pngoptions/)() | 기본 생성자입니다. |

## Properties

| Name | Description |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 이미지 변환 모드를 가져옵니다. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션을 반환합니다. |
| override [OperationName](../../aspose.pdf.plugins/pngoptions/operationname/) { get; } | 작업의 이름을 반환합니다. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 결과 이미지의 해상도 값을 가져오거나 설정합니다. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 프로세스를 위한 페이지 목록을 가져오거나 설정합니다. |

## Methods

| Name | Description |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 새로운 저장 데이터 소스를 설정합니다. . 메모리 스트림에 이미지를 저장하려면 null을 매개변수로 전달하십시오. |

### See Also

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)