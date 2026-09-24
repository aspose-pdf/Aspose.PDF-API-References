---
title: "PdfFileSignature.GetSignNames"
linktitle: "GetSignNames"
articleTitle: "GetSignNames"
second_title: "Aspose.PDF for .NET"
description: "Gets the names of all not empty signatures."
type: docs
weight: 190
url: "/net/aspose.pdf.facades/pdffilesignature/getsignnames/"
product_version: "26.9.0"
---
## GetSignNames(bool) {#getsignnames}

> **Deprecated.** The method can produce the same signature names, which cannot be distinguished during verification. Use GetSignatureNames(bool onlyActive) instead.

Gets the names of all not empty signatures.

```csharp
public IList<string> GetSignNames(bool onlyActive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| onlyActive | bool | if true, return only active signatures; otherwise, return all signatures. |

### Return Value

[IList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ilist-1)<string>

Return an IList&lt;string&gt;.

## Examples

```csharp
[C#]
 string inFile=TestPath + "example1.pdf";
 PdfFileSignature pdfSign=new PdfFileSignature();
 pdfSign.BindPdf(inFile); 
 var names=pdfSign.GetSignNames();
 for(int i=0;i<names.Count;i++)
 {
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
 Dim pdfSign as PdfFileSignature =new PdfFileSignature
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

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

