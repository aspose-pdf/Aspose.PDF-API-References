---
title: PdfFileSignature.GetSignatureNames
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature 方法。获取所有非空签名的名称
type: docs
weight: 210
url: /zh/net/aspose.pdf.facades/pdffilesignature/getsignaturenames/
---
## PdfFileSignature.GetSignatureNames 方法

获取所有非空签名的名称。

```csharp
public IList<SignatureName> GetSignatureNames(bool onlyActive = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| onlyActive | 布尔值 | 如果为 true，则仅返回活动签名；否则，返回所有签名。 |

### 返回值

返回 IList&lt;SignatureName&gt;。

## 示例

```csharp
[C#]
string inFile=TestPath + "example1.pdf";
PdfFileSignature pdfSign=new PdfFileSignature();
pdfSign.BindPdf(inFile); 
var names=pdfSign.GetSignatureNames();
or(int i=0;i<names.Count;i++)

 Console.WriteLine("signature name:" + names[i]);
 Console.WriteLine("coverswholedocument:" + pdfSign.CoversWholeDocument(names[i]));
 Console.WriteLine("revision:" + pdfSign.GetRevision(names[i]));	
 Console.WriteLine("verifysigned:" + pdfSign.VerifySignature(names[i]));
 Console.WriteLine("reason:" + pdfSign.GetReason(names[i]));
 Console.WriteLine("location:" + pdfSign.GetLocation(names[i]));
 Console.WriteLine("datatime:" + pdfSign.GetDateTime(names[i]));		
}
Console.WriteLine("totalvision:" + pdfSign.GetTotalRevision());
[Visual Basic]
Dim pdfSign as PdfFileSignature =new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names=pdfSign.GetSignNames()
For i=0 To names.Count

	Console.WriteLine("signature name:" + (SignatureName)names[i])
	Console.WriteLine("coverswholedocument:" + pdfSign.IsCoversWholeDocument((string)names[i]))
	Console.WriteLine("revision:" + pdfSign.GetRevision((SignatureName)names[i]))	
	Console.WriteLine("verifysigned:" + pdfSign.VerifySignature((SignatureName)names[i]))
	Console.WriteLine("reason:" + pdfSign.GetReason((SignatureName)names[i]))
	Console.WriteLine("location:" + pdfSign.GetLocation((SignatureName)names[i]))
	Console.WriteLine("datatime:" + pdfSign.GetDateTime((SignatureName)names[i]))	
Next i
Console.WriteLine("totalvision:" + pdfSign.GetTotalRevision())
```

### 另请参阅

* 类 [SignatureName](../../signaturename/)
* 类 [PdfFileSignature](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)