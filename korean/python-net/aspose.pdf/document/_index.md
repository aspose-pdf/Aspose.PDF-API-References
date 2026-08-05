---
title: "Document"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 문서를 나타내는 클래스"
type: docs
weight: 230
url: /ko/python-net/aspose.pdf/document/
---

## Document class

PDF 문서를 나타내는 클래스

Document 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| Document(input) | Document 클래스의 새 인스턴스를 초기화합니다 |
| Document(input, password, is_managed_stream) | Document 클래스의 새 인스턴스를 초기화합니다 |
| Document(input, is_managed_stream) | Document 클래스의 새 인스턴스를 초기화합니다 |
| Document(filename) | Document 클래스의 새 인스턴스를 초기화합니다 |
| Document(input, password) | Document 클래스의 새 인스턴스를 초기화합니다 |
| Document() | 빈 문서를 초기화합니다. |
| Document(filename, options) | Document 클래스의 새 인스턴스를 초기화합니다 |
| Document(input, options) | Document 클래스의 새 인스턴스를 초기화합니다 |
| Document(filename, password) | Document 클래스의 새 인스턴스를 초기화합니다 |
| Document(filename, password, is_managed_stream) | Document 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| java_script | 문서 수준의 JavaScript 컬렉션입니다. |
| is_licensed | 시스템의 라이선스 상태를 가져옵니다. 시스템이 라이선스 모드에서 작동하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| page_info | 페이지 정보를 가져오거나 설정합니다.(생성기 전용이며, 문서를 읽을 때는 채워지지 않습니다) |
| enable_signature_sanitization | 서명 필드 정화를 관리하는 플래그를 가져오거나 설정합니다. 기본적으로 활성화됩니다. |
| is_pdfa_compliant | 문서가 PDF/A 준수인지 가져옵니다. |
| is_pdf_ua_compliant | 문서가 PDF/UA 준수인지 가져옵니다. |
| is_xref_gaps_allowed | 문서가 PDF/A 준수인지 가져오거나 설정합니다. |
| named_destinations | 문서에 있는 명명된 목적지의 컬렉션입니다. |
| 목적지 | 목적지 컬렉션을 가져옵니다.<br/>            사용되지 않음. NamedDestinations를 사용하십시오. |
| pdf_format | PDF 형식을 가져옵니다 |
| embed_standard_fonts | 문서가 모든 표준 Type1 글꼴을 포함해야 함을 선언하는 속성 <br/>            여기서 IsEmbedded 플래그가 true로 설정됩니다. 모든 PDF 글꼴은 <br/>            IsEmbedded 플래그를 true로 설정하면 문서에 쉽게 포함될 수 있지만, PDF 표준 Type1 글꼴은 이 규칙에서 예외입니다.<br/>            표준 Type1 글꼴 포함에는 많은 시간이 소요되므로, 이러한 글꼴을 포함하려면<br/>            지정된 글꼴에 대해 IsEmbedded 플래그를 true로 설정할 뿐만 아니라 <br/>            문서 수준에서 추가 플래그인 EmbedStandardFonts = true를 설정해야 합니다;<br/>            이 속성은 모든 글꼴에 대해 한 번만 설정할 수 있습니다.<br/>            기본값은 false입니다. |
| disable_font_license_verifications | 글꼴에 대한 많은 작업은 해당 글꼴의 라이선스가 이러한 작업을 금지하는 경우 실행할 수 없습니다.<br/>            예를 들어, 라이선스 규정이 해당 글꼴의 포함을 금지하는 경우 일부 글꼴은 PDF 문서에 포함될 수 없습니다.<br/>            이 플래그는 현재 PDF 문서의 모든 글꼴에 대한 라이선스 제한을 해제하는 데 사용됩니다.<br/>            이 플래그를 사용할 때는 주의하십시오. 플래그가 설정되면 해당 플래그를 설정한 사람이<br/>            가능한 라이선스/법 위반에 대한 모든 책임을 스스로 짊어지게 됩니다.<br/>            따라서 이는 자신의 위험 부담 하에 이루어집니다.<br/>            저작권법을 위반하지 않는다는 확신이 완전히 있을 때만 이 플래그를 사용하는 것이 강력히 권장됩니다.<br/>            기본값은 false입니다. |
| font_utilities | IDocumentFontUtilities 인스턴스 |
| 컬렉션 | 문서의 컬렉션을 가져옵니다. |
| version | PDF 파일 헤더에서 PDF 버전을 가져옵니다. |
| open_action | 문서가 열릴 때 수행되는 작업을 가져오거나 설정합니다. |
| hide_tool_bar | 문서가 활성화될 때 툴바를 숨길지 여부를 지정하는 플래그를 가져오거나 설정합니다. |
| hide_menubar | 문서가 활성화될 때 메뉴 바를 숨길지 여부를 지정하는 플래그를 가져오거나 설정합니다. |
| hide_window_ui | 문서가 활성화될 때 사용자 인터페이스 요소를 숨길지 여부를 지정하는 플래그를 가져오거나 설정합니다. |
| fit_window | 문서 창을 첫 번째 표시 페이지에 맞게 크기를 조정해야 하는지 여부를 지정하는 플래그를 가져오거나 설정합니다. |
| center_window | 문서 창의 위치가 화면 중앙에 배치되는지 여부를 지정하는 플래그를 가져오거나 설정합니다. |
| display_doc_title | 문서 창 제목 표시줄에 문서 제목을 표시할지 여부를 지정하는 플래그를 가져오거나 설정합니다. |
| pages | 문서 페이지 컬렉션을 가져오거나 설정합니다.<br/>            컬렉션의 페이지 번호는 1부터 시작한다는 점에 유의하십시오. |
| outlines | 문서 개요를 가져옵니다. |
| actions | 문서 작업을 가져옵니다. 이 속성은 DocumentActions 클래스의 인스턴스로, BeforClosing, BeforSaving 등 작업을 가져오거나 설정할 수 있게 합니다. |
| form | 문서의 Acro Form을 가져옵니다. |
| embedded_files | 문서에 삽입된 파일 컬렉션을 가져옵니다. |
| direction | 텍스트의 읽기 순서를 가져오거나 설정합니다: L2R(왼쪽에서 오른쪽) 또는 R2L(오른쪽에서 왼쪽). |
| page_mode | 문서가 열릴 때 표시되는 방식을 지정하는 페이지 모드를 가져오거나 설정합니다. |
| non_full_screen_page_mode | 전체 화면 모드에서 나올 때 문서를 표시하는 방식을 지정하는 페이지 모드를 가져오거나 설정합니다. |
| page_layout | 문서가 열릴 때 사용될 페이지 레이아웃을 가져오거나 설정합니다. |
| duplex | 인쇄 대화 상자에서 파일을 인쇄할 때 사용할 양면 인쇄 모드 처리 옵션을 가져오거나 설정합니다. |
| file_name | 이 문서를 생성한 PDF 파일의 이름 |
| info | 문서 정보를 가져옵니다. |
| 메타데이터 | 문서 메타데이터.<br/>            (PDF 문서는 일반 정보(예: 문서 제목, 저자, 생성 및 수정 날짜)를 포함할 수 있습니다.<br/>             이러한 전역 정보는 문서의 내용이나 구조와는 별도로 메타데이터라고 하며,<br/>             외부 데이터베이스에서 문서를 카탈로그화하고 검색하는 데 도움이 되도록 설계되었습니다.) |
| logical_structure | 문서의 논리 구조를 가져옵니다. |
| handle_signature_change | 문서가 변경된 상태로 저장되고 서명이 있는 경우 예외를 발생시킵니다. |
| crypto_algorithm | 문서가 암호화된 경우 보안 설정을 가져옵니다. <br/>            문서가 암호화되지 않은 경우 .net 1.1에서는 해당 예외가 발생하고,<br/>            다른 .net 버전에서는 CryptoAlgorithm이 null이 됩니다. |
| is_linearized | 문서가 선형화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| permissions | 문서의 권한을 가져옵니다. |
| is_encrypted | 문서의 암호화 상태를 가져옵니다. 문서가 암호화된 경우 true입니다. |
| id | ID를 가져옵니다. |
| background | 문서의 배경 색상을 가져오거나 설정합니다. |
| optimize_size | 최적화 플래그를 가져오거나 설정합니다. 문서에 페이지를 추가할 때, 결과 파일의 동일한 리소스 스트림이<br/>            이 플래그가 설정되어 있으면 하나의 PDF 객체로 병합됩니다. <br/>            이를 통해 결과 파일 크기를 줄일 수 있지만 실행 속도가 느려지고 메모리 요구량이 증가할 수 있습니다.<br/>            기본값: false. |
| allow_reuse_page_content | 페이지 내용을 병합하여 문서 크기를 최적화할 수 있습니다. 이 옵션을 사용하면 서로 다른 복제 페이지가 동일한 콘텐츠 객체를 참조할 수 있습니다. <br/>            이 모드는 다른 페이지가 변경될 때 페이지 내용이 변경되는 등 부작용을 일으킬 수 있다는 점에 유의하세요. |
| ignore_corrupted_objects | 소스 파일의 오류를 무시하는 플래그를 가져오거나 설정합니다. <br/>            소스 문서의 페이지를 대상 문서로 복사할 때, 이 플래그가 false이면 소스 파일의 일부 객체가 손상된 경우 예외가 발생하여 복사 과정이 중단됩니다. <br/>            예시: dest.Pages.Add(src.Pages);<br/>            이 플래그를 true로 설정하면 손상된 객체가 빈 값으로 대체됩니다.<br/>            기본값: true. |
| page_labels | 문서의 페이지 레이블을 가져옵니다. |
| enable_object_unload | 문서를 메모리에서 부분적으로 언로드하도록 허용하는 플래그를 가져오거나 설정합니다. <br/>            이를 통해 메모리 사용량을 줄일 수 있지만 성능에 부정적인 영향을 미칠 수 있습니다. |
| tagged_content | TaggedPdf 콘텐츠에 대한 접근을 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| save(output) | 문서를 스트림에 저장합니다. |
| save(output_file_name) | 지정된 파일에 문서를 저장합니다. |
| save() | 문서를 스트림에 저장합니다. |
| save(options) | 저장 옵션으로 문서를 저장합니다. |
| save(output_file_name, format) | 새 이름과 파일 형식으로 문서를 저장합니다. |
| save(output_stream, format) | 새 이름과 파일 형식으로 문서를 저장합니다. |
| save(output_file_name, options) | 새 이름으로 저장 옵션을 설정하여 문서를 저장합니다. |
| save(output_stream, options) | 저장 옵션을 사용하여 문서를 스트림에 저장합니다. |
| export_annotations_to_xfdf(file_name) | 모든 문서 주석을 XFDF 파일로 내보냅니다. |
| export_annotations_to_xfdf(stream) | 모든 문서 주석을 스트림으로 내보냅니다. |
| send_to(device, output) | 전체 문서를 처리하기 위해 문서 장치로 보냅니다. |
| send_to(device, from_page, to_page, output) | 문서의 특정 페이지를 처리하기 위해 문서 장치로 보냅니다. |
| send_to(device, output_file_name) | 전체 문서를 처리하기 위해 문서 장치로 보냅니다. |
| send_to(device, from_page, to_page, output_file_name) | 전체 문서를 처리하기 위해 문서 장치로 보냅니다. |
| import_annotations_from_xfdf(file_name) | XFDF 파일에서 문서로 주석을 가져옵니다. |
| import_annotations_from_xfdf(stream) | 스트림에서 문서로 주석을 가져옵니다. |
| validate(output_log_file_name, format) | 문서를 지정된 파일에 검증합니다. |
| validate(output_log_stream, format) | 문서를 지정된 파일에 검증합니다. |
| validate(options) | 문서를 지정된 파일에 검증합니다. |
| convert(output_log_file_name, format, action, transparency_action) | 문서를 변환하고 오류를 지정된 파일에 저장합니다. |
| convert(output_log_stream, format, action, transparency_action) | 문서를 변환하고 오류를 지정된 파일에 저장합니다. |
| convert(output_log_file_name, format, action) | 문서를 변환하고 오류를 지정된 파일에 저장합니다. |
| convert(options) | 지정된 변환 옵션을 사용하여 문서를 변환합니다 |
| convert(output_log_stream, format, action) | 문서를 변환하고 오류를 지정된 파일에 저장합니다. |
| convert(fixup, output_log, only_validation, parameters) | Fixup을 적용하여 문서를 변환합니다. |
| convert(fixup, output_log, only_validation, parameters) | Fixup을 적용하여 문서를 변환합니다. |
| convert(src_file_name, load_options, dst_file_name, save_options) | 소스 형식의 소스 파일을 대상 형식의 대상 파일로 변환합니다. |
| convert(src_stream, load_options, dst_file_name, save_options) | 소스 형식의 스트림을 대상 형식의 대상 파일로 변환합니다. |
| convert(src_file_name, load_options, dst_stream, save_options) | 소스 형식의 스트림을 대상 형식의 대상 파일로 변환합니다. |
| convert(src_stream, load_options, dst_stream, save_options) | 소스 형식의 스트림을 대상 형식의 대상 파일로 변환합니다. |
| flatten() | 문서에서 모든 필드를 제거하고 대신 해당 값을 배치합니다. |
| flatten(flatten_settings) | 문서에서 모든 필드를 제거하고 대신 해당 값을 배치합니다. |
| encrypt(user_password, owner_password, privileges, crypto_algorithm, use_pdf20) | 문서를 암호화합니다. 그런 다음 Save를 호출하여 암호화된 문서 버전을 얻으세요. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm) | 문서를 암호화합니다. 그런 다음 Save를 호출하여 암호화된 문서 버전을 얻으세요. |
| encrypt(user_password, owner_password, permissions, crypto_algorithm, use_pdf20) | 문서를 암호화합니다. 그런 다음 Save를 호출하여 암호화된 문서 버전을 얻으세요. |
| optimize_resources() | 문서에서 리소스를 최적화합니다:<br/>            1. 문서 페이지에서 사용되지 않는 리소스가 제거됩니다;<br/>            2. 동일한 리소스가 하나의 객체로 병합됩니다; <br/>            3. 사용되지 않는 객체가 삭제됩니다. |
| optimize_resources(strategy) | 정의된 최적화 전략에 따라 문서의 리소스를 최적화합니다. |
| bind_xml(file) | xml을 문서에 바인드합니다 |
| bind_xml(xml_file, xsl_file) | xml을 문서에 바인드합니다 |
| bind_xml(xml_stream, xsl_stream) | xml/xsl을 문서에 바인드합니다 |
| bind_xml(stream) | xml/xsl을 문서에 바인드합니다 |
| remove_pdfa_compliance() | 문서에서 pdfa 준수를 제거합니다 |
| remove_pdf_ua_compliance() | 문서에서 pdfUa 준수를 제거합니다 |
| set_title(title) | Pdf 문서의 제목을 설정합니다 |
| process_paragraphs() | 생성기를 위한 단락을 처리합니다. |
| remove_metadata() | 문서에서 메타데이터를 제거합니다. |
| change_passwords(owner_password, new_user_password, new_owner_password) | 문서 비밀번호를 변경합니다. 이 작업은 소유자 비밀번호를 사용해야만 수행할 수 있습니다. |
| decrypt() | 문서를 복호화합니다. 그런 다음 저장을 호출하여 복호화된 문서 버전을 얻으세요. |
| optimize() | Linearize document in order to<br/>            - 첫 페이지를 가능한 빨리 열 수 있도록;<br/>            - 다음 페이지를 표시하거나 다음 페이지로 연결되는 링크를 가능한 빨리 따라갈 수 있도록;<br/>            - 페이지 데이터가 느린 채널을 통해 전달될 때 페이지를 도착하는 대로 점진적으로 표시합니다(가장 유용한 데이터를 먼저 표시);<br/>            - 전체 페이지가 수신 및 표시되기 전에 링크를 따라가는 등 사용자 상호작용을 수행할 수 있도록 허용합니다.<br/>            이 메서드를 호출해도 실제로 문서가 저장되지 않습니다. 오히려 문서는 최적화된 구조를 갖도록 준비될 뿐이며,<br/>            그런 다음 Save를 호출하여 최적화된 문서를 얻으세요. |
| get_catalog_value(key) | 카탈로그 사전에서 항목 값을 반환합니다. |
| free_memory() | 메모리를 해제합니다. |
| save_xml(file) | 문서를 XML로 저장합니다. |
| get_object_by_id(id) | 문서에서 지정된 ID를 가진 객체를 가져옵니다. |
| repair() | 손상된 문서를 복구합니다. |
| get_xmp_metadata(stream) | 문서에서 XMP 메타데이터를 가져옵니다. |
| set_xmp_metadata(stream) | 문서의 XMP 메타데이터를 설정합니다. |
| check(do_repair) | 문서를 검증합니다. |
| page_nodes_to_balanced_tree(nodes_num_in_subtrees) | 문서의 페이지 트리 노드를 균형 잡힌 트리로 정리합니다.<br/>            문서에 nodesNumInSubtrees보다 많은 페이지 객체가 있는 경우에만 수행되며, 그렇지 않으면 아무 작업도 하지 않습니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

