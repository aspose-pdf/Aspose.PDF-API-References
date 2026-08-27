---
title: "PdfFileSignature"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "인증서를 사용하여 PDF 파일에 서명하는 클래스를 나타냅니다."
type: docs
weight: 310
url: /ko/python-net/aspose.pdf.facades/pdffilesignature/
---

## PdfFileSignature class

인증서를 사용하여 PDF 파일에 서명하는 클래스를 나타냅니다.

PdfFileSignature 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfFileSignature() | PdfFileSignature 클래스의 생성자입니다. |
| PdfFileSignature(input_file) | PdfFileSignature 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileSignature(input_file, output_file) | PdfFileSignature 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileSignature(document) | PdfFileSignature 클래스의 새 인스턴스를 초기화합니다 |
| PdfFileSignature(document, output_file) | PdfFileSignature 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| signature_appearance | 서명에 대한 그래픽 외관을 설정하거나 가져옵니다. 속성 값은 이미지 파일 이름을 나타냅니다. |
| is_ltv_enabled | LTV 활성화 플래그를 가져옵니다. |
| is_certified | 문서가 인증되었는지 여부를 결정하는 플래그를 가져옵니다. |
| signature_appearance_stream | 서명에 대한 그래픽 외관을 설정하거나 가져옵니다. 속성 값은 이미지 스트림을 나타냅니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(input_file) | 편집을 위해 Pdf 파일을 바인딩합니다. |
| bind_pdf(input_stream) | 편집을 위해 Pdf 스트림을 바인딩합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(output_file) | 결과 PDF를 파일에 저장합니다. |
| save(output_stream) | 결과 PDF를 스트림에 저장합니다. |
| save() | 결과 PDF를 파일에 저장합니다. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect) | pdf 문서에 서명을 만듭니다. |
| sign(page, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | 주어진 유형 서명으로 문서에 서명합니다. |
| sign(page, visible, annot_rect, sig) | 주어진 유형 서명으로 문서에 서명합니다. |
| sign(sig_name, sig_reason, sig_contact, sig_location, sig) | 주어진 유형 서명으로 문서에 서명합니다. |
| sign(page, sig_name, sig_reason, sig_contact, sig_location, visible, annot_rect, sig) | 주어진 유형 서명으로 문서에 서명합니다. |
| sign(sig_name, sig) | 주어진 유형 서명으로 문서에 서명합니다. |
| certify(page, sig_reason, sig_contact, sig_location, visible, annot_rect, doc_mdp_signature) | MDP 서명을 사용하여 문서를 인증합니다.<br/>            서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성으로 제공되어야 합니다. |
| certify(sig_name, doc_mdp_signature) | MDP 서명을 사용하여 문서를 인증합니다.<br/>            서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성으로 제공되어야 합니다. |
| remove_signature(sign_name) | 서명 이름에 따라 서명을 제거합니다. |
| remove_signature(sign_name, remove_field) | 서명 이름에 따라 서명을 제거합니다. |
| close() | Facade를 닫습니다. |
| get_access_permissions() | MDP 서명 유형으로 인증된 문서의 접근 권한 값을 반환합니다. |
| get_sign_names(only_active) | 비어 있지 않은 모든 서명의 이름을 가져옵니다. |
| get_blank_sign_names() | 비어 있는 모든 서명 필드의 이름을 가져옵니다. |
| is_contain_signature() | PDF에 디지털 서명이 있는지 여부를 확인합니다. |
| contains_signature() | PDF에 디지털 서명이 있는지 여부를 확인합니다. |
| contains_usage_rights() | PDF에 사용 권한이 있는지 여부를 확인합니다. |
| is_covers_whole_document(sign_name) | 서명이 전체 문서를 커버하는지 확인합니다. |
| covers_whole_document(sign_name) | 서명이 전체 문서를 커버하는지 확인합니다. |
| get_revision(sign_name) | 서명의 개정을 가져옵니다. |
| get_total_revision() | 전체 개정 번호를 가져옵니다. |
| remove_usage_rights() | 사용 권한 항목을 제거합니다. |
| verify_signed(sign_name) | 서명의 유효성을 확인합니다. |
| get_signer_name(sign_name) | PDF 문서에 서명한 사람 또는 조직의 이름을 가져옵니다. |
| get_date_time(sign_name) | 서명의 날짜와 시간을 가져옵니다. |
| get_reason(sign_name) | 서명의 이유를 가져옵니다. |
| get_location(sign_name) | 서명의 위치를 가져옵니다. |
| get_contact_info(sign_name) | 서명의 연락처 정보를 가져옵니다. |
| verify_signature(sign_name) | 서명의 유효성을 확인합니다. |
| extract_image(sign_name) | 서명의 이미지를 추출합니다. |
| extract_certificate(sign_name) | 서명의 단일 X.509 인증서를 스트림으로 추출합니다. |
| set_certificate(pfx, pass) | 서명 절차를 위한 인증서 파일과 비밀번호를 설정합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

