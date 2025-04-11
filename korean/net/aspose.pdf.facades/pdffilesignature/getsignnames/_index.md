---
title: PdfFileSignature.GetSignNames
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 메서드. 모든 비어 있지 않은 서명의 이름을 가져옵니다.
type: docs
weight: 230
url: /ko/net/aspose.pdf.facades/pdffilesignature/getsignnames/
---
## PdfFileSignature.GetSignNames 메서드

모든 비어 있지 않은 서명의 이름을 가져옵니다.

```csharp
public IList<string> GetSignNames(bool onlyActive = true)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| onlyActive | Boolean | true인 경우, 활성 서명만 반환합니다. 그렇지 않으면 모든 서명을 반환합니다. |

### 반환 값

IList&lt;string&gt;를 반환합니다.

## 예제

```csharp
[C#]
string inFile=TestPath + "example1.pdf";
PdfFileSignature pdfSign=new PdfFileSignature();
pdfSign.BindPdf(inFile); 
var names=pdfSign.GetSignNames();
or(int i=0;i<names.Count;i++)

 Console.WriteLine("signature name:"+names[i]);
 Console.WriteLine("coverswholedocument:"+pdfSign.IsCoversWholeDocument(names[i]));
 Console.WriteLine("revision:"+pdfSign.GetRevision(names[i]));	
 Console.WriteLine("verifysigned:"+pdfSign.VerifySigned(names[i]));
 Console.WriteLine("reason:"+pdfSign.GetReason(names[i]));
 Console.WriteLine("location:"+pdfSign.GetLocation(names[i]));
 Console.WriteLine("datatime:"+pdfSign.GetDateTime(names[i]));		
}
Console.WriteLine("totalvision:"+pdfSign.GetTotalRevision());
[Visual Basic]
Dim pdfSign as PdfFileSignature =new  PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names=pdfSign.GetSignNames()
For i=0 To names.Count

	Console.WriteLine("signature name:" + (string)names[i])
	Console.WriteLine("coverswholedocument:" + pdfSign.IsCoversWholeDocument((string)names[i]))
	Console.WriteLine("revision:" + pdfSign.GetRevision((string)names[i]))	
	Console.WriteLine("verifysigned:" + pdfSign.VerifySigned((string)names[i]))
	Console.WriteLine("reason:" + pdfSign.GetReason((string)names[i]))
	Console.WriteLine("location:" + pdfSign.GetLocation((string)names[i]))
	Console.WriteLine("datatime:" + pdfSign.GetDateTime((string)names[i]))	
Next i
Console.WriteLine("totalvision:"+pdfSign.GetTotalRevision())
```

### 참조

* 클래스 [PdfFileSignature](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)