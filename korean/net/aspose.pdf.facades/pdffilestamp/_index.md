---
title: "클래스 PdfFileStamp"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfFileStamp 클래스. PDF 파일에 스탬프, 워터마크 또는 배경을 추가하기 위한 클래스"
type: docs
weight: 4690
url: /ko/net/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class

PDF 파일에 스탬프(워터마크 또는 배경)를 추가하는 클래스.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | PdfFileStamp의 생성자. 입력 파일과 출력 파일은 해당 속성을 통해 지정할 수 있습니다. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | 새 `PdfFileStamp` 객체를 *document*를 기반으로 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | PDF 파일 형식을 설정합니다. 결과 파일은 지정된 파일 형식으로 저장됩니다. 이 속성이 지정되지 않으면 파일은 변환 없이 기본 PDF 형식으로 저장됩니다. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 Document 파사드를 가져옵니다. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | true인 경우 보안을 유지합니다. (이 기능은 다음 버전에서 구현될 예정입니다.) |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | 페이지 번호 매기기 스타일을 가져오거나 설정합니다. 가능한 값: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | 최적화 플래그를 가져오거나 설정합니다. 결과 파일에서 동일한 리소스 스트림은 이 플래그가 설정된 경우 하나의 PDF 객체로 병합됩니다. 이는 결과 파일 크기를 줄일 수 있지만 실행 속도가 느려지고 메모리 요구량이 증가할 수 있습니다. 기본값: false. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | 소스 파일에서 첫 번째 페이지의 높이를 가져옵니다. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | 페이지 번호의 회전을 가져오거나 설정합니다. 회전은 각도로 지정되며 기본값은 0입니다. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | 입력 파일에서 첫 번째 페이지의 너비를 가져옵니다. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | 다음 추가된 스탬프의 스탬프 ID(페이지 헤더/푸터/페이지 번호 포함). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | 입력 파일에서 첫 번째 페이지의 시작 번호를 가져오거나 설정합니다. 이후 페이지는 이 값부터 번호가 매겨집니다. 예를 들어 StartingNumber가 100으로 설정되면 문서 페이지 번호는 100, 101, 102...이 됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | 문서 페이지에 푸터를 추가합니다. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | 페이지의 푸터로 이미지를 추가합니다. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | 문서 페이지에 푸터 이미지로 추가합니다. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | 문서 페이지에 푸터를 추가합니다. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | 페이지의 푸터로 이미지를 추가합니다. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | 페이지 하단에 이미지를 추가합니다. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | 페이지에 헤더를 추가합니다. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | 페이지에 헤더로 이미지를 추가합니다. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | 파일의 페이지에 헤더로 이미지를 추가합니다. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | 파일의 페이지에 헤더를 추가합니다. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | 페이지 상단에 이미지를 추가합니다. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | 페이지에 헤더로 이미지를 추가합니다. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | 페이지에 페이지 번호를 추가합니다. 페이지 번호는 # 기호를 포함할 수 있으며, 이는 페이지 번호로 대체됩니다. 페이지 번호는 페이지 하단에 수평으로 가운데 정렬되어 배치됩니다. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | 파일에 페이지 번호를 추가합니다. 페이지 번호 텍스트는 # 기호를 포함할 수 있으며, 이는 페이지 번호로 대체됩니다. 페이지 번호는 페이지 하단에 수평으로 가운데 정렬되어 배치됩니다. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | 페이지에 페이지 번호를 추가합니다. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | 페이지에 페이지 번호를 추가합니다. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | 페이지의 지정된 위치에 페이지 번호를 추가합니다. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | 페이지의 지정된 위치에 페이지 번호를 추가합니다. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | 문서의 페이지에 페이지 번호를 추가합니다. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | 문서의 페이지에 페이지 번호를 추가합니다. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | 파일에 스탬프를 추가합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Facade를 초기화합니다. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | 열린 파일을 닫고 변경 사항을 저장합니다. 경고: 입력 또는 출력 스트림이 지정된 경우 Close() 메서드에 의해 닫히지 않습니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Facade를 해제합니다. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | 문서를 지정된 스트림에 저장합니다. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | 결과를 지정된 파일에 저장합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | 왼쪽 하단 위치. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | 중앙 하단 위치. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | 오른쪽 하단 위치. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | 왼쪽 위치. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | 오른쪽 위치. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | 상단 let 위치. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | 중앙 상단 위치. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | 오른쪽 상단 위치. |

### 또 보기

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


