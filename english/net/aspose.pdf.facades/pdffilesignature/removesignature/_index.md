---
title: PdfFileSignature.RemoveSignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature method. Remove the signature according to the name of the signature
type: docs
weight: 240
url: /net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(string) {#removesignature}

Remove the signature according to the name of the signature.

```csharp
public void RemoveSignature(string signName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | String | The name of signature. |

## Examples

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
PdfFileSignature pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile); 
IList names = pdfSign.GetSignNames();
for(int i = 0; i < names.Count; i++)
{
   pdfSign.RemoveSignature((string)names[i]);
}
pdfSign.Save(TestPath + "signed_removed.pdf");
[Visual Basic]
Dim pdfSign as PdfFileSignature = new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names = pdfSign.GetSignNames()
For i = 0 To names.Count
 pdfSign.RemoveSignature((string)names[i])
Next i
pdfSign.Save(TestPath + "signed_removed.pdf")
```

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## RemoveSignature(string, bool) {#removesignature_1}

Removes the signature according to the name of the signature.

```csharp
public void RemoveSignature(string signName, bool removeField)
```

| Parameter | Type | Description |
| --- | --- | --- |
| signName | String | The name of signature. |
| removeField | Boolean | If set to true, than removes both of signature and field from document; otherwise, signature only. |

## Examples

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
PdfFileSignature pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile); 
IList names = pdfSign.GetSignNames();
for(int i = 0; i < names.Count; i++)
{
   pdfSign.RemoveSignature((string)names[i], false);
}
pdfSign.Save(TestPath + "signed_removed.pdf");
[Visual Basic]
Dim pdfSign as PdfFileSignature = new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names = pdfSign.GetSignNames()
For i = 0 To names.Count
 pdfSign.RemoveSignature((string)names[i], false)
Next i
pdfSign.Save(TestPath + "signed_removed.pdf")
```

### See Also

* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


