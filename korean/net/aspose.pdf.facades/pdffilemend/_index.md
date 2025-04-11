---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileMend 클래스. 기존 PDF 문서의 페이지에 텍스트와 이미지를 추가하는 클래스입니다.
type: docs
weight: 4530
url: /ko/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend 클래스

기존 PDF 문서의 페이지에 텍스트와 이미지를 추가하는 클래스를 나타냅니다.

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | 생성자. |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | *document*를 기반으로 새로운 `PdfFileMend` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 문서의 파사드를 가져옵니다. |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | AddText 메서드에서 단어 줄 바꿈을 나타내는 bool 값을 설정합니다. 값이 true이면 FormattedText의 텍스트가 줄 바꿈됩니다. 기본값은 false입니다. |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | 텍스트 위치 지정 전략을 설정하거나 가져옵니다. [`PositioningMode`](../positioningmode/) 기본 모드는 Legacy입니다. |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | 단어 줄 바꿈 알고리즘을 설정하거나 가져옵니다. WordWrapMode 및 IsWordWrap을 참조하십시오. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | 지정된 좌표에 PDF 문서의 지정된 페이지에 이미지를 추가합니다. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | 구현되지 않음. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | 구현되지 않음. |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | 구현되지 않음. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 파사드를 초기화합니다. |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | PdfFileMend 객체를 닫습니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 폐기합니다. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | PDF 문서를 지정된 파일에 저장합니다. |

### 참조

* 클래스 [SaveableFacade](../saveablefacade/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)