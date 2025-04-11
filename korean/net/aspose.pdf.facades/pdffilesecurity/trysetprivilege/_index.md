---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 메서드. 원래 비밀번호로 Pdf 파일 보안을 설정합니다. 프로세스가 실패하더라도 예외를 발생시키지 않습니다.
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege 메서드

원래 비밀번호로 Pdf 파일 보안을 설정합니다. 프로세스가 실패하더라도 예외를 발생시키지 않습니다.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 원래 사용자 비밀번호. |
| ownerPassword | String | 원래 소유자 비밀번호. |
| privilege | DocumentPrivilege | 권한 설정. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### 참조

* 클래스 [DocumentPrivilege](../../documentprivilege/)
* 클래스 [PdfFileSecurity](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)