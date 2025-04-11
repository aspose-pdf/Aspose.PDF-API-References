---
title: Class PdfContentEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfContentEditor 클래스. PDF 파일의 내용을 편집하는 클래스입니다.
type: docs
weight: 4430
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor 클래스

PDF 파일의 내용을 편집하는 클래스를 나타냅니다.

```csharp
public sealed class PdfContentEditor : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfContentEditor](pdfcontenteditor/#constructor)() | PdfContentEditor 객체의 생성자입니다. |
| [PdfContentEditor](pdfcontenteditor/#constructor_1)(Document) | *document*를 기반으로 새로운 `PdfContentEditor` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 문서의 파사드를 가져옵니다. |
| [ReplaceTextStrategy](../../aspose.pdf.facades/pdfcontenteditor/replacetextstrategy/) { get; set; } | 텍스트 교체 작업을 위한 매개변수 집합입니다. |
| [TextEditOptions](../../aspose.pdf.facades/pdfcontenteditor/texteditoptions/) { get; set; } | 텍스트 편집 옵션을 가져오거나 설정합니다. |
| [TextReplaceOptions](../../aspose.pdf.facades/pdfcontenteditor/textreplaceoptions/) { get; set; } | 텍스트 교체 옵션을 가져오거나 설정합니다. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfcontenteditor/textsearchoptions/) { get; set; } | 텍스트 검색 옵션을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddDocumentAdditionalAction](../../aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/)(string, string) | 문서 이벤트에 대한 추가 작업을 추가합니다. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment_1)(string, string) | 주석 없이 문서 첨부 파일을 추가합니다. |
| [AddDocumentAttachment](../../aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/#adddocumentattachment)(Stream, string, string) | 주석 없이 문서 첨부 파일을 추가합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 파사드를 초기화합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_1)(Stream) | 편집을 위해 PDF 스트림을 바인딩합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdfcontenteditor/bindpdf/#bindpdf_2)(string) | 편집을 위해 PDF 파일을 바인딩합니다. |
| [ChangeViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/changeviewerpreference/)(int) | 보기 기본 설정을 변경합니다. |
| override [Close](../../aspose.pdf.facades/pdfcontenteditor/close/)() | 열린 문서를 닫습니다. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink)(Rectangle, string, int) | PDF 문서에서 애플리케이션을 실행하는 링크를 생성합니다. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_1)(Rectangle, string, int, Color) | PDF 문서에서 애플리케이션을 실행하는 링크를 생성합니다. |
| [CreateApplicationLink](../../aspose.pdf.facades/pdfcontenteditor/createapplicationlink/#createapplicationlink_2)(Rectangle, string, int, Color, Enum[]) | PDF 문서에서 애플리케이션을 실행하는 링크를 생성합니다. |
| [CreateBookmarksAction](../../aspose.pdf.facades/pdfcontenteditor/createbookmarksaction/)(string, Color, bool, bool, string, string, string) | 지정된 작업으로 북마크를 생성합니다. |
| [CreateCaret](../../aspose.pdf.facades/pdfcontenteditor/createcaret/)(int, Rectangle, Rectangle, string, string, Color) | 커서 주석을 생성합니다. |
| [CreateCustomActionLink](../../aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/)(Rectangle, int, Color, Enum[]) | PDF 문서에서 사용자 정의 작업에 대한 링크를 생성합니다. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_2)(Rectangle, string, string, int, string) | 파일 첨부 주석을 생성합니다. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment)(Rectangle, string, Stream, string, int, string) | 파일 첨부 주석을 생성합니다. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_3)(Rectangle, string, string, int, string, double) | 파일 첨부 주석을 생성합니다. |
| [CreateFileAttachment](../../aspose.pdf.facades/pdfcontenteditor/createfileattachment/#createfileattachment_1)(Rectangle, string, Stream, string, int, string, double) | 파일 첨부 주석을 생성합니다. |
| [CreateFreeText](../../aspose.pdf.facades/pdfcontenteditor/createfreetext/)(Rectangle, string, int) | PDF 문서에서 자유 텍스트 주석을 생성합니다. |
| [CreateJavaScriptLink](../../aspose.pdf.facades/pdfcontenteditor/createjavascriptlink/)(string, Rectangle, int, Color) | PDF 문서에서 JavaScript에 대한 링크를 생성합니다. |
| [CreateLine](../../aspose.pdf.facades/pdfcontenteditor/createline/)(Rectangle, string, float, float, float, float, int, int, Color, string, int[], string[]) | 선 주석을 생성합니다. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink)(Rectangle, int, int) | PDF 문서에서 로컬 링크를 생성합니다. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_1)(Rectangle, int, int, Color) | PDF 문서에서 로컬 링크를 생성합니다. |
| [CreateLocalLink](../../aspose.pdf.facades/pdfcontenteditor/createlocallink/#createlocallink_2)(Rectangle, int, int, Color, Enum[]) | PDF 문서에서 로컬 링크를 생성합니다. |
| [CreateMarkup](../../aspose.pdf.facades/pdfcontenteditor/createmarkup/)(Rectangle, string, int, int, Color) | PDF 문서에서 마크업 주석을 생성합니다. |
| [CreateMovie](../../aspose.pdf.facades/pdfcontenteditor/createmovie/)(Rectangle, string, int) | 영화 주석을 생성합니다. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink)(Rectangle, string, int, int) | 다른 PDF 문서 페이지에 대한 링크를 생성합니다. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_1)(Rectangle, string, int, int, Color) | 다른 PDF 문서 페이지에 대한 링크를 생성합니다. |
| [CreatePdfDocumentLink](../../aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/#createpdfdocumentlink_2)(Rectangle, string, int, int, Color, Enum[]) | 다른 PDF 문서 페이지에 대한 링크를 생성합니다. |
| [CreatePolygon](../../aspose.pdf.facades/pdfcontenteditor/createpolygon/)(LineInfo, int, Rectangle, string) | 다각형 주석을 생성합니다. |
| [CreatePolyLine](../../aspose.pdf.facades/pdfcontenteditor/createpolyline/)(LineInfo, int, Rectangle, string) | 폴리라인 주석을 생성합니다. |
| [CreatePopup](../../aspose.pdf.facades/pdfcontenteditor/createpopup/)(Rectangle, string, bool, int) | PDF 문서에서 팝업 주석을 생성합니다. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp)(int, Rectangle, string, Color, Stream) | 고무 도장 주석을 생성합니다. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_1)(int, Rectangle, string, Color, string) | 고무 도장 주석을 생성합니다. |
| [CreateRubberStamp](../../aspose.pdf.facades/pdfcontenteditor/createrubberstamp/#createrubberstamp_2)(int, Rectangle, string, string, Color) | 고무 도장 주석을 생성합니다. |
| [CreateSound](../../aspose.pdf.facades/pdfcontenteditor/createsound/)(Rectangle, string, string, int, string) | 소리 주석을 생성합니다. |
| [CreateSquareCircle](../../aspose.pdf.facades/pdfcontenteditor/createsquarecircle/)(Rectangle, string, Color, bool, int, int) | 사각형-원 주석을 생성합니다. |
| [CreateText](../../aspose.pdf.facades/pdfcontenteditor/createtext/)(Rectangle, string, string, bool, string, int) | PDF 문서에서 텍스트 주석을 생성합니다. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink)(Rectangle, string, int) | PDF 문서에서 웹 링크를 생성합니다. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_1)(Rectangle, string, int, Color) | PDF 문서에서 웹 링크를 생성합니다. |
| [CreateWebLink](../../aspose.pdf.facades/pdfcontenteditor/createweblink/#createweblink_2)(Rectangle, string, int, Color, Enum[]) | PDF 문서에서 웹 링크를 생성합니다. |
| [DeleteAttachments](../../aspose.pdf.facades/pdfcontenteditor/deleteattachments/)() | PDF 문서의 모든 첨부 파일을 삭제합니다. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage)() | PDF 문서의 모든 이미지를 삭제합니다. |
| [DeleteImage](../../aspose.pdf.facades/pdfcontenteditor/deleteimage/#deleteimage_1)(int, int[]) | 지정된 페이지에서 지정된 이미지를 삭제합니다. |
| [DeleteStamp](../../aspose.pdf.facades/pdfcontenteditor/deletestamp/)(int, int[]) | 지정된 페이지에서 스탬프 인덱스를 사용하여 여러 스탬프를 삭제합니다. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid)(int) | 문서의 모든 페이지에서 ID로 스탬프를 삭제합니다. |
| [DeleteStampById](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyid/#deletestampbyid_1)(int, int) | 지정된 페이지에서 스탬프 ID로 스탬프를 삭제합니다. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids_1)(int[]) | 문서의 모든 페이지에서 지정된 ID로 스탬프를 삭제합니다. |
| [DeleteStampByIds](../../aspose.pdf.facades/pdfcontenteditor/deletestampbyids/#deletestampbyids)(int, int[]) | 지정된 페이지에서 여러 스탬프 ID로 스탬프를 삭제합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 폐기합니다. |
| [DrawCurve](../../aspose.pdf.facades/pdfcontenteditor/drawcurve/)(LineInfo, int, Rectangle, string) | 곡선 주석을 생성합니다. |
| [ExtractLink](../../aspose.pdf.facades/pdfcontenteditor/extractlink/)() | PDF 문서에 포함된 링크 인스턴스의 컬렉션을 추출합니다. |
| [GetStamps](../../aspose.pdf.facades/pdfcontenteditor/getstamps/)(int) | 페이지의 스탬프 배열을 반환합니다. |
| [GetViewerPreference](../../aspose.pdf.facades/pdfcontenteditor/getviewerpreference/)() | 보기 기본 설정을 반환합니다. |
| [HideStampById](../../aspose.pdf.facades/pdfcontenteditor/hidestampbyid/)(int, int) | 스탬프를 숨깁니다. 숨긴 후에는 ShowStampById 메서드를 사용하여 스탬프의 가시성을 복원할 수 있습니다. |
| [MoveStamp](../../aspose.pdf.facades/pdfcontenteditor/movestamp/)(int, int, double, double) | 페이지에서 스탬프의 위치를 변경합니다. |
| [MoveStampById](../../aspose.pdf.facades/pdfcontenteditor/movestampbyid/)(int, int, double, double) | 페이지에서 스탬프의 위치를 변경합니다. |
| [RemoveDocumentOpenAction](../../aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/)() | 문서에서 열기 작업을 제거합니다. 이 작업은 시작 시 명시적인 'GoTo' 작업을 사용하는 여러 문서를 연결할 때 유용합니다. |
| [ReplaceImage](../../aspose.pdf.facades/pdfcontenteditor/replaceimage/)(int, int, string) | PDF 문서의 지정된 페이지에서 지정된 이미지를 다른 이미지로 교체합니다. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_2)(string, string) | PDF 파일의 텍스트를 교체합니다. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext)(string, int, string) | 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_4)(string, string, int) | PDF 파일의 텍스트를 교체하고 글꼴 크기를 설정합니다. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_3)(string, string, TextState) | 지정된 [`TextState`](../../aspose.pdf.text/textstate/) 객체를 사용하여 PDF 파일의 텍스트를 교체합니다. |
| [ReplaceText](../../aspose.pdf.facades/pdfcontenteditor/replacetext/#replacetext_1)(string, int, string, TextState) | 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. 교체된 텍스트에 대해 [`TextState`](../../aspose.pdf.text/textstate/) 객체(글꼴 패밀리, 색상)를 지정할 수 있습니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF 문서를 지정된 파일에 저장합니다. |
| [ShowStampById](../../aspose.pdf.facades/pdfcontenteditor/showstampbyid/)(int, int) | HiddenStampById로 숨겨진 스탬프를 표시합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DocumentClose](../../aspose.pdf.facades/pdfcontenteditor/documentclose/) | 문서 이벤트 유형. 문서를 닫습니다. |
| const [DocumentOpen](../../aspose.pdf.facades/pdfcontenteditor/documentopen/) | 문서 이벤트 유형. 문서를 엽니다. |
| const [DocumentPrinted](../../aspose.pdf.facades/pdfcontenteditor/documentprinted/) | 문서 이벤트 유형. 인쇄 후 작업을 실행합니다. |
| const [DocumentSaved](../../aspose.pdf.facades/pdfcontenteditor/documentsaved/) | 문서 이벤트 유형. 저장 후 작업을 실행합니다. |
| const [DocumentWillPrint](../../aspose.pdf.facades/pdfcontenteditor/documentwillprint/) | 문서 이벤트 유형. 인쇄 전에 작업을 실행합니다. |
| const [DocumentWillSave](../../aspose.pdf.facades/pdfcontenteditor/documentwillsave/) | 문서 이벤트 유형. 저장 전에 작업을 실행합니다. |

### 참조

* 클래스 [SaveableFacade](../saveablefacade/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)