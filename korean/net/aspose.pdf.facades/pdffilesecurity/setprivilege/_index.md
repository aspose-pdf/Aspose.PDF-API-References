---
title: "PdfFileSecurity.SetPrivilege"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileSecurity 메서드. 사용자/소유자 비밀번호가 비어 있는 상태에서 PDF 파일 보안을 설정합니다. 소유자 비밀번호는 무작위 문자열로 추가됩니다. 처리에 실패하면 예외를 발생시�니다"
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

빈 사용자/소유자 비밀번호로 Pdf 파일 보안을 설정합니다. 소유자 비밀번호는 무작위 문자열로 추가됩니다. 처리에 실패하면 예외를 발생시킵니다.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 권한 | DocumentPrivilege | 권한 설정. |

### 반환 값

성공이면 true.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### 또 보기

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

원본 비밀번호로 Pdf 파일 보안을 설정합니다. 처리에 실패하면 예외를 발생시킵니다.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 원본 사용자 비밀번호. |
| ownerPassword | String | 원본 소유자 비밀번호. |
| 권한 | DocumentPrivilege | 권한 설정. |

### 반환 값

성공이면 true.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### 또 보기

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


