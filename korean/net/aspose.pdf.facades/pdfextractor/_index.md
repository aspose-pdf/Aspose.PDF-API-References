---
title: "PdfExtractor 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfExtractor class. PDF 문서에서 이미지와 텍스트를 추출하는 클래스"
type: docs
weight: 4570
url: /ko/net/aspose.pdf.facades/pdfextractor/
---
## PdfExtractor class

PDF 문서에서 이미지와 텍스트를 추출하는 클래스.

```csharp
public sealed class PdfExtractor : Facade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | `PdfExtractor` 객체를 새로 초기화합니다. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | `PdfExtractor` 객체를 *document*를 기반으로 새로 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 Document 파사드를 가져옵니다. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | 추출 작업이 수행될 페이지 범위의 끝 페이지를 가져오거나 설정합니다. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | 이미지 추출 프로세스의 모드를 설정합니다. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | 텍스트 추출 결과의 모드를 설정합니다. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | 텍스트에 히브리어 또는 아랍어 기호가 포함된 경우 true입니다. 이 경우 문자열 함수가 동작을 변경하고 텍스트 처리를 오른쪽에서 왼쪽으로 시작하기 때문에 특별히 고려해야 합니다(숫자 및 기타 비텍스트 문자 제외). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | 입력 파일의 비밀번호를 가져오거나 설정합니다. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | 추출된 이미지의 해상도를 설정하거나 가져옵니다. 기본값은 150입니다. 해상도 값이 높을수록 이미지가 더 선명해집니다. 그러나 해상도 값을 높이면 이미지 추출에 필요한 시간과 메모리가 증가합니다. 일반적으로 선명한 이미지를 얻으려면 해상도를 150 또는 300으로 설정하면 충분합니다. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | 추출 작업이 수행될 페이지 범위 내 시작 페이지를 가져오거나 설정합니다. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | 텍스트 검색 옵션을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Facade를 초기화합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | 스트림에서 PDF 문서를 바인딩합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | 입력 PDF 파일을 바인딩합니다. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Facade와 연결된 Aspose.Pdf.Document를 해제합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Facade를 해제합니다. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Pdf 문서에서 첨부 파일을 추출합니다. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | 첨부 파일 이름으로 PDF 파일에 첨부 파일을 추출합니다. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | PDF 파일에서 이미지를 추출합니다. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Unicode 인코딩을 사용하여 Pdf 문서에서 텍스트를 추출합니다. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | 지정된 인코딩을 사용하여 Pdf 문서에서 텍스트를 추출합니다. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | 모든 첨부 파일을 스트림에 저장합니다. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | 첨부 파일을 파일에 저장합니다. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | 첨부 파일 목록을 가져옵니다. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | PDF 파일의 첨부 파일 목록을 반환합니다. 참고: 이 메서드를 사용하기 전에 ExtractAttachments를 호출해야 합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | PDF 파일에서 다음 이미지를 가져와 스트림에 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | PDF 문서에서 다음 이미지를 가져옵니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | PDF 파일에서 다음 이미지를 가져와 지정된 이미지 형식으로 스트림에 저장합니다. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | PDF 문서에서 지정된 이미지 형식으로 다음 이미지를 가져옵니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | 한 페이지의 텍스트를 스트림에 저장합니다. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | 한 페이지의 텍스트를 파일에 저장합니다. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | 텍스트를 스트림에 저장합니다. 또한 보기: [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | 텍스트를 파일에 저장합니다. 또한 보기: [`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | 텍스트를 스트림에 저장합니다. 또한 보기: [`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | PDF 문서에서 더 많은 이미지에 접근할 수 있는지 확인합니다. 참고: 이 메서드를 사용하기 전에 ExtractImage를 호출해야 합니다. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | 추가 텍스트를 가져올 수 있는지 여부를 나타냅니다. |

### 또 보기

* class [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


