---
title: "PdfFileSecurity"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "소유자 또는 사용자 비밀번호로 PDF 파일을 암호화하거나 복호화하고, 보안 설정 및 비밀번호를 변경하는 것을 나타냅니다."
type: docs
weight: 300
url: /ko/python-net/aspose.pdf.facades/pdffilesecurity/
---

## PdfFileSecurity class

소유자 또는 사용자 비밀번호로 PDF 파일을 암호화하거나 복호화하고, 보안 설정 및 비밀번호를 변경하는 것을 나타냅니다.

PdfFileSecurity 형식은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| PdfFileSecurity(input_stream, output_stream) | PdfFileSecurity 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileSecurity(input_file, output_file) | PdfFileSecurity 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileSecurity() | PdfFileSecurity 객체를 초기화합니다. |
| PdfFileSecurity(document) | PdfFileSecurity 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileSecurity(document, output_file) | PdfFileSecurity 클래스의 새 인스턴스를 초기화합니다. |
| PdfFileSecurity(document, output_stream) | PdfFileSecurity 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| document | 작업 중인 문서 파사드를 가져옵니다. |
| allow_exceptions | 이 값을 true로 설정하면 작업 실패 시 예외가 발생합니다. 그렇지 않으면 메서드는 실패 시 false를 반환하고 마지막 예외는 LastException 속성을 통해 확인할 수 있습니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| bind_pdf(src_file) | 파사드를 초기화합니다. |
| bind_pdf(src_stream) | 파사드를 초기화합니다. |
| bind_pdf(src_doc) | PDF 문서를 편집용으로 바인딩합니다. |
| save(dest_file) | PDF 문서를 지정된 파일에 저장합니다. |
| save(dest_stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| encrypt_file(user_password, owner_password, privilege, key_size) | 사용자 비밀번호와 소유자 비밀번호로 PDF 파일을 암호화하고 문서의 접근 권한을 설정합니다.<br/>            사용자 비밀번호와 소유자 비밀번호는 null 또는 빈 문자열일 수 있습니다. 입력된 소유자 비밀번호가 null 또는 빈 문자열인 경우 소유자 비밀번호는 무작위 문자열로 대체됩니다.<br/>            처리에 실패하면 예외가 발생합니다. |
| encrypt_file(user_password, owner_password, privilege, key_size, cipher) | 사용자 비밀번호와 소유자 비밀번호로 PDF 파일을 암호화하고 문서의 접근 권한을 설정합니다.<br/>            사용자 비밀번호와 소유자 비밀번호는 null 또는 빈 문자열일 수 있습니다. 입력된 소유자 비밀번호가 null 또는 빈 문자열인 경우 소유자 비밀번호는 무작위 문자열로 대체됩니다.<br/>            KeySize와 Algorithm 값의 가능한 조합은 6가지입니다.<br/>            그러나 (KeySize.x40, Algorithm.AES)와 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며, 키트가 이 조합을 만나면 해당 예외가 발생합니다.<br/>            처리에 실패하면 예외가 발생합니다. |
| set_privilege(privilege) | 빈 사용자/소유자 비밀번호로 PDF 파일 보안을 설정합니다.<br/>            소유자 비밀번호는 무작위 문자열로 추가됩니다.<br/>            처리에 실패하면 예외가 발생합니다. |
| set_privilege(user_password, owner_password, privilege) | 원래 비밀번호로 PDF 파일 보안을 설정합니다.<br/>            처리에 실패하면 예외가 발생합니다. |
| change_password(owner_password, new_user_password, new_owner_password) | 소유자 비밀번호를 사용하여 사용자 비밀번호와 소유자 비밀번호를 변경하고, 원래 보안 설정을 유지합니다.<br/>             새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 빈 문자열일 수 있습니다. 새로운 소유자 비밀번호가 null 또는 빈 문자열인 경우 소유자 비밀번호는 무작위 문자열로 대체됩니다.<br/>             처리에 실패하면 예외가 발생합니다. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | 소유자 비밀번호를 사용하여 사용자 비밀번호와 비밀번호를 변경하고, PDF 문서 보안을 재설정할 수 있습니다.<br/>            새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 빈 문자열일 수 있습니다. 새로운 소유자 비밀번호가 null 또는 빈 문자열인 경우 소유자 비밀번호는 무작위 문자열로 대체됩니다.<br/>            처리에 실패하면 예외가 발생합니다. |
| change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | 소유자 비밀번호를 사용하여 사용자 비밀번호와 비밀번호를 변경하고, PDF 문서 보안을 재설정할 수 있습니다.<br/>            새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 빈 문자열일 수 있습니다. 새로운 소유자 비밀번호가 null 또는 빈 문자열인 경우 소유자 비밀번호는 무작위 문자열로 대체됩니다.<br/>            KeySize와 Algorithm 값의 가능한 조합은 6가지입니다.<br/>            그러나 (KeySize.x40, Algorithm.AES)와 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며, 키트가 이 조합을 만나면 해당 예외가 발생합니다.<br/>            처리에 실패하면 예외가 발생합니다. |
| try_change_password(owner_password, new_user_password, new_owner_password) | 소유자 비밀번호를 사용하여 사용자 비밀번호와 소유자 비밀번호를 변경하고, 원래 보안 설정을 유지합니다.<br/>             새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 빈 문자열일 수 있습니다. 소유자 비밀번호는 새로운 소유자 비밀번호가 null 또는 빈 문자열인 경우 무작위 문자열로 대체됩니다.<br/>             처리에 실패해도 예외가 발생하지 않습니다. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size) | 소유자 비밀번호를 사용하여 사용자 비밀번호와 비밀번호를 변경하고, PDF 문서 보안을 재설정할 수 있습니다.<br/>            새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 빈 문자열일 수 있습니다. 새로운 소유자 비밀번호가 null 또는 빈 문자열인 경우 소유자 비밀번호는 무작위 문자열로 대체됩니다.<br/>            처리에 실패해도 예외가 발생하지 않습니다. |
| try_change_password(owner_password, new_user_password, new_owner_password, privilege, key_size, cipher) | 소유자 비밀번호를 사용하여 사용자 비밀번호와 비밀번호를 변경하고, PDF 문서 보안을 재설정할 수 있습니다.<br/>            새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 빈 문자열일 수 있습니다. 새로운 소유자 비밀번호가 null 또는 빈 문자열인 경우 소유자 비밀번호는 무작위 문자열로 대체됩니다.<br/>            KeySize와 Algorithm 값의 가능한 조합은 6가지입니다.<br/>            그러나 (KeySize.x40, Algorithm.AES)와 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며, 키트가 이 조합을 만나면 해당 예외가 발생합니다.<br/>            처리에 실패해도 예외가 발생하지 않습니다. |
| close() | Facade를 닫습니다. |
| try_encrypt_file(user_password, owner_password, privilege, key_size) | 사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다.<br/>            사용자 비밀번호와 소유자 비밀번호는 null이거나 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null이거나 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다.<br/>            프로세스가 실패해도 예외를 발생시키지 않습니다. |
| decrypt_file(owner_password) | 소유자 비밀번호로 암호화된 Pdf 문서를 복호화합니다. <br/>            문서에 소유자 비밀번호가 없을 경우 사용자 비밀번호를 사용할 수 있습니다.<br/>            프로세스가 실패하면 예외를 발생시킵니다. |
| try_decrypt_file(owner_password) | 소유자 비밀번호로 암호화된 Pdf 문서를 복호화합니다. <br/>            문서에 소유자 비밀번호가 없을 경우 사용자 비밀번호를 사용할 수 있습니다.<br/>            프로세스가 실패해도 예외를 발생시키지 않습니다. |
| try_set_privilege(user_password, owner_password, privilege) | 원본 비밀번호로 Pdf 파일 보안을 설정합니다.<br/>            프로세스가 실패해도 예외를 발생시키지 않습니다. |

### 또 보기

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

