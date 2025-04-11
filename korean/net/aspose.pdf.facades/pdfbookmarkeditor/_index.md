---
title: Class PdfBookmarkEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfBookmarkEditor 클래스. PDF 파일의 북마크를 생성, 수정, 내보내기, 가져오기 및 삭제하는 작업을 위한 클래스입니다.
type: docs
weight: 4420
url: /ko/net/aspose.pdf.facades/pdfbookmarkeditor/
---
## PdfBookmarkEditor 클래스

PDF 파일의 북마크를 생성, 수정, 내보내기, 가져오기 및 삭제하는 작업을 위한 클래스를 나타냅니다.

```csharp
public sealed class PdfBookmarkEditor : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor)() | 새로운 `PdfBookmarkEditor` 객체를 초기화합니다. |
| [PdfBookmarkEditor](pdfbookmarkeditor/#constructor_1)(Document) | *document*를 기반으로 새로운 `PdfBookmarkEditor` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 문서의 파사드를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 파사드를 초기화합니다. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 파사드와 연결된 Aspose.Pdf.Document를 폐기합니다. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage)(string, int) | 지정된 페이지에 대한 북마크를 생성합니다. |
| [CreateBookmarkOfPage](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarkofpage/#createbookmarkofpage_1)(string[], int[]) | 지정된 페이지에 대한 북마크를 생성합니다. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks)() | 모든 페이지에 대한 북마크를 생성합니다. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_1)(Bookmark) | 문서에 지정된 북마크를 생성합니다. 이 메서드는 중첩된 북마크 계층을 형성하는 데 사용할 수 있습니다. |
| [CreateBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/createbookmarks/#createbookmarks_2)(Color, bool, bool) | 지정된 색상과 스타일(굵게, 기울임꼴)로 모든 페이지에 대한 북마크를 생성합니다. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks)() | PDF 문서의 모든 북마크를 삭제합니다. |
| [DeleteBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/deletebookmarks/#deletebookmarks_1)(string) | PDF 문서의 북마크를 삭제합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 폐기합니다. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml)(Stream) | 북마크를 XML 스트림으로 내보냅니다. |
| [ExportBookmarksToXML](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstoxml/#exportbookmarkstoxml_1)(string) | 북마크를 XML 파일로 내보냅니다. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks)() | 문서에서 모든 수준의 북마크를 추출합니다. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_1)(Bookmark) | 지정된 북마크와 같은 제목을 가진 북마크의 자식을 추출합니다. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_2)(bool) | 문서에서 모든 수준의 북마크를 추출합니다. |
| [ExtractBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/extractbookmarks/#extractbookmarks_3)(string) | 지정된 제목을 가진 북마크를 추출합니다. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml)(Stream) | XML 파일에서 문서로 북마크를 가져옵니다. |
| [ImportBookmarksWithXML](../../aspose.pdf.facades/pdfbookmarkeditor/importbookmarkswithxml/#importbookmarkswithxml_1)(string) | XML 파일에서 문서로 북마크를 가져옵니다. |
| [ModifyBookmarks](../../aspose.pdf.facades/pdfbookmarkeditor/modifybookmarks/)(string, string) | 지정된 북마크 제목에 따라 북마크 제목을 수정합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF 문서를 지정된 파일에 저장합니다. |
| static [ExportBookmarksToHtml](../../aspose.pdf.facades/pdfbookmarkeditor/exportbookmarkstohtml/)(string, string) | 북마크를 HTML 파일로 내보냅니다. |

### 참조

* 클래스 [SaveableFacade](../saveablefacade/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)