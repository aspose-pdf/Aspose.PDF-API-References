---
title: "ListBoxField"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "ListBox 필드를 나타내는 클래스입니다."
type: docs
weight: 140
url: /ko/python-net/aspose.pdf.forms/listboxfield/
---

## ListBoxField class

ListBox 필드를 나타내는 클래스입니다.

ListBoxField 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| ListBoxField() | Generator에서 사용할 ListBoxField의 생성자입니다. |
| ListBoxField(page, rect) | ListBoxField 클래스의 새 인스턴스를 초기화합니다. |
| ListBoxField(doc, rect) | ListBoxField 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| vertical_alignment | 없음 |
| horizontal_alignment | 없음 |
| margin | 없음 |
| is_first_paragraph_in_column | 없음 |
| is_kept_with_next | 없음 |
| is_in_new_page | 없음 |
| is_in_line_paragraph | 없음 |
| hyperlink | 없음 |
| z_index | 없음 |
| update_appearance_on_convert | 없음 |
| use_font_subset | 없음 |
| flags | 없음 |
| annotation_type | 없음 |
| width | 없음 |
| actions | 없음 |
| 높이 | 없음 |
| 사각형 | 필드 사각형을 가져오거나 설정합니다. |
| 내용 | 없음 |
| 이름 | 없음 |
| 수정됨 | 없음 |
| 색상 | 없음 |
| 테두리 | 없음 |
| active_state | 없음 |
| 특징 | 없음 |
| 상태 | 없음 |
| 정렬 | 없음 |
| text_horizontal_alignment | 없음 |
| full_name | 없음 |
| 모양 | 없음 |
| page_index | 이 필드를 포함하는 페이지의 인덱스를 가져옵니다. |
| on_activated | 없음 |
| highlighting | 없음 |
| parent | 없음 |
| default_appearance | 없음 |
| read_only | 없음 |
| 필수 | 없음 |
| 내보낼 수 있음 | 없음 |
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
| commit_immediately | 선택 변경 시 커밋 플래그를 가져오거나 설정합니다. |
| multi_select | 다중 선택 플래그를 가져오거나 설정합니다. |
| 선택됨 | 선택된 항목의 인덱스를 가져오거나 설정합니다. 항목은 1부터 번호가 매겨집니다. |
| selected_items | 다중 선택 목록에서 선택된 항목들의 배열을 가져오거나 설정합니다. 단일 선택 목록의 경우 단일 항목이 포함된 배열을 반환합니다. |
| options | 선택 옵션 컬렉션을 가져옵니다. |
| top_index | 목록에서 가장 위에 보이는 요소의 인덱스를 가져오거나 설정합니다. |
## Indexer
| 이름 | 설명 |
| :- | :- |
| [index] | 인덱스로 이 필드에 포함된 하위 필드를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| add_option(option_name) | 지정된 이름으로 새 옵션을 추가합니다. |
| add_option(export, name) | 지정된 이름으로 새 옵션을 추가합니다. |
| clone() | 없음 |
| get_rectangle(consider_rotation) | 없음 |
| accept(visitor) | 없음 |
| flatten() | 이 필드를 제거하고 그 값을 페이지에 직접 배치합니다. |
| change_after_resize(transform) | 없음 |
| recalculate() | 폼의 모든 계산된 필드를 다시 계산합니다. |
| copy_to(array, index) | 지정된 인덱스부터 이 필드의 하위 필드들을 배열에 복사합니다. |
| set_position(point) | 필드의 위치를 설정합니다. |
| delete_option(option_name) | 옵션을 이름으로 삭제합니다. |

### 또 보기

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

