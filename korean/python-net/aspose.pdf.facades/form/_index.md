---
title: "Form"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "Acro 양식 객체를 나타내는 클래스."
type: docs
weight: 80
url: /ko/python-net/aspose.pdf.facades/form/
---

## Form class

Acro 양식 객체를 나타내는 클래스.

Form 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Form(src_stream, dest_stream) | Form 클래스의 새 인스턴스를 초기화합니다. |
| Form() | 매개변수 없이 Form의 생성자입니다. |
| Form(src_file_name) | Form 클래스의 새 인스턴스를 초기화합니다. |
| Form(src_stream) | Form 클래스의 새 인스턴스를 초기화합니다. |
| Form(src_file_name, dest_file_name) | Form 클래스의 새 인스턴스를 초기화합니다. |
| Form(src_file_name, dest_stream) | Form 클래스의 새 인스턴스를 초기화합니다. |
| Form(src_stream, dest_file_name) | Form 클래스의 새 인스턴스를 초기화합니다. |
| Form(document) | Form 클래스의 새 인스턴스를 초기화합니다. |
| Form(document, dest_file_name) | Form 클래스의 새 인스턴스를 초기화합니다. |
| Form(document, dest_stream) | Form 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| import_result | 마지막 가져오기 작업의 결과입니다. 각 필드에 대한 가져오기 결과를 설명하는 객체 배열입니다. |
| src_file_name | 소스 파일 이름을 가져오거나 설정합니다. |
| dest_file_name | 대상 파일 이름을 가져오거나 설정합니다. |
| src_stream | 소스 스트림을 가져오거나 설정합니다. |
| dest_stream | 대상 스트림을 가져오거나 설정합니다. |
| field_names | 양식에 있는 필드 이름 목록을 가져옵니다. |
| form_submit_button_names | 모든 양식 제출 버튼 이름을 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_stream) | PDF 문서를 편집용으로 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save() | 채워진 필드 값을 저장하고 열린 PDF 문서를 닫습니다. |
| save(dest_file) | 지정된 파일에 문서를 저장합니다. |
| save(dest_stream) | 지정된 스트림에 문서를 저장합니다. |
| fill_field(field_name, field_value) | 전체 지정된 필드 이름에 따라 필드에 유효한 값을 채웁니다.<br/>            필드를 채우기 전에 모든 필드 이름과 해당 유효한 값을 알아야 합니다.<br/>            필드 이름과 값은 모두 대소문자를 구분합니다.<br/>            Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다.<br/>            예를 들어 필드의 전체 이름이 "Form.Subform.TextField"인 경우 전체 이름을 지정해야 하며 "TextField"만 지정해서는 안 됩니다. <br/>            기존 필드 이름을 탐색하고 필요한 필드를 부분 이름으로 검색하려면 FieldNames 속성을 사용할 수 있습니다. |
| fill_field(field_name, index) | 전체 지정된 필드 이름에 따라 라디오 박스 필드에 유효한 인덱스 값을 채웁니다.<br/>            필드를 채우기 전에 필드 이름만 알면 됩니다. 값은 인덱스로 지정할 수 있습니다.<br/>            참고: 라디오 박스, 콤보 박스 및 리스트 박스 필드에만 적용됩니다.<br/>            Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다.<br/>            예를 들어 필드의 전체 이름이 "Form.Subform.ListBoxField"인 경우 전체 이름을 지정해야 하며 "ListBoxField"만 지정해서는 안 됩니다. <br/>            기존 필드 이름을 탐색하고 필요한 필드를 부분 이름으로 검색하려면 FieldNames 속성을 사용할 수 있습니다. |
| fill_field(field_name, be_checked) | 체크 박스 필드에 불리언 값을 채웁니다.<br/>            참고: 체크 박스에만 적용됩니다.<br/>            Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다.<br/>            예를 들어 필드의 전체 이름이 "Form.Subform.CheckBoxField"인 경우 전체 이름을 지정해야 하며 "CheckBoxField"만 지정해서는 안 됩니다. <br/>            기존 필드 이름을 탐색하고 필요한 필드를 부분 이름으로 검색하려면 FieldNames 속성을 사용할 수 있습니다. |
| fill_field(field_name, field_values) | 텍스트 박스 필드에 텍스트 값을 채우고 문서를 저장합니다.<br/>            서명된 문서에 적용됩니다.<br/>            참고: 텍스트 박스에만 적용됩니다.<br/>            필드 이름과 값은 모두 대소문자를 구분합니다. |
| fill_field(field_name, value, fit_font_size) | 체크 박스 필드에 불리언 값을 채웁니다.<br/>            참고: 체크 박스에만 적용됩니다.<br/>            Aspose.Pdf.Facades는 전체 필드 이름만 지원하며 Aspose.Pdf.Kit과 달리 부분 필드 이름은 작동하지 않습니다.<br/>            예를 들어 필드의 전체 이름이 "Form.Subform.CheckBoxField"인 경우 전체 이름을 지정해야 하며 "CheckBoxField"만 지정해서는 안 됩니다. <br/>            기존 필드 이름을 탐색하고 필요한 필드를 부분 이름으로 검색하려면 FieldNames 속성을 사용할 수 있습니다. |
| import_xml(input_xml_stream) | XML 파일에서 필드 내용을 가져와 새 PDF에 삽입합니다. |
| import_xml(input_xml_stream, ignore_form_template_changes) | XML 파일에서 필드 내용을 가져와 새 PDF에 삽입합니다. |
| fill_image_field(field_name, image_file_name) | 기존 버튼 필드에 이미지를 붙여 해당 외관으로 사용합니다. <br/>            전체 지정된 필드 이름에 따라. |
| fill_image_field(field_name, image_stream) | FillImageField 함수의 오버로드 버전입니다.<br/>            입력은 이미지 스트림입니다. |
| close() | 열린 파일을 변경 없이 닫습니다. |
| get_field_facade(field_name) | 모든 외관 속성을 포함하는 FrofmFieldFacade 객체를 반환합니다. |
| fill_fields(field_names, field_values, output) | 텍스트 박스 필드에 텍스트 값을 채우고 문서를 저장합니다.<br/>            서명된 문서에 적용됩니다.<br/>            참고: 텍스트 박스에만 적용됩니다.<br/>            필드 이름과 값은 모두 대소문자를 구분합니다. |
| get_button_option_current_value(field_name) | 라디오 버튼 옵션 필드의 현재 값을 반환합니다. |
| get_field(field_name) | 모든 외관 속성을 포함하는 FrofmFieldFacade 객체를 반환합니다. |
| get_full_field_name(field_name) | 짧은 필드 이름에 따라 전체 필드 이름을 가져옵니다. |
| get_field_limit(field_name) | 텍스트 필드의 제한을 가져옵니다. |
| flatten_all_fields() | 모든 필드를 평탄화합니다. |
| flatten_field(field_name) | 전체 지정된 필드 이름을 사용하여 지정된 필드를 평탄화합니다.<br/>            다른 모든 필드는 변경되지 않은 상태로 유지됩니다. fieldName이 유효하지 않은 경우,<br/>            모든 필드는 변경되지 않은 상태로 유지됩니다. |
| fill_barcode_field(field_name, data) | 전체 지정된 필드 이름에 따라 바코드 필드를 채웁니다. |
| import_fdf(input_fdf_stream) | fdf 파일에서 필드 내용을 가져와 새 PDF에 삽입합니다. |
| export_fdf(output_fdf_stream) | PDF의 필드 내용을 fdf 스트림으로 내보냅니다. |
| export_xml(output_xml_stream) | PDF의 필드 내용을 XML 스트림으로 내보냅니다.<br/>            버튼 필드의 값은 내보내지 않습니다. |
| extract_xfa_data(output_xml_stream) | XFA 데이터 패킷을 추출합니다. |
| set_xfa_data(input_xml_stream) | 지정된 데이터 패킷으로 XFA 데이터를 교체합니다. 데이터 패킷은 ExtractXfaData를 사용하여 추출할 수 있습니다. |
| import_xfdf(input_xfdf_stream) | xfdf(xml) 파일에서 필드 내용을 가져와 새 PDF에 삽입합니다. |
| export_xfdf(output_xfdf_stream) | PDF의 필드 내용을 XML 스트림으로 내보냅니다.<br/>            버튼 필드의 값은 내보내지 않습니다. |
| rename_field(field_name, new_field_name) | 필드의 이름을 변경합니다. AcroForm 필드든 XFA 필드든 모두 가능합니다. |
| get_rich_text(field_name) | 리치 텍스트 필드의 값을 가져오고, 각 문자마다의 포맷팅 정보를 포함합니다. |
| get_submit_flags(field_name) | 제출 버튼의 제출 플래그를 반환합니다. |
| get_field_type(field_name) | 필드의 유형을 반환합니다. |
| is_required_field(field_name) | 필드가 필수인지 여부를 결정합니다. |
| get_field_flag(field_name) | 필드의 플래그를 반환합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

