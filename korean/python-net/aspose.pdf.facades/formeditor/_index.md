---
title: "FormEditor"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "폼을 편집하는 클래스(필드 추가/삭제 등)."
type: docs
weight: 110
url: /ko/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

폼을 편집하는 클래스(필드 추가/삭제 등).

FormEditor 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| FormEditor(src_stream, dest_stream) | FormEditor 클래스의 새 인스턴스를 초기화합니다 |
| FormEditor(src_file_name, dest_file_name) | FormEditor 클래스의 새 인스턴스를 초기화합니다 |
| FormEditor() | FormEditor의 생성자입니다. |
| FormEditor(document) | FormEditor 클래스의 새 인스턴스를 초기화합니다 |
| FormEditor(document, dest_file_name) | FormEditor 클래스의 새 인스턴스를 초기화합니다 |
| FormEditor(document, dest_stream) | FormEditor 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| src_file_name | 소스 파일의 이름을 가져오거나 설정합니다. |
| dest_file_name | 대상 파일 이름을 가져오거나 설정합니다. |
| src_stream | 소스 스트림을 가져오거나 설정합니다. |
| dest_stream | 대상 스트림을 가져오거나 설정합니다. |
| items | 새로 생성된 리스트 박스 또는 콤보 박스에 추가될 항목을 설정합니다. |
| export_items | 내보내기 값을 가진 콤보 박스 옵션을 설정합니다. |
| facade | 필드의 시각적 속성을 설정합니다. |
| radio_gap | 두 인접 라디오 버튼 사이의 간격을 픽셀 단위로 기록하는 멤버이며, 기본값은 50입니다. |
| radio_horiz | 라디오 버튼이 가로로 배열되는지 세로로 배열되는지를 나타내는 플래그이며, 기본값은 true입니다. |
| radio_button_item_size | 새 라디오 버튼 필드가 추가될 때 라디오 버튼 항목 크기를 가져오거나 설정합니다. |
| submit_flag | 제출 버튼의 제출 플래그를 설정합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_stream) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save() | 변경 사항을 대상 파일에 저장합니다. |
| save(dest_file) | 변경 사항을 대상 파일에 저장합니다. |
| save(dest_stream) | 변경 사항을 대상 파일에 저장합니다. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | 지정된 유형의 필드를 양식에 추가합니다. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | 지정된 유형의 필드를 양식에 추가합니다. |
| copy_inner_field(field_name, new_field_name, page_num) | 기존 필드를 지정된 페이지 번호의 동일한 위치에 복사합니다.<br/> 새 문서가 생성되며, 이 문서는 원본 문서의 모든 내용을 포함하지만 새로 복사된 필드만 제외됩니다. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | 기존 필드를 페이지 번호와 좌표 모두로 지정된 새로운 위치에 복사합니다.<br/> 새 문서가 생성되며, 이 문서는 원본 문서의 모든 내용을 포함하지만 새로 복사된 필드만 제외됩니다. |
| copy_outer_field(src_file_name, field_name) | 기존 필드를 한 PDF 문서에서 원본 페이지 번호와 좌표를 유지한 채 다른 문서로 복사합니다.<br/> 참고: AcroForm 필드에만 적용됩니다(라디오 박스 제외). |
| copy_outer_field(src_file_name, field_name, page_num) | 기존 필드를 한 PDF 문서에서 지정된 페이지 번호와 원본 좌표를 유지한 채 다른 문서로 복사합니다.<br/> 참고: AcroForm 필드에만 적용됩니다(라디오 박스 제외). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | 기존 필드를 한 PDF 문서에서 지정된 페이지 번호와 좌표를 사용하여 다른 문서로 복사합니다.<br/> 참고: AcroForm 필드에만 적용됩니다(라디오 박스 제외). |
| decorate_field(field_name) | 지정된 필드의 시각적 속성을 변경합니다. |
| decorate_field(field_type) | 지정된 필드 유형을 가진 모든 필드의 시각적 속성을 변경합니다. |
| decorate_field() | 지정된 필드의 시각적 속성을 변경합니다. |
| add_list_item(field_name, item_name) | 목록 상자에 새 항목을 추가합니다. |
| add_list_item(field_name, export_name) | Export 값을 가진 새 항목을 기존 목록 상자 필드에 추가합니다. 이는 AcroForm 콤보 박스 필드에만 적용됩니다. |
| close() | Facade를 닫습니다. |
| set_field_attribute(field_name, flag) | 필드의 속성을 설정합니다. |
| set_field_appearance(field_name, flags) | 필드 플래그를 설정합니다 |
| get_field_appearance(field_name) | 필드 플래그를 가져옵니다. |
| set_submit_flag(field_name, submit_form_flag) | 제출 버튼의 제출 플래그를 설정합니다. |
| set_submit_url(field_name, url) | 버튼의 URL을 설정합니다. |
| set_field_limit(field_name, field_limit) | 텍스트 필드의 최대 문자 수를 설정합니다. |
| set_field_comb_number(field_name, comb_number) | 일반 단일 라인 텍스트 필드의 콤 수를 설정합니다 (필드는 <br/>            combNumber 매개변수 값만큼 동일하게 간격을 둔 위치, 즉 콤으로 자동으로 나뉩니다. <br/>            ). |
| move_field(field_name, llx, lly, urx, ury) | 필드의 새 위치를 설정합니다. |
| remove_field(field_name) | 폼에서 필드를 제거합니다. |
| reset_facade() | 모든 시각적 속성을 빈 값으로 재설정합니다. |
| reset_inner_facade() | 내부 파사드의 모든 시각적 속성을 빈 값으로 재설정합니다. |
| rename_field(field_name, new_field_name) | 필드의 이름을 변경합니다. |
| remove_field_action(field_name) | 필드의 제출 동작을 제거합니다. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | 양식에 제출 버튼을 추가합니다. |
| del_list_item(field_name, item_name) | 목록 필드에서 항목을 삭제합니다. |
| set_field_script(field_name, script) | PushButton 필드에 대한 JavaScript를 설정합니다. 기존 JavaScript가 존재하면 새 것으로 교체됩니다. |
| add_field_script(field_name, script) | PushButton 필드에 JavaScript를 추가합니다. 기존 이벤트가 존재하면 새 이벤트가 그 뒤에 추가됩니다. |
| single_2_multiple(field_name) | 단일 라인 텍스트 필드를 다중 라인 필드로 변경합니다. |
| set_field_alignment(field_name, alignment) | 텍스트 필드의 정렬 스타일을 설정합니다. |
| set_field_alignment_v(field_name, alignment) | 텍스트 필드의 수직 정렬 스타일을 설정합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

