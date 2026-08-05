---
title: "Form"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "양식 객체를 나타내는 클래스입니다."
type: docs
weight: 110
url: /ko/python-net/aspose.pdf.forms/form/
---

## Form class

양식 객체를 나타내는 클래스입니다.

Form 유형은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| is_synchronized | 객체가 스레드 안전하면 true를 반환합니다. |
| sync_root | 동기화 객체를 반환합니다. |
| auto_recalculate | 설정하면 필드가 변경될 때 모든 양식 필드가 다시 계산됩니다. 기본값은 true입니다. 계산된 필드가 많은 양식을 채울 때 성능을 향상시키려면 false로 설정하십시오. |
| auto_restore_form | 설정하면 주석에 존재하는 경우 누락된 양식 필드가 자동으로 생성됩니다. |
| default_resources | 이 양식에 배치된 기본 리소스를 가져옵니다. |
| default_appearance | 양식의 기본 외관을 가져오거나 설정합니다(양식 필드의 기본 글꼴, 텍스트 크기 및 색상을 설명하는 객체). |
| xfa | 양식의 XFA 데이터를 가져옵니다(존재하는 경우). |
| ignore_needs_rendering | 이 속성이 true이면 XFA 양식을 표준 양식으로 변환하는 동안 NeedsRendering 키의 값이 무시됩니다.<br/>            기본값은 false입니다. |
| remove_permission | 이 속성이 true이면 동적 문서를 표준으로 변환한 후 PDF 문서에서 "Perms" 사전이 제거됩니다.<br/>            "Perms" 사전에는 Adobe Acrobat Reader에서 필수 필드 선택 표시를 방해하는 규칙이 포함될 수 있습니다.<br/>            기본값은 false입니다. |
| emulate_requierd_groups | 이 속성이 true이면 필수 Xfa exclGroup 요소 컨테이너에 추가 빨간 경계 사각형이 그려집니다.<br/>            이 속성은 Xfa 형태를 표준으로 변환할 때 exclGroup에 대한 유사 항목이 없어서 도입되었습니다.<br/>            기본값은 false입니다. |
| type | 폼의 유형을 가져옵니다. 가능한 값은: Standard, Static, Dynamic. |
| 필드 | 계층형 폼의 최하위 수준에 있는 모든 필드 목록을 가져옵니다. |
| signatures_exist | 설정된 경우, 문서에 최소 하나의 서명 필드가 포함됩니다. |
| signatures_append_only | 설정된 경우, 파일이 이전 내용을 변경하는 방식으로 저장(쓰기)될 때 무효화될 수 있는 서명이 문서에 포함됩니다, <br/>            증분 업데이트와는 반대로. |
| sign_dependent_elements_rendering_mode_when_converted | 폼은 서명 정보를 포함할 수 있으며, 서명되었거나 서명되지 않을 수 있습니다.<br/>              또한 폼의 뷰는 때때로 폼이 서명되었는지 여부에 따라 달라져야 합니다.<br/>              이 속성은 폼 변환기(예: XFA 폼을 Standard 폼으로 변환하는 동안)에게 결과 폼을 서명된 형태로 렌더링할지 서명되지 않은 형태로 렌더링할지 알려줍니다.<br/>               |
## Indexer
| 이름 | 설명 |
| :- | :- |
| [index] | 필드 인덱스로 폼의 필드를 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| delete(field) | 폼에서 필드를 삭제합니다. |
| delete(field_name) | 이름으로 폼에서 필드를 삭제합니다. |
| add(field, page_number) | 폼에 필드를 추가합니다. |
| add(field) | 폼에 필드를 추가합니다. |
| add(field, partial_name, page_number) | 폼에 새 필드를 추가합니다; 이 필드가 이미 다른 폼이나 현재 폼에 배치된 경우, 필드의 복사본이 생성됩니다. |
| has_field(field) | 폼에 지정된 필드가 이미 있는지 확인합니다. |
| has_field(field_name) | 지정된 이름을 가진 필드가 이미 폼에 추가되었는지 판단합니다. |
| copy_to(array, index) | 폼에 배치된 필드를 배열에 복사합니다. |
| flatten() | 모든 폼 필드를 제거하고 해당 값을 페이지에 직접 배치합니다. |
| add_field_appearance(field, page_number, rect) | 지정된 위치의 문서 지정 페이지에 필드의 추가 외관을 추가합니다. |
| get_fields_in_rect(rect) | 지정된 사각형 내부의 필드를 반환합니다. |

### 또 보기

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

