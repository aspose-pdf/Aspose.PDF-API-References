---
title: PdfFileSignature.GetSignatureNames
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature method. Gets the names of all not empty signatures
type: docs
weight: 210
url: /net/aspose.pdf.facades/pdffilesignature/getsignaturenames/
---
## PdfFileSignature.GetSignatureNames method

Gets the names of all not empty signatures.

```csharp
public IList<SignatureName> GetSignatureNames(bool onlyActive = true)
```

| Parameter | Type | Description |
| --- | --- | --- |
| onlyActive | Boolean | if true, return only active signatures; otherwise, return all signatures. |

### Return Value

Return an IList&lt;SignatureName&gt;.

## Examples

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

### See Also

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


