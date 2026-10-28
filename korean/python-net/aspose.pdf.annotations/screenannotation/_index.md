---
title: "ScreenAnnotation"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "미디어 클립을 재생할 수 있는 페이지 영역을 지정하는 화면 주석입니다."
type: docs
weight: 720
url: /ko/python-net/aspose.pdf.annotations/screenannotation/
---

## ScreenAnnotation class

미디어 클립을 재생할 수 있는 페이지 영역을 지정하는 화면 주석입니다.

ScreenAnnotation 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| ScreenAnnotation(page, rect, media_file) | ScreenAnnotation 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| vertical_alignment | 단락의 수직 정렬을 가져오거나 설정합니다 |
| horizontal_alignment | 주석에 대한 텍스트 정렬을 가져오거나 설정합니다. |
| margin | 단락의 외부 여백을 가져오거나 설정합니다 (PDF 생성용) |
| is_first_paragraph_in_column | 다음 열에 이 단락이 배치될지 여부를 나타내는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_kept_with_next | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지 여부를 나타내는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_in_new_page | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_in_line_paragraph | 단락이 인라인인지 여부를 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| hyperlink | 프래그먼트 하이퍼링크를 가져오거나 설정합니다 (PDF 생성기용). |
| z_index | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 <br/>            ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. 음수 ZIndex를 가진 그래프는 <br/>            페이지의 텍스트 뒤에 배치됩니다. |
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
| 제목 | 스크린 주석의 제목을 가져오거나 설정합니다. |
| action | 주석이 활성화될 때 수행될 작업을 가져오거나 설정합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| clone() | 이 인스턴스를 복제합니다.<br/>            가상 메서드. 항상 null을 반환합니다. |
| get_rectangle(consider_rotation) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |
| accept(visitor) | 주석을 처리하기 위해 방문자 객체를 수락합니다. |
| flatten() | 주석 내용을 페이지에 직접 배치합니다,<br/>            주석 객체가 제거됩니다. |
| change_after_resize(transform) | 행렬 변환에 따라 매개변수와 외관을 업데이트합니다. |

### 또 보기

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

