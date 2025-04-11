---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSecurity 클래스. 소유자 또는 사용자 비밀번호로 Pdf 파일을 암호화하거나 복호화하고 보안 설정 및 비밀번호를 변경합니다.
type: docs
weight: 4550
url: /ko/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity 클래스

소유자 또는 사용자 비밀번호로 Pdf 파일을 암호화하거나 복호화하고 보안 설정 및 비밀번호를 변경합니다.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | PdfFileSecurity 객체를 초기화합니다. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | *document*를 기반으로 새로운 `PdfFileSecurity` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 문서의 파사드를 가져옵니다. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | 마지막 작업에서 발생한 예외를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 파사드를 초기화합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | 파사드를 초기화합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | 파사드를 초기화합니다. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | 소유자 비밀번호로 사용자 비밀번호와 소유자 비밀번호를 변경하고 원래 보안 설정을 유지합니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. 프로세스가 실패하면 예외가 발생합니다. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | 소유자 비밀번호로 사용자 비밀번호와 비밀번호를 변경하고 Pdf 문서 보안을 재설정할 수 있습니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. 프로세스가 실패하면 예외가 발생합니다. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | 소유자 비밀번호로 사용자 비밀번호와 비밀번호를 변경하고 Pdf 문서 보안을 재설정할 수 있습니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. KeySize와 Algorithm 값의 조합은 6가지가 가능합니다. 그러나 (KeySize.x40, Algorithm.AES) 및 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며 이 조합을 만날 경우 해당 예외가 발생합니다. 프로세스가 실패하면 예외가 발생합니다. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | 파사드를 닫습니다. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | 소유자 비밀번호로 암호화된 Pdf 문서를 복호화합니다. 문서에 소유자 비밀번호가 없는 경우 사용자 비밀번호를 사용할 수 있습니다. 프로세스가 실패하면 예외가 발생합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 폐기합니다. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | 사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. 프로세스가 실패하면 예외가 발생합니다. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | 사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. KeySize와 Algorithm 값의 조합은 6가지가 가능합니다. 그러나 (KeySize.x40, Algorithm.AES) 및 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며 이 조합을 만날 경우 해당 예외가 발생합니다. 프로세스가 실패하면 예외가 발생합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF 문서를 지정된 파일에 저장합니다. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | 빈 사용자/소유자 비밀번호로 Pdf 파일 보안을 설정합니다. 소유자 비밀번호는 무작위 문자열로 추가됩니다. 프로세스가 실패하면 예외가 발생합니다. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | 원래 비밀번호로 Pdf 파일 보안을 설정합니다. 프로세스가 실패하면 예외가 발생합니다. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | 소유자 비밀번호로 사용자 비밀번호와 소유자 비밀번호를 변경하고 원래 보안 설정을 유지합니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. 프로세스가 실패하면 예외를 발생시키지 않습니다. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | 소유자 비밀번호로 사용자 비밀번호와 비밀번호를 변경하고 Pdf 문서 보안을 재설정할 수 있습니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. 프로세스가 실패하면 예외를 발생시키지 않습니다. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | 소유자 비밀번호로 사용자 비밀번호와 비밀번호를 변경하고 Pdf 문서 보안을 재설정할 수 있습니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. KeySize와 Algorithm 값의 조합은 6가지가 가능합니다. 그러나 (KeySize.x40, Algorithm.AES) 및 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며 이 조합을 만날 경우 해당 예외가 발생합니다. 프로세스가 실패하면 예외를 발생시키지 않습니다. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | 소유자 비밀번호로 암호화된 Pdf 문서를 복호화합니다. 문서에 소유자 비밀번호가 없는 경우 사용자 비밀번호를 사용할 수 있습니다. 프로세스가 실패하면 예외를 발생시키지 않습니다. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | 사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 무작위 문자열로 대체됩니다. 프로세스가 실패하면 예외를 발생시키지 않습니다. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | 원래 비밀번호로 Pdf 파일 보안을 설정합니다. 프로세스가 실패하면 예외를 발생시키지 않습니다. |

### 참조

* 클래스 [SaveableFacade](../saveablefacade/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)