---
title: "PdfFileSecurity.TryChangePassword"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileSecurity 메서드. 소유자 비밀번호를 사용하여 사용자 비밀번호와 소유자 비밀번호를 변경하며 원래 보안 설정을 유지합니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null이거나 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null이거나 비어 있으면 소유자 비밀번호는 무작위 문자열로 교체됩니다. 처리에 실패해도 예외를 발생시키지 않습니다."
type: docs
weight: 90
url: /ko/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

사용자 비밀번호와 소유자 비밀번호를 소유자 비밀번호로 변경하고, 원래 보안 설정을 유지합니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null이거나 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null이거나 비어 있으면 소유자 비밀번호가 무작위 문자열로 교체됩니다. 처리에 실패해도 예외를 발생시키지 않습니다.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | String | 원본 소유자 비밀번호. |
| newUserPassword | String | 새 사용자 비밀번호. |
| newOwnerPassword | String | 새 소유자 비밀번호. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 예제

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### 또 보기

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

소유자 비밀번호로 사용자 비밀번호와 비밀번호를 변경하여 Pdf 문서 보안을 재설정할 수 있습니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null이거나 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null이거나 비어 있으면 소유자 비밀번호가 무작위 문자열로 교체됩니다. 처리에 실패해도 예외를 발생시키지 않습니다.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | String | 원본 소유자 비밀번호. |
| newUserPassword | String | 새 사용자 비밀번호. |
| newOwnerPassword | String | 새 소유자 비밀번호. |
| 권한 | DocumentPrivilege | 보안을 재설정합니다. |
| 키 크기 | KeySize | KeySize.x40은 40비트 암호화, KeySize.x128은 128비트 암호화, KeySize.x256은 256비트 암호화를 의미합니다. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 예제

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### 또 보기

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

소유자 비밀번호로 사용자 비밀번호와 비밀번호를 변경하여 Pdf 문서 보안을 재설정할 수 있습니다. 새로운 사용자 비밀번호와 새로운 소유자 비밀번호는 null이거나 비어 있을 수 있습니다. 새로운 소유자 비밀번호가 null이거나 비어 있으면 소유자 비밀번호가 무작위 문자열로 교체됩니다. KeySize와 Algorithm 값의 가능한 조합은 6가지입니다. 그러나 (KeySize.x40, Algorithm.AES)와 (KeySize.x256, Algorithm.RC4)는 유효하지 않으며, 키트가 이 조합을 만나면 해당 예외가 발생합니다. 처리에 실패해도 예외를 발생시키지 않습니다.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | String | 원본 소유자 비밀번호. |
| newUserPassword | String | 새 사용자 비밀번호. |
| newOwnerPassword | String | 새 소유자 비밀번호. |
| 권한 | DocumentPrivilege | 보안을 재설정합니다. |
| 키 크기 | KeySize | KeySize.x40은 40비트 암호화, KeySize.x128은 128비트 암호화, KeySize.x256은 256비트 암호화를 의미합니다. |
| 암호 | Algorithm | Algorithm.AES는 AES 알고리즘을 사용하여 암호화하고, Algorithm.RC4는 RC4 암호화를 수행합니다. |

### 반환 값

성공이면 true, 그렇지 않으면 false.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### 또 보기

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


