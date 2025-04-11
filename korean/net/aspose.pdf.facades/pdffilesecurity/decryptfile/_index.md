---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 메서드. 소유자 비밀번호로 암호화된 Pdf 문서를 해독합니다. 문서에 소유자 비밀번호가 없으면 사용자 비밀번호를 사용할 수 있습니다. 프로세스가 실패하면 예외가 발생합니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile 메서드

소유자 비밀번호로 암호화된 Pdf 문서를 해독합니다. 문서에 소유자 비밀번호가 없으면 사용자 비밀번호를 사용할 수 있습니다. 프로세스가 실패하면 예외가 발생합니다.

```csharp
public bool DecryptFile(string ownerPassword)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | String | 소유자 비밀번호. |

### 반환 값

성공 시 True입니다.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### 참조

* 클래스 [PdfFileSecurity](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)