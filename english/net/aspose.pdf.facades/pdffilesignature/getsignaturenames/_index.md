---
title: "PdfFileSignature.GetSignatureNames"
linktitle: "GetSignatureNames"
articleTitle: "GetSignatureNames"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfFileSignature method. Gets the names of all not empty signatures."
type: docs
weight: 200
url: "/net/aspose.pdf.facades/pdffilesignature/getsignaturenames/"
product_version: "26.9.0"
---
## GetSignatureNames(bool) {#getsignaturenames}

Gets the names of all not empty signatures.

```csharp
public IList<SignatureName> GetSignatureNames(bool onlyActive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| onlyActive | bool | if true, return only active signatures; otherwise, return all signatures. |

### Return Value

[IList](https://learn.microsoft.com/dotnet/api/system.collections.generic.ilist-1)<[SignatureName](../../../aspose.pdf.facades/signaturename/)>

Return an IList&lt;SignatureName&gt;.

## Examples

```csharp
[C#]
 string inFile=TestPath + "example1.pdf";
 PdfFileSignature pdfSign=new PdfFileSignature();
 pdfSign.BindPdf(inFile); 
 var names=pdfSign.GetSignatureNames();
 for(int i=0;i<names.Count;i++)
 {
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

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

