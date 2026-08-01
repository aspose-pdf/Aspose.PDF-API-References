---
title: "클래스 PdfToImageOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.PdfToImageOptions 클래스. PdfToImage 플러그인을 위한 옵션을 나타냅니다"
type: docs
weight: 9280
url: /ko/net/aspose.pdf.plugins/pdftoimageoptions/
---
## PdfToImageOptions class

[`PdfToImage`](../pdftoimage/) 플러그인을 위한 옵션을 나타냅니다.

```csharp
public abstract class PdfToImageOptions : IPluginOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftoimageoptions/conversionmode/) { get; } | 이미지 변환 모드를 가져옵니다. |
| [Inputs](../../aspose.pdf.plugins/pdftoimageoptions/inputs/) { get; } | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션을 반환합니다. |
| virtual [OperationName](../../aspose.pdf.plugins/pdftoimageoptions/operationname/) { get; } | 작업 이름을 반환합니다. |
| [OutputResolution](../../aspose.pdf.plugins/pdftoimageoptions/outputresolution/) { get; set; } | 결과 이미지의 해상도 값을 가져오거나 설정합니다. |
| [Outputs](../../aspose.pdf.plugins/pdftoimageoptions/outputs/) { get; } |  |
| [PageList](../../aspose.pdf.plugins/pdftoimageoptions/pagelist/) { get; set; } | 프로세스를 위한 페이지 목록을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdftoimageoptions/addinput/)(IDataSource) | [`PdfToImage`](../pdftoimage/) 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/pdftoimageoptions/addoutput/)(IDataSource) | 새 저장 데이터 소스를 설정합니다. 이는 .만 될 수 있습니다. 이미지를 메모리 스트림에 저장하려면 매개변수로 null을 전달하십시오. |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| enum [ImageConversionMode](../../aspose.pdf.plugins/pdftoimageoptions.imageconversionmode) | PDF 문서를 Jpeg 이미지로 변환할 때 사용할 수 있는 다양한 모드를 정의합니다. [`JpegOptions`](../jpegoptions/) 클래스를 참조하십시오. |

## 비고

PdfImageOptions 클래스는 입력 PDF 문서를 나타내는 데이터(파일, 스트림)를 추가하기 위한 기본 기능을 포함합니다.

### 또 보기

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


