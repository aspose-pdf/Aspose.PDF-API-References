---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfViewer 클래스. PDF를 보기 또는 인쇄하는 클래스를 나타냅니다.
type: docs
weight: 4630
url: /ko/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer 클래스

PDF를 보기 또는 인쇄하는 클래스를 나타냅니다.

```csharp
public sealed class PdfViewer : IFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | 새로운 `PdfViewer` 객체를 초기화합니다. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | 새로운 `PdfViewer` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | 파일이 최적화된 크기로 인쇄될지 여부를 나타내는 bool 값을 가져오거나 설정합니다. false인 경우 페이지 크기 조정 없이 인쇄합니다. true인 경우 인쇄 가능한 영역에 맞게 크기를 조정하여 인쇄합니다. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | 파일이 자동 회전으로 인쇄될지 여부를 나타내는 bool 값을 가져오거나 설정합니다. |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | 회전 방향을 나타내는 AutoRotateMode 값을 가져오거나 설정합니다. |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | 페이지 좌표 유형(Media/Crop boxes)을 가져오거나 설정합니다. 기본적으로 CropBox 값이 사용됩니다. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | 양식 프레젠테이션 모드를 가져오거나 설정합니다. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | 수평 정렬을 나타내는 값을 가져오거나 설정합니다. |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | 현재 PDF 파일의 페이지 수를 가져옵니다. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | 입력 문서 비밀번호를 가져오거나 설정합니다. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | 페이지가 그레이스케일로 인쇄되는지 여부를 나타내는 bool 값을 가져오거나 설정합니다. 기본값은 false입니다. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | PdfViewer가 이미지를 인쇄하도록 설정하거나 가져옵니다. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | 문서가 인쇄될 때 프린터 큐에서 문서의 이름을 가져오거나 설정합니다. 기본값은 파일 이름입니다. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | 인쇄할 때 페이지 번호 대화 상자를 생성할지 여부를 나타내는 bool 값을 가져오거나 설정합니다. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | 인쇄 작업의 결과를 가져옵니다. 성공하면 null; 그렇지 않으면 예외 객체입니다. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | 렌더링 옵션을 가져오거나 설정합니다. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | 보기 및 인쇄 중 해상도를 가져오거나 설정합니다. 해상도가 높을수록 속도가 느려집니다. 기본값은 150입니다. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | 스케일 팩터를 나타내는 부동 소수점 값을 가져오거나 설정합니다. 기본값은 1.0입니다. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | 파일 모드에서 인쇄할 때 PDF 페이지를 중간 PNG 파일로 변환하는 사용 여부를 가져오거나 설정합니다. 출력 파일의 크기가 중요할 때 사용합니다. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | 수직 정렬을 나타내는 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | 파사드를 초기화합니다. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | 파사드를 초기화합니다. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | 파사드를 초기화합니다. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | 파사드를 닫습니다. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | 현재 PDF 파일의 페이지를 가져옵니다. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | 하나의 PDF 파일의 페이지를 디코딩합니다. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | 파사드 리소스를 해제합니다. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | 기본 페이지 설정을 가져옵니다. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | 기본 프린터 설정을 가져옵니다. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | 기본 프린터를 사용하여 PDF 문서를 인쇄합니다. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | 프린터 설정으로 PDF 문서를 인쇄합니다. 출력 페이지 크기는 문서의 첫 페이지 크기에 맞게 조정됩니다. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | 설정으로 PDF 문서를 인쇄합니다. 문서 크기가 페이지 크기와 일치하지 않으면 페이지 크기에 맞게 확장됩니다. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | 설정 대화 상자와 함께 PDF 문서를 인쇄합니다. 대화 상자를 사용하여 프린터를 선택합니다. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | 큰 PDF 스트림을 열고 인쇄합니다. PDF 파일에 수백 페이지가 있거나 크기가 3MB를 초과하는 경우 이 방법을 사용하여 더 나은 성능을 얻는 것이 좋습니다. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | 큰 PDF 파일을 열고 인쇄합니다. PDF 파일에 수백 페이지가 있거나 크기가 3MB를 초과하는 경우 이 방법을 사용하여 더 나은 성능을 얻는 것이 좋습니다. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | 지정된 프린터 설정으로 큰 PDF 스트림을 열고 인쇄합니다. PDF 파일에 수백 페이지가 있거나 크기가 3MB를 초과하는 경우 이 방법을 사용하여 더 나은 성능을 얻는 것이 좋습니다. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | 지정된 프린터 설정으로 큰 PDF 파일을 열고 인쇄합니다. PDF 파일에 수백 페이지가 있거나 크기가 3MB를 초과하는 경우 이 방법을 사용하여 더 나은 성능을 얻는 것이 좋습니다. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | 지정된 페이지 설정 및 프린터 설정으로 큰 PDF 스트림을 열고 인쇄합니다. PDF 파일에 수백 페이지가 있거나 크기가 3MB를 초과하는 경우 이 방법을 사용하여 더 나은 성능을 얻는 것이 좋습니다. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | 지정된 페이지 설정 및 프린터 설정으로 큰 PDF 파일을 열고 인쇄합니다. PDF 파일에 수백 페이지가 있거나 크기가 3MB를 초과하는 경우 이 방법을 사용하여 더 나은 성능을 얻는 것이 좋습니다. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | 결과 PDF 문서를 스트림에 저장합니다. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | 결과 PDF 문서를 파일에 저장합니다. |

## 이벤트

| 이름 | 설명 |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | 인쇄가 시작되기 전에 발생하며 기본 인쇄 핸들러 대신 사용자 정의 인쇄 핸들러를 제공할 수 있습니다. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | PdfViewer에서 페이지 인쇄가 끝날 때 발생합니다. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | 마지막 페이지 인쇄 이벤트에 대한 구독을 추가/제거합니다. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | 마지막 페이지 인쇄 이벤트에 대한 구독을 추가/제거합니다. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | 페이지 인쇄가 시작되기 전에 발생합니다. |

### 참조

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)