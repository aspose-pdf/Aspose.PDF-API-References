---
title: Class PdfConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfConverter 클래스. PDF 파일의 각 페이지를 BMP, JPEG, PNG 및 TIFF 형식의 이미지로 변환하는 클래스를 나타냅니다. PDF에서 지원되는 콘텐츠: 그림, 양식, 주석.
type: docs
weight: 4440
url: /ko/net/aspose.pdf.facades/pdfconverter/
---
## PdfConverter 클래스

PDF 파일의 각 페이지를 BMP, JPEG, PNG 및 TIFF 형식의 이미지로 변환하는 클래스를 나타냅니다. PDF에서 지원되는 콘텐츠: 그림, 양식, 주석.

```csharp
public sealed class PdfConverter : Facade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfConverter](pdfconverter/#constructor)() | 새로운 `PdfConverter` 객체를 초기화합니다. |
| [PdfConverter](pdfconverter/#constructor_1)(Document) | *document*를 기반으로 새로운 `PdfConverter` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CoordinateType](../../aspose.pdf.facades/pdfconverter/coordinatetype/) { get; set; } | 페이지 좌표 유형(미디어/크롭 박스)을 가져오거나 설정합니다. 기본적으로 CropBox 값이 사용됩니다. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 문서 파사드를 가져옵니다. |
| [EndPage](../../aspose.pdf.facades/pdfconverter/endpage/) { get; set; } | 변환하려는 끝 위치를 가져오거나 설정합니다. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfconverter/formpresentationmode/) { get; set; } | 양식 프레젠테이션 모드를 가져오거나 설정합니다. |
| [PageCount](../../aspose.pdf.facades/pdfconverter/pagecount/) { get; } | 페이지 수를 가져옵니다. |
| [Password](../../aspose.pdf.facades/pdfconverter/password/) { get; set; } | 문서 소유자 비밀번호를 가져오거나 설정합니다. |
| [RenderingOptions](../../aspose.pdf.facades/pdfconverter/renderingoptions/) { get; set; } | 렌더링 옵션을 가져오거나 설정합니다. |
| [Resolution](../../aspose.pdf.facades/pdfconverter/resolution/) { get; set; } | 변환 중 해상도를 가져오거나 설정합니다. 해상도가 높을수록 변환 속도가 느려집니다. 기본값은 150입니다. |
| [StartPage](../../aspose.pdf.facades/pdfconverter/startpage/) { get; set; } | 변환하려는 시작 위치를 가져오거나 설정합니다. 최소값은 1입니다. |
| [UserPassword](../../aspose.pdf.facades/pdfconverter/userpassword/) { get; set; } | 문서 사용자 비밀번호를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 파사드를 초기화합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_1)(Stream) | 변환을 위한 PDF 스트림을 바인딩합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdfconverter/bindpdf/#bindpdf_2)(string) | 변환을 위한 PDF 파일을 바인딩합니다. |
| override [Close](../../aspose.pdf.facades/pdfconverter/close/)() | PdfConverter 인스턴스를 닫고 리소스를 해제합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 폐기합니다. |
| [DoConvert](../../aspose.pdf.facades/pdfconverter/doconvert/)() | PDF 문서를 이미지로 변환하기 위한 초기 작업을 수행합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage)(Stream) | 기본 이미지 형식인 JPEG로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_9)(string) | 기본 이미지 형식인 JPEG로 파일에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_4)(Stream, ImageFormat) | 주어진 이미지 형식으로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_1)(Stream, PageSize) | 주어진 페이지 크기로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_13)(string, ImageFormat) | 주어진 이미지 형식으로 파일에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_10)(string, PageSize) | 주어진 페이지 크기와 기본 이미지 형식인 JPEG로 파일에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_6)(Stream, ImageFormat, int) | 주어진 이미지 형식과 품질로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_2)(Stream, PageSize, ImageFormat) | 주어진 페이지 크기로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_15)(string, ImageFormat, int) | 주어진 이미지 형식과 품질로 파일에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_11)(string, PageSize, ImageFormat) | 주어진 페이지 크기와 이미지 형식으로 파일에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_7)(Stream, ImageFormat, int, int) | 주어진 이미지 형식, 크기 및 품질로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_3)(Stream, PageSize, ImageFormat, int) | 주어진 페이지 크기, 이미지 형식 및 품질로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_16)(string, ImageFormat, int, int) | 주어진 이미지 형식과 치수로 파일에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_12)(string, PageSize, ImageFormat, int) | 주어진 페이지 크기, 이미지 형식 및 품질로 파일에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_5)(Stream, ImageFormat, double, double, int) | 주어진 이미지 형식, 크기 및 품질로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_8)(Stream, ImageFormat, int, int, int) | 주어진 이미지 형식, 치수 및 품질로 스트림에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_14)(string, ImageFormat, double, double, int) | 주어진 이미지 형식, 이미지 크기 및 품질로 파일에 이미지를 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfconverter/getnextimage/#getnextimage_17)(string, ImageFormat, int, int, int) | 주어진 이미지 형식, 치수 및 품질로 파일에 이미지를 저장합니다. |
| [HasNextImage](../../aspose.pdf.facades/pdfconverter/hasnextimage/)() | PDF 파일에 더 많은 이미지가 있는지 여부를 나타냅니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff)(Stream) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_10)(string) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_1)(Stream, CompressionType) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_4)(Stream, PageSize) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_2)(Stream, TiffSettings) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_11)(string, CompressionType) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_14)(string, PageSize) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_12)(string, TiffSettings) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_6)(Stream, int, int) | PDF 문서의 각 페이지를 치수로 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_5)(Stream, PageSize, TiffSettings) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_3)(Stream, TiffSettings, IIndexBitmapConverter) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_16)(string, int, int) | PDF 문서의 각 페이지를 치수로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_15)(string, PageSize, TiffSettings) | PDF 문서의 각 페이지를 페이지 크기로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_13)(string, TiffSettings, IIndexBitmapConverter) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_7)(Stream, int, int, CompressionType) | PDF 문서의 각 페이지를 치수로 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_8)(Stream, int, int, TiffSettings) | PDF 문서의 각 페이지를 치수로 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_17)(string, int, int, CompressionType) | PDF 문서의 각 페이지를 치수로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_18)(string, int, int, TiffSettings) | PDF 문서의 각 페이지를 치수로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_9)(Stream, int, int, TiffSettings, IIndexBitmapConverter) | PDF 문서의 각 페이지를 치수로 이미지로 변환하고 이미지를 단일 TIFF 스트림에 저장합니다. |
| [SaveAsTIFF](../../aspose.pdf.facades/pdfconverter/saveastiff/#saveastiff_19)(string, int, int, TiffSettings, IIndexBitmapConverter) | PDF 문서의 각 페이지를 치수로 이미지로 변환하고 이미지를 단일 TIFF 파일에 저장합니다. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf)(Stream) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_3)(string) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일에 저장합니다. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_1)(Stream, PageSize) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_4)(string, PageSize) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일에 저장합니다. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_2)(Stream, int, int) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 스트림에 저장합니다. |
| [SaveAsTIFFClassF](../../aspose.pdf.facades/pdfconverter/saveastiffclassf/#saveastiffclassf_5)(string, int, int) | PDF 문서의 각 페이지를 이미지로 변환하고 이미지를 단일 TIFF ClassF 파일에 저장합니다. |
| static [MergeImages](../../aspose.pdf.facades/pdfconverter/mergeimages/)(List&lt;Stream&gt;, ImageFormat, ImageMergeMode, int?, int?) | 이미지 스트림 목록을 하나의 이미지 스트림으로 병합합니다. PNG/JPG/TIFF 출력 형식이 지원되며, 지원되지 않는 형식의 경우 기본적으로 JPEG로 인코딩된 출력 스트림이 생성됩니다. |
| static [MergeImagesAsTiff](../../aspose.pdf.facades/pdfconverter/mergeimagesastiff/)(List&lt;Stream&gt;) | TIFF 스트림 목록을 하나의 다중 프레임 TIFF 스트림으로 병합합니다. |

### 참조

* 클래스 [Facade](../facade/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)