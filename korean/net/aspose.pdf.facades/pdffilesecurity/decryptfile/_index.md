---
title: "PdfFileSecurity.DecryptFile"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileSecurity 메서드. 소유자 비밀번호로 암호화된 Pdf 문서를 복호화합니다. 문서에 소유자 비밀번호가 없으면 사용자 비밀번호를 사용할 수 있습니다. 처리에 실패하면 예외를 발생시킵니다."
type: docs
weight: 60
url: /ko/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

소유자 비밀번호로 암호화된 Pdf 문서를 복호화합니다. 문서에 소유자 비밀번호가 없을 경우 사용자 비밀번호를 사용할 수 있습니다. 작업이 실패하면 예외를 발생시킵니다.

```csharp
public bool DecryptFile(string ownerPassword)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ownerPassword | String | 소유자 비밀번호. |

### 반환 값

성공이면 true.

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

### 또 보기

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


