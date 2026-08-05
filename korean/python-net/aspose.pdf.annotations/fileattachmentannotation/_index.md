---
title: "FileAttachmentAnnotation"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "클래스는 파일 첨부 주석을 설명합니다."
type: docs
weight: 170
url: /ko/python-net/aspose.pdf.annotations/fileattachmentannotation/
---

## FileAttachmentAnnotation class

클래스는 파일 첨부 주석을 설명합니다.

FileAttachmentAnnotation 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| FileAttachmentAnnotation(page, rect, file_spec) | FileAttachmentAnnotation 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| vertical_alignment | 없음 |
| horizontal_alignment | 주석에 대한 텍스트 정렬을 가져오거나 설정합니다. |
| margin | 없음 |
| is_first_paragraph_in_column | 없음 |
| is_kept_with_next | 없음 |
| is_in_new_page | 없음 |
| is_in_line_paragraph | 없음 |
| hyperlink | 없음 |
| z_index | 없음 |
| update_appearance_on_convert | true인 경우, PF 문서를 이미지로 변환하기 전에 주석 모양이 업데이트됩니다. 이는 필드를 올바르게 변환하도록 허용하지만 아마도 더 많은 시간이 필요합니다. |
| use_font_subset | 이 속성이 true로 설정되면, 글꼴이 문서에 서브셋으로 추가됩니다. 기본값은 true입니다. |
| flags | 주석의 플래그. |
| annotation_type | 주석의 유형을 가져옵니다. |
| width | 주석의 너비를 가져오거나 설정합니다. |
| actions | 주석 작업 목록을 가져옵니다. |
| 높이 | 주석의 높이를 가져오거나 설정합니다. |
| 사각형 | 주석 사각형을 가져오거나 설정합니다. |
| 내용 | 주석 텍스트를 가져오거나 설정합니다. |
| 이름 | 페이지상의 주석 이름을 가져오거나 설정합니다. |
| 수정됨 | 주석이 최근에 수정된 날짜와 시간을 가져오거나 설정합니다. |
| 색상 | 주석 색상을 가져오거나 설정합니다. |
| border | 주석 테두리 특성을 가져오거나 설정합니다. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| active_state | 현재 주석 외관 상태를 가져오거나 설정합니다. |
| 특징 | 주석 특성을 가져옵니다. |
| 상태 | 주석의 외관 사전을 가져옵니다. |
| 정렬 | 주석 정렬. 이 속성은 더 이상 사용되지 않습니다. 대신 HorizontalAligment를 사용하십시오. |
| text_horizontal_alignment | 주석에 대한 텍스트 정렬을 가져오거나 설정합니다. |
| full_name | 주석의 전체 자격 이름을 가져옵니다. |
| 모양 | 주석의 외관 사전을 가져옵니다. |
| page_index | 주석이 포함된 페이지의 인덱스를 가져옵니다. |
| 제목 | 주석의 제목 표시줄에 표시될 텍스트를 가져오거나 설정합니다. |
| rich_text | 주석이 열릴 때 팝업 창에 표시될 리치 텍스트 문자열을 가져오거나 설정합니다. |
| creation_date | 주석이 생성된 날짜와 시간을 가져옵니다. |
| subject | 객체의 설명을 나타내는 텍스트를 가져옵니다. |
| popup | 이 주석과 연결된 텍스트를 입력하거나 편집하기 위한 팝업 주석입니다. |
| opacity | 아이콘의 불투명도를 0에서 1 사이로 가져오거나 설정합니다: 0 - 완전히 투명, 1 - 완전히 불투명. |
| in_reply_to | 이 주석이 "답변하는" 주석에 대한 참조입니다.<br/>            두 주석은 문서의 같은 페이지에 있어야 합니다. |
| reply_type | 이 주석과 InReplyTo에 의해 지정된 주석 사이의 관계("reply type")를 지정하는 문자열<br/>            그리고 InReplyTo에 의해 지정된 주석. |
| file | 이 주석과 연결된 파일의 사양입니다. |
| icon | 주석을 표시할 때 사용할 아이콘을 가져오거나 설정합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| clone() | 없음 |
| get_rectangle(consider_rotation) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |
| accept(visitor) | 주석을 처리하기 위해 방문자 객체를 받아들입니다. |
| flatten() | 주석 내용을 페이지에 직접 배치합니다,<br/>            주석 객체가 제거됩니다. |
| change_after_resize(transform) | 행렬 변환에 따라 매개변수와 외관을 업데이트합니다. |

### 또 보기

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

