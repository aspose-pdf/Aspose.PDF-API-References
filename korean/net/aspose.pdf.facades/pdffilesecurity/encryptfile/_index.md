---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 메서드. 사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. 프로세스가 실패하면 예외가 발생합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. 프로세스가 실패하면 예외가 발생합니다.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| privilege | DocumentPrivilege | 권한 설정. |
| keySize | KeySize | 40비트 암호화를 위한 KeySize.x40, 128비트 암호화를 위한 KeySize.x128, 256비트 암호화를 위한 KeySize.x256. |

### 반환 값

성공 시 True.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### 참조

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

사용자 비밀번호와 소유자 비밀번호로 Pdf 파일을 암호화하고 문서의 접근 권한을 설정합니다. 사용자 비밀번호와 소유자 비밀번호는 null 또는 비어 있을 수 있습니다. 입력된 소유자 비밀번호가 null 또는 비어 있으면 소유자 비밀번호는 임의의 문자열로 대체됩니다. KeySize와 Algorithm 값의 조합은 6가지가 가능합니다. 그러나 (KeySize.x40, Algorithm.AES) 및 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며, 이 조합을 만날 경우 해당 예외가 발생합니다. 프로세스가 실패하면 예외가 발생합니다.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |
| privilege | DocumentPrivilege | 권한 설정. |
| keySize | KeySize | 40비트 암호화를 위한 KeySize.x40, 128비트 암호화를 위한 KeySize.x128, 256비트 암호화를 위한 KeySize.x256. |
| cipher | Algorithm | AES 알고리즘을 사용하여 암호화하기 위한 Algorithm.AES 또는 RC4 암호화를 위한 Algorithm.RC4. |

### 반환 값

성공 시 True.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### 참조

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)