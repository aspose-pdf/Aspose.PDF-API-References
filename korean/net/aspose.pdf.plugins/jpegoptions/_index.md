---
title: "클래스 JpegOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.JpegOptions 클래스. Jpeg 플러그인을 위한 Pdf에서 Jpeg로 변환기 옵션을 나타냅니다"
type: docs
weight: 9050
url: /ko/net/aspose.pdf.plugins/jpegoptions/
---
## JpegOptions class

Pdf에서 Jpeg 변환기 옵션을 나타냅니다. [`Jpeg`](../jpeg/) 플러그인용.

```csharp
public sealed class JpegOptions : PdfToImageOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JpegOptions](jpegoptions/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 이미지 변환 모드를 가져옵니다. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션을 반환합니다. |
| override [OperationName](../../aspose.pdf.plugins/jpegoptions/operationname/) { get; } | 작업의 이름을 반환합니다. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 결과 이미지의 해상도 값을 가져오거나 설정합니다. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 프로세스를 위한 페이지 목록을 가져오거나 설정합니다. |
| [Quality](../../aspose.pdf.plugins/jpegoptions/quality/) { get; set; } | Jpeg 품질을 가져오고 설정합니다 |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 새 저장 데이터 소스를 설정합니다. 이는 .만 될 수 있습니다. 이미지를 메모리 스트림에 저장하려면 매개변수로 null을 전달하십시오. |

### 또 보기

* class [PdfToImageOptions](../pdftoimageoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


