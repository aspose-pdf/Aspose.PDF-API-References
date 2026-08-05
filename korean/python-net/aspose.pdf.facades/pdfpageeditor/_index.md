---
title: "PdfPageEditor"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "페이지 회전, 확대/축소, 위치 이동 및 페이지 크기 변경을 포함하여 PDF 파일의 페이지를 편집하는 클래스를 나타냅니다."
type: docs
weight: 340
url: /ko/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

페이지 회전, 확대/축소, 위치 이동 및 페이지 크기 변경을 포함하여 PDF 파일의 페이지를 편집하는 클래스를 나타냅니다.

PdfPageEditor 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfPageEditor() | PdfPageEditor 클래스의 생성자입니다. |
| PdfPageEditor(document) | PdfPageEditor 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| transition_duration | 전환 효과의 지속 시간을 가져오거나 설정합니다. |
| transition_type | 프레젠테이션 중 다른 페이지에서 이 페이지로 이동할 때 사용할 전환 스타일을 가져오거나 설정합니다. |
| display_duration | 페이지의 표시 지속 시간을 가져오거나 설정합니다. |
| process_pages | 편집할 페이지 번호를 가져오거나 설정합니다. 기본값은 모든 페이지가 편집됩니다. |
| rotation | 페이지의 회전을 가져오거나 설정합니다. 회전값은 0, 90, 180 또는 270이어야 합니다.<br/>            기본값은 0입니다. |
| zoom | 줌 계수를 가져오거나 설정합니다. 값 1.0은 100%에 해당합니다.<br/>            기본값은 1.0입니다. |
| page_size | 출력 파일의 페이지 크기를 가져오거나 설정합니다. |
| 정렬 | 결과 페이지에서 원본 PDF 내용의 수평 정렬을 가져오거나 설정합니다. 기본값은 AlignmentType.Left입니다. |
| horizontal_alignment | 결과 페이지에서 원본 PDF 내용의 수평 정렬을 가져오거나 설정합니다. 기본값은 AlignmentType.Left입니다. |
| vertical_alignment | 결과 페이지에서 원본 PDF 내용의 수직 정렬을 가져오거나 설정합니다. 기본값은 VerticalAlignmentType.Bottom입니다. |
| vertical_alignment_type | 결과 페이지에서 원본 PDF 내용의 수직 정렬을 가져오거나 설정합니다. 기본값은 VerticalAlignmentType.Bottom입니다. |
| SPLITVOUT | 수직 분할 출력 |
| SPLITHOUT | 외부 가로 분할 |
| SPLITVIN | 내부 세로 분할 |
| SPLITHIN | 내부 가로 분할 |
| BLINDV | 수직 블라인드 |
| BLINDH | 수직 블라인드 |
| INBOX | 내부 박스 |
| OUTBOX | 외부 박스 |
| LRWIPE | 좌우 와이프 |
| RLWIPE | 우좌 와이프 |
| BTWIPE | 하단-상단 와이프 |
| TBWIPE | 상단-하단 와이프 |
| DISSOLVE | 이전 페이지가 사라집니다 |
| LRGLITTER | 좌우 글리터 |
| TBGLITTER | 상하 글리터 |
| DGLITTER | 대각선 글리터 |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_stream) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(output_file) | 변경된 문서를 파일에 저장합니다. |
| save(output_stream) | 변경된 문서를 스트림에 저장합니다. |
| close() | 현재 파사드와 연관된 모든 리소스를 해제합니다. |
| move_position(move_x, move_y) | 원점을 (0, 0)에서 지정된 점으로 이동합니다. <br/>            원점은 왼쪽 하단이며 단위는 포인트(1인치 = 72포인트)입니다. |
| get_pages() | 전체 페이지 수를 반환합니다. |
| get_page_size(page) | 지정된 페이지의 페이지 크기를 반환합니다. |
| get_page_rotation(page) | 지정된 페이지의 회전을 반환합니다. |
| get_page_box_size(page, page_box_name) | 문서에서 지정된 박스의 크기를 반환합니다. |
| apply_changes() | 문서 페이지에 적용된 변경 사항을 적용합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

