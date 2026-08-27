---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileSecurity 메서드. 사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null이거나 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null이거나 비어 있으면 소유자 비밀번호가 임의 문자열로 교체됩니다. 처리에 실패해도 예외를 발생시키지 않습니다."
type: docs
weight: 110
url: /ko/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

Pdf 파일을 사용자 비밀번호와 소유자 비밀번호로 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null이거나 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null이거나 비어 있으면 소유자 비밀번호가 무작위 문자열로 교체됩니다. 처리에 실패해도 예외를 발생시키지 않습니다.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| 권한 | DocumentPrivilege | 권한 설정. |
| 키 크기 | KeySize | KeySize.x40은 40비트 암호화, KeySize.x128은 128비트 암호화, KeySize.x256은 256비트 암호화를 의미합니다. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

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

### 또 보기

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


