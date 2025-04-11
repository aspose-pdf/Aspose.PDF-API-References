---
title: Class JpegOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.JpegOptions 클래스. Jpeg 플러그인을 위한 Pdf에서 Jpeg 변환기 옵션을 나타냅니다.
type: docs
weight: 8920
url: /ko/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions 클래스

[`Jpeg`](../jpeg/) 플러그인을 위한 Pdf에서 Jpeg 변환기 옵션을 나타냅니다.

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JpegOptions](jpegoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 이미지 변환 모드를 가져옵니다. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션을 반환합니다. |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | 작업의 이름을 반환합니다. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 결과 이미지의 해상도 값을 가져오거나 설정합니다. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 프로세스를 위한 페이지 목록을 가져오거나 설정합니다. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Jpeg 품질을 가져오고 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 새로운 저장 데이터 소스를 설정합니다. 메모리 스트림에 이미지를 저장하려면 null을 매개변수로 전달하십시오. |

### 참조

* 클래스 [PdfToImageOptions](../pdftoimageoptions/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)