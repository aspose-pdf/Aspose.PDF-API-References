---
title: "PdfFileSignature.GetSignNames"
second_title: "Aspose.PDF for .NET API 参考"
description: "PdfFileSignature 方法。获取所有非空签名的名称"
type: docs
weight: 230
url: /zh/net/aspose.pdf.facades/pdffilesignature/getsignnames/
---
## PdfFileSignature.GetSignNames method

获取所有非空签名的名称。

```csharp
public IList<string> GetSignNames(bool onlyActive = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| onlyActive | Boolean | 如果为 true，则仅返回活动签名；否则，返回所有签名。 |

### 返回值

返回一个 IList&lt;string&gt;。

## 示例

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

### 另请参见

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


