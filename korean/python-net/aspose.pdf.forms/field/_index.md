---
title: "필드"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "Acro 양식 필드의 기본 클래스입니다."
type: docs
weight: 90
url: /ko/python-net/aspose.pdf.forms/field/
---

## Field class

Acro 양식 필드의 기본 클래스입니다.

Field 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Field(doc) | Field 클래스의 새 인스턴스를 초기화합니다 |
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
| actions | 주석 작업을 가져옵니다. |
| 높이 | 주석의 높이를 가져오거나 설정합니다. |
| 사각형 | 필드 사각형을 가져오거나 설정합니다. |
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
| page_index | 이 필드를 포함하는 페이지의 인덱스를 가져옵니다. |
| on_activated | 주석이 활성화될 때 수행되는 작업입니다. |
| highlighting | 주석 강조 모드. |
| parent | 주석의 부모를 가져옵니다. |
| default_appearance | 필드의 기본 모양을 가져오거나 설정합니다. |
| read_only | 필드의 읽기 전용 상태를 가져오거나 설정합니다. |
| 필수 | 필드의 필수 상태를 가져오거나 설정합니다. |
| 내보낼 수 있음 | 필드의 내보낼 수 있음 플래그를 가져오거나 설정합니다. |
| partial_name | 필드의 부분 이름을 가져오거나 설정합니다. |
| alternate_name | 필드의 대체 이름을 가져오거나 설정합니다 (대체 필드 <br/>            실제 필드 이름 대신 사용되는 이름 <br/>            사용자 인터페이스에서 필드를 식별해야 하는 모든 곳).<br/>            대체 이름은 Adobe Acrobat에서 필드 툴팁으로 사용됩니다. |
| mapping_name | 문서에서 대화형 양식 필드 데이터를 내보낼 때 사용되는 필드의 매핑 이름을 가져오거나 설정합니다. |
| 값 | 필드의 값을 가져오거나 설정합니다. |
| is_synchronized | 사전이 동기화된 경우 true를 반환합니다. |
| sync_root | 동기화 객체. |
| is_group | 이 필드가 비단말 필드(즉, 필드 그룹)인지 여부를 나타내는 부울 값을 가져오거나 설정합니다. |
| annotation_index | 페이지에서 이 주석의 인덱스를 가져오거나 설정합니다. |
| is_shared_field | Generator 지원을 위한 속성입니다. 필드가 헤더 또는 푸터에 추가될 때 사용됩니다. true인 경우 이 필드는 한 번만 생성되며 문서의 모든 페이지에 동일한 외관이 표시됩니다. false인 경우 각 문서 페이지마다 별도의 필드가 생성됩니다. |
| fit_into_rectangle | true인 경우 텍스트가 지정된 사각형에 맞도록 글꼴 크기가 줄어듭니다. |
| max_font_size | 필드 내용에 사용할 수 있는 최대 글꼴 크기. -1이면 크기를 확인하지 않음. |
| min_font_size | 필드 내용에 사용할 수 있는 최소 글꼴 크기. -1이면 크기를 확인하지 않음. |
| tab_order | 필드의 탭 순서를 가져오거나 설정합니다. |
## Indexer
| 이름 | 설명 |
| :- | :- |
| [index] | 인덱스로 이 필드에 포함된 하위 필드를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| clone() | 없음 |
| get_rectangle(consider_rotation) | 페이지 회전을 고려하여 주석의 사각형을 반환합니다. |
| accept(visitor) | 방문자를 수락합니다. |
| flatten() | 이 필드를 제거하고 그 값을 페이지에 직접 배치합니다. |
| change_after_resize(transform) | 행렬 변환에 따라 매개변수와 외관을 업데이트합니다. |
| recalculate() | 폼의 모든 계산된 필드를 다시 계산합니다. |
| copy_to(array, index) | 지정된 인덱스부터 이 필드의 하위 필드들을 배열에 복사합니다. |
| set_position(point) | 필드의 위치를 설정합니다. |

### 또 보기

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

