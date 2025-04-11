---
title: PdfFileSignature.RemoveSignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature metodu. İmzanın adına göre imzayı kaldır
type: docs
weight: 250
url: /tr/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(SignatureName) {#removesignature}

İmzanın adına göre imzayı kaldır.

```csharp
public void RemoveSignature(SignatureName signName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signName | SignatureName | İmzanın adı. |

## Örnekler

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
PdfFileSignature pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile); 
IList<SignatureName> names = pdfSign.GetSignatureNames();
for(int i = 0; i < names.Count; i++)
{
   pdfSign.RemoveSignature(names[i]);
}
pdfSign.Save(TestPath + "signed_removed.pdf");
[Visual Basic]
Dim pdfSign as PdfFileSignature = new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names = pdfSign.GetSignatureNames()
For i = 0 To names.Count
 pdfSign.RemoveSignature((SignatureName)names[i])
Next i
pdfSign.Save(TestPath + "signed_removed.pdf")
```

### Ayrıca Bakınız

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## RemoveSignature(SignatureName, bool) {#removesignature_1}

İmzanın adına göre imzayı kaldırır.

```csharp
public void RemoveSignature(SignatureName signName, bool removeField)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signName | SignatureName | İmzanın adı. |
| removeField | Boolean | true olarak ayarlandığında, hem imzayı hem de alanı belgeden kaldırır; aksi takdirde, yalnızca imzayı kaldırır. |

## Örnekler

```csharp
[C#]
string inFile = TestPath + "example1.pdf";
PdfFileSignature pdfSign = new PdfFileSignature();
pdfSign.BindPdf(inFile); 
IList<SignatureName> names = pdfSign.GetSignatureNames();
for(int i = 0; i < names.Count; i++)
{
   pdfSign.RemoveSignature(names[i], false);
}
pdfSign.Save(TestPath + "signed_removed.pdf");
[Visual Basic]
Dim pdfSign as PdfFileSignature = new PdfFileSignature
pdfSign.BindPdf(inFile)
Dim names as IList
names = pdfSign.GetSignNames()
For i = 0 To names.Count
 pdfSign.RemoveSignature((SignatureName)names[i], false)
Next i
pdfSign.Save(TestPath + "signed_removed.pdf")
```

### Ayrıca Bakınız

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)