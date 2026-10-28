---
title: "PdfFileInfo"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 문서의 메타 정보를 액세스하는 클래스를 나타냅니다."
type: docs
weight: 270
url: /ko/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

PDF 문서의 메타 정보를 액세스하는 클래스를 나타냅니다.

PdfFileInfo 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfFileInfo() | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| PdfFileInfo(input_stream) | PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileInfo(input_stream, password) | PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileInfo(input_file) | PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileInfo(input_file, password) | PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileInfo(document) | PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| author | PDF 문서의 Author 정보를 가져오거나 설정합니다. |
| is_encrypted | PDF 문서가 암호화되었는지 확인합니다. |
| is_pdf_file | 소스 입력이 유효한 PDF 파일인지 확인합니다. |
| use_strict_validation | 엄격한 검증 규칙을 사용하여 [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) 속성을 이용합니다. |
| creation_date | PDF 문서의 CreationDate 정보를 가져오거나 설정합니다. |
| creator | PDF 문서의 Creator 정보를 가져오거나 설정합니다. |
| has_collection | 현재 입력 파일이 PDF 파일 컬렉션을 포함하는 'Portfolio' 파일인 경우 true를 반환합니다. |
| input_file | 입력 파일을 가져오거나 설정합니다. |
| input_stream | 입력 스트림을 가져오거나 설정합니다. |
| keywords | PDF 문서의 Keywords 정보를 가져오거나 설정합니다. |
| mod_date | PDF 문서의 ModDate 날짜 정보를 가져오거나 설정합니다. |
| number_of_pages | 문서 페이지 수를 가져옵니다. |
| producer | PDF 문서의 Producer 정보를 가져옵니다. |
| subject | PDF 문서의 Subject 정보를 가져오거나 설정합니다. |
| 제목 | PDF 문서의 Title 정보를 가져오거나 설정합니다. |
| password_type | PdfFileInfo 인스턴스를 생성할 때 전달된 비밀번호 유형을 반환합니다. 가능한 값은 [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/)에서 확인하세요.<br/>            PDF 문서는 사용자(또는 열기) 비밀번호와 소유자(또는 권한, 편집) 비밀번호 모두를 사용하여 열 수 있다는 점에 유의하십시오. |
| has_open_password | 비밀번호로 보호된 PDF 문서를 열기 위해 비밀번호가 필요하면 true를 반환합니다. |
| has_edit_password | 권한 또는 문서 보안 속성을 수정하기 위해 비밀번호가 필요하면 true를 반환합니다.<br/>            이 속성은 [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/) 생성자에 유효한 비밀번호가 제공된 경우에만 읽을 수 있다는 점에 유의하십시오.<br/>            PasswordType이 Inaccessible인 경우(잘못된 비밀번호가 제공된 경우) 이 속성을 읽으면 [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/)이 발생합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_doc) | 파사드를 초기화합니다. |
| bind_pdf(src_file) | 파사드를 초기화합니다. |
| bind_pdf(src_stream) | 파사드를 초기화합니다. |
| save(dest_stream) | 업데이트된 PDF 문서를 지정된 스트림에 저장합니다. |
| save(dest_file) | 업데이트된 PDF 문서를 지정된 파일에 저장합니다. |
| save_new_info(output_stream) | 업데이트된 PDF 문서를 지정된 스트림에 저장합니다. |
| save_new_info(output_file) | 업데이트된 PDF 문서를 지정된 파일에 저장합니다. |
| close() | 인스턴스를 비활성화합니다. |
| clear_info() | PDF 문서의 모든 메타 정보를 삭제합니다. |
| get_document_privilege() | PDF 문서 권한 설정을 가져옵니다. |
| get_meta_info(name) | 속성 이름을 사용하여 PDF 문서의 사용자 정의 정보를 가져옵니다. 해당 이름과 일치하는 속성이 없으면 빈 문자열을 반환합니다. |
| get_page_height(page_num) | 지정된 페이지의 높이를 가져옵니다. |
| get_page_rotation(page_num) | 지정된 페이지의 회전을 가져옵니다. |
| get_page_width(page_num) | 지정된 페이지의 너비를 가져옵니다. |
| get_page_x_offset(page_num) | 지정된 페이지 표시 영역의 수평 오프셋을 가져옵니다. |
| get_page_y_offset(page_num) | 지정된 페이지 표시 영역의 수직 오프셋을 가져옵니다. |
| get_pdf_version() | PDF 문서의 버전 정보를 가져옵니다. |
| set_meta_info(name, value) | PDF 문서의 사용자 지정 정보를 설정합니다. |
| save_new_info_with_xmp(output_file_name) | 파일 정보를 설정하여 명시적으로 지정된 속성을 변경하고, 다른 속성은 그대로 유지합니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

