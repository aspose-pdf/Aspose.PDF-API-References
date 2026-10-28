---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 파일의 북마크를 생성, 수정, 내보내기, 가져오기 및 삭제를 포함하여 작업하는 클래스를 나타냅니다."
type: docs
weight: 180
url: /ko/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

PDF 파일의 북마크를 생성, 수정, 내보내기, 가져오기 및 삭제를 포함하여 작업하는 클래스를 나타냅니다.

PdfBookmarkEditor 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfBookmarkEditor() | 새로운 [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/) 객체를 초기화합니다. |
| PdfBookmarkEditor(document) | PdfBookmarkEditor 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_stream) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(dest_file) | PDF 문서를 지정된 파일에 저장합니다. |
| save(dest_stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| create_bookmarks() | 모든 페이지에 대한 북마크를 생성합니다. |
| create_bookmarks(bookmark) | 모든 페이지에 대한 북마크를 생성합니다. |
| create_bookmarks(color, bold_flag, italic_flag) | 지정된 색상 및 스타일(굵게, 기울임)로 모든 페이지에 북마크를 생성합니다. |
| create_bookmark_of_page(bookmark_name, page_number) | 지정된 페이지에 대한 북마크를 생성합니다. |
| create_bookmark_of_page(bookmark_name, page_number) | 지정된 페이지들에 대한 북마크를 생성합니다. |
| delete_bookmarks() | PDF 문서의 모든 북마크를 삭제합니다. |
| delete_bookmarks(title) | PDF 문서의 북마크를 삭제합니다. |
| extract_bookmarks() | 문서에서 모든 수준의 북마크를 추출합니다. |
| extract_bookmarks(upper_level) | 문서에서 모든 수준의 북마크를 추출합니다. |
| extract_bookmarks(title) | 지정된 제목을 가진 북마크를 추출합니다. |
| extract_bookmarks(bookmark) | 문서에서 모든 수준의 북마크를 추출합니다. |
| export_bookmarks_to_xml(xml_file) | 북마크를 XML 파일로 내보냅니다. |
| export_bookmarks_to_xml(stream) | 북마크를 XML 스트림으로 내보냅니다. |
| import_bookmarks_with_xml(xml_file) | XML 파일에서 문서로 북마크를 가져옵니다. |
| import_bookmarks_with_xml(stream) | XML 파일에서 문서로 북마크를 가져옵니다. |
| close() | 현재 파사드와 연관된 모든 리소스를 해제합니다. |
| modify_bookmarks(s_title, d_title) | 지정된 북마크 제목에 따라 북마크 제목을 수정합니다. |
| extract_bookmarks_to_html(pdf_file, css_file) | 북마크를 HTML 파일로 내보냅니다. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | 북마크를 HTML 파일로 내보냅니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

