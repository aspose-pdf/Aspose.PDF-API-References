---
title: PdfFileSignature.GetSignNames
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature メソッド。すべての空でない署名の名前を取得します
type: docs
weight: 230
url: /ja/net/aspose.pdf.facades/pdffilesignature/getsignnames/
---
## PdfFileSignature.GetSignNames メソッド

すべての空でない署名の名前を取得します。

```csharp
public IList<string> GetSignNames(bool onlyActive = true)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| onlyActive | Boolean | true の場合、アクティブな署名のみを返します。それ以外の場合は、すべての署名を返します。 |

### 戻り値

IList&lt;string&gt; を返します。

## 例

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

### 参照

* クラス [PdfFileSignature](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)