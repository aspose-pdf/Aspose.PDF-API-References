---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 메서드. 빈 사용자/소유자 비밀번호로 Pdf 파일 보안을 설정합니다. 소유자 비밀번호는 임의의 문자열로 추가됩니다. 프로세스가 실패하면 예외가 발생합니다.
type: docs
weight: 80
url: /ko/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

빈 사용자/소유자 비밀번호로 Pdf 파일 보안을 설정합니다. 소유자 비밀번호는 임의의 문자열로 추가됩니다. 프로세스가 실패하면 예외가 발생합니다.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| privilege | DocumentPrivilege | 권한을 설정합니다. |

### Return Value

성공 시 True입니다.

## Examples

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

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

원래 비밀번호로 Pdf 파일 보안을 설정합니다. 프로세스가 실패하면 예외가 발생합니다.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | 원래 사용자 비밀번호입니다. |
| ownerPassword | String | 원래 소유자 비밀번호입니다. |
| privilege | DocumentPrivilege | 권한을 설정합니다. |

### Return Value

성공 시 True입니다.

## Examples

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

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)