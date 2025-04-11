---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 메서드. 사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. 프로세스가 실패하더라도 예외를 발생시키지 않습니다.
type: docs
weight: 110
url: /ko/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile 메서드

사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. 프로세스가 실패하더라도 예외를 발생시키지 않습니다.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| privilege | DocumentPrivilege | 권한 설정. |
| keySize | KeySize | 40비트 암호화를 위한 KeySize.x40, 128비트 암호화를 위한 KeySize.x128, 256비트 암호화를 위한 KeySize.x256. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### 참조

* 클래스 [DocumentPrivilege](../../documentprivilege/)
* 열거형 [KeySize](../../keysize/)
* 클래스 [PdfFileSecurity](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)