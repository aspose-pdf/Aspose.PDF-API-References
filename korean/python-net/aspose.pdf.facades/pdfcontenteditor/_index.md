---
title: "PdfContentEditor"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 파일의 내용을 편집하는 클래스를 나타냅니다."
type: docs
weight: 190
url: /ko/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

PDF 파일의 내용을 편집하는 클래스를 나타냅니다.

PdfContentEditor 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfContentEditor() | PdfContentEditor 객체의 생성자입니다. |
| PdfContentEditor(document) | PdfContentEditor 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| text_search_options | 텍스트 검색 옵션을 가져오거나 설정합니다. |
| text_edit_options | 텍스트 편집 옵션을 가져오거나 설정합니다. |
| text_replace_options | 텍스트 교체 옵션을 가져오거나 설정합니다. |
| replace_text_strategy | 텍스트 교체 작업을 위한 매개변수 집합 |
| DOCUMENT_OPEN | 문서 이벤트 유형입니다. 문서를 엽니다. |
| DOCUMENT_CLOSE | 문서 이벤트 유형입니다. 문서를 닫습니다. |
| DOCUMENT_WILL_SAVE | 문서 이벤트 유형입니다. 저장하기 전에 작업을 실행합니다. |
| DOCUMENT_SAVED | 문서 이벤트 유형입니다. 저장 후에 작업을 실행합니다. |
| DOCUMENT_WILL_PRINT | 문서 이벤트 유형입니다. 인쇄하기 전에 작업을 실행합니다. |
| DOCUMENT_PRINTED | 문서 이벤트 유형입니다. 인쇄 후에 작업을 실행합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(input_file) | 편집을 위해 PDF 파일을 바인딩합니다. |
| bind_pdf(input_stream) | 편집을 위해 PDF 스트림을 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(dest_file) | PDF 문서를 지정된 파일에 저장합니다. |
| save(dest_stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| create_web_link(rect, url, original_page, clr) | PDF 문서에 웹 링크를 생성합니다. |
| create_web_link(rect, url, original_page) | PDF 문서에 웹 링크를 생성합니다. |
| create_local_link(rect, des_page, original_page, clr) | PDF 문서에 로컬 링크를 생성합니다. |
| create_local_link(rect, des_page, original_page) | PDF 문서에 로컬 링크를 생성합니다. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | 다른 PDF 문서 페이지에 대한 링크를 생성합니다. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | 다른 PDF 문서 페이지에 대한 링크를 생성합니다. |
| create_application_link(rect, application, page, clr) | PDF 문서에서 애플리케이션을 실행하는 링크를 생성합니다. |
| create_application_link(rect, application, page) | PDF 문서에서 애플리케이션을 실행하는 링크를 생성합니다. |
| create_file_attachment(rect, contents, file_path, page, name) | 파일 첨부 주석을 생성합니다. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | 파일 첨부 주석을 생성합니다. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | 파일 첨부 주석을 생성합니다. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | 파일 첨부 주석을 생성합니다. |
| add_document_attachment(file_attachment_path, description) | 주석 없이 문서 첨부 파일을 추가합니다. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | 주석 없이 문서 첨부 파일을 추가합니다. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | 고무 스탬프 주석을 생성합니다. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | 고무 스탬프 주석을 생성합니다. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | 고무 스탬프 주석을 생성합니다. |
| delete_image(page_number, index) | 지정된 페이지에서 지정된 이미지를 삭제합니다. |
| delete_image() | 지정된 페이지에서 지정된 이미지를 삭제합니다. |
| replace_text(src_string, the_page, dest_string, text_state) | 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 객체(글꼴 패밀리, 색상)를 지정하여 교체된 텍스트를 지정할 수 있습니다. |
| replace_text(src_string, dest_string) | 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 객체(글꼴 패밀리, 색상)를 지정하여 교체된 텍스트를 지정할 수 있습니다. |
| replace_text(src_string, the_page, dest_string) | 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 객체(글꼴 패밀리, 색상)를 지정하여 교체된 텍스트를 지정할 수 있습니다. |
| replace_text(src_string, dest_string, text_state) | 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 객체(글꼴 패밀리, 색상)를 지정하여 교체된 텍스트를 지정할 수 있습니다. |
| replace_text(src_string, dest_string, font_size) | 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. [TextState](/pdf/python-net/aspose.pdf.text/textstate/) 객체(글꼴 패밀리, 색상)를 지정하여 교체된 텍스트를 지정할 수 있습니다. |
| delete_stamp_by_ids(stamp_ids) | 문서의 모든 페이지에서 지정된 ID를 가진 스탬프를 삭제합니다. |
| delete_stamp_by_ids(page_number, stamp_ids) | 문서의 모든 페이지에서 지정된 ID를 가진 스탬프를 삭제합니다. |
| delete_stamp_by_id(page_number, stamp_id) | 문서의 모든 페이지에서 지정된 ID를 가진 스탬프를 삭제합니다. |
| delete_stamp_by_id(stamp_id) | 문서의 모든 페이지에서 지정된 ID를 가진 스탬프를 삭제합니다. |
| close() | 열린 문서를 닫습니다. |
| extract_link() | PDF 문서에 포함된 Link 인스턴스 컬렉션을 추출합니다. |
| create_java_script_link(code, rect, original_page, color) | PDF 문서에서 JavaScript에 대한 링크를 생성합니다. |
| create_text(rect, title, contents, open, icon, page) | PDF 문서에 텍스트 주석을 생성합니다 |
| create_free_text(rect, contents, page) | PDF 문서에 자유 텍스트 주석을 생성합니다 |
| create_markup(rect, contents, type, page, clr) | PDF 문서에 마크업 주석을 생성합니다. |
| create_popup(rect, contents, open, page) | PDF 문서에 팝업 주석을 생성합니다. |
| delete_attachments() | PDF 문서의 모든 첨부 파일을 삭제합니다. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | 선 주석을 생성합니다. |
| create_square_circle(rect, contents, clr, square, page, border_width) | 사각형-원 주석을 생성합니다. |
| draw_curve(line_info, page, annot_rect, annot_contents) | 곡선 주석을 생성합니다. |
| create_polygon(line_info, page, annot_rect, annot_contents) | 다각형 주석을 생성합니다. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | 폴리라인 주석을 생성합니다. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | 캐럿 주석을 생성합니다. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | 지정된 동작으로 북마크를 생성합니다. |
| add_document_additional_action(event_type, code) | 문서 이벤트에 대한 추가 동작을 추가합니다. |
| remove_document_open_action() | 문서에서 열기 동작을 제거합니다. 이 작업은 시작 시 명시적인 'GoTo' 동작을 사용하는 여러 문서를 연결할 때 유용합니다. |
| change_viewer_preference(viewer_attribution) | 보기 기본 설정을 변경합니다. |
| get_viewer_preference() | 보기 기본 설정을 반환합니다. |
| replace_image(page_number, index, image_file) | PDF 문서의 지정된 페이지에 있는 지정된 이미지를 다른 이미지로 교체합니다. |
| create_movie(rect, file_path, page) | 동영상 주석을 생성합니다. |
| create_sound(rect, file_path, name, page, rate) | 오디오 주석을 생성합니다. |
| delete_stamp(page_number, index) | 지정된 페이지에서 스탬프 인덱스로 여러 스탬프를 삭제합니다. |
| hide_stamp_by_id(page_number, stamp_id) | 스탬프를 숨깁니다. 숨긴 후에는 ShowStampById 메서드로 스탬프 가시성을 복원할 수 있습니다. |
| show_stamp_by_id(page_number, stamp_id) | HiddenStampById에 의해 숨겨진 스탬프를 표시합니다. |
| move_stamp_by_id(page_number, stamp_id, x, y) | 페이지에서 스탬프의 위치를 변경합니다. |
| move_stamp(page_number, stamp_index, x, y) | 페이지에서 스탬프의 위치를 변경합니다. |
| get_stamps(page_number) | 페이지에 있는 스탬프 배열을 반환합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

