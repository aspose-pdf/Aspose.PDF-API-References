---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity 메서드. 소유자 비밀번호로 암호화된 Pdf 문서를 복호화합니다. 문서에 소유자 비밀번호가 없으면 사용자 비밀번호를 사용할 수 있습니다. 프로세스가 실패하더라도 예외를 발생시키지 않습니다.
type: docs
weight: 100
url: /ko/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile 메서드

소유자 비밀번호로 암호화된 Pdf 문서를 복호화합니다. 문서에 소유자 비밀번호가 없으면 사용자 비밀번호를 사용할 수 있습니다. 프로세스가 실패하더라도 예외를 발생시키지 않습니다.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | 문자열 | 소유자 비밀번호. |

### 반환 값

성공 시 true, 실패 시 false.

## 예제

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### 참조

* 클래스 [PdfFileSecurity](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)