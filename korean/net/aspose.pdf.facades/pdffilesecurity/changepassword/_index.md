---
title: PdfFileSecurity.ChangePassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 메서드. 소유자 비밀번호로 사용자 비밀번호와 소유자 비밀번호를 변경하며 원래 보안 설정을 유지합니다. 새 사용자 비밀번호와 새 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. 프로세스가 실패하면 예외가 발생합니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

소유자 비밀번호로 사용자 비밀번호와 소유자 비밀번호를 변경하며 원래 보안 설정을 유지합니다. 새 사용자 비밀번호와 새 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. 프로세스가 실패하면 예외가 발생합니다.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | String | 원래 소유자 비밀번호. |
| newUserPassword | String | 새 사용자 비밀번호. |
| newOwnerPassword | String | 새 소유자 비밀번호. |

### 반환 값

성공 시 true.

## 예제

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### 참조

* 클래스 [PdfFileSecurity](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

소유자 비밀번호로 사용자 비밀번호와 비밀번호를 변경하며 Pdf 문서 보안을 재설정할 수 있습니다. 새 사용자 비밀번호와 새 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. 프로세스가 실패하면 예외가 발생합니다.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | String | 원래 소유자 비밀번호. |
| newUserPassword | String | 새 사용자 비밀번호. |
| newOwnerPassword | String | 새 소유자 비밀번호. |
| privilege | DocumentPrivilege | 보안 재설정. |
| keySize | KeySize | KeySize.x40는 40비트 암호화, KeySize.x128은 128비트 암호화, KeySize.x256은 256비트 암호화에 해당합니다. |

### 반환 값

성공 시 true.

## 예제

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### 참조

* 클래스 [DocumentPrivilege](../../documentprivilege/)
* 열거형 [KeySize](../../keysize/)
* 클래스 [PdfFileSecurity](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

소유자 비밀번호로 사용자 비밀번호와 비밀번호를 변경하며 Pdf 문서 보안을 재설정할 수 있습니다. 새 사용자 비밀번호와 새 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 새 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. KeySize와 Algorithm 값의 조합은 6가지가 가능합니다. 그러나 (KeySize.x40, Algorithm.AES)와 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며 이 조합을 만날 경우 해당 예외가 발생합니다. 프로세스가 실패하면 예외가 발생합니다.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | String | 원래 소유자 비밀번호. |
| newUserPassword | String | 새 사용자 비밀번호. |
| newOwnerPassword | String | 새 소유자 비밀번호. |
| privilege | DocumentPrivilege | 보안 재설정. |
| keySize | KeySize | KeySize.x40는 40비트 암호화, KeySize.x128은 128비트 암호화, KeySize.x256은 256비트 암호화에 해당합니다. |
| cipher | Algorithm | Algorithm.AES는 AES 알고리즘을 사용하여 암호화하거나 Algorithm.RC4는 RC4 암호화를 위해 사용합니다. |

### 반환 값

성공 시 true.

## 예제

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### 참조

* 클래스 [DocumentPrivilege](../../documentprivilege/)
* 열거형 [KeySize](../../keysize/)
* 열거형 [Algorithm](../../algorithm/)
* 클래스 [PdfFileSecurity](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)