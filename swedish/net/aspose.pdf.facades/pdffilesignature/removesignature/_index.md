---
title: "PdfFileSignature.RemoveSignature"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileSignature-metod. Tar bort signaturen enligt signaturens namn"
type: docs
weight: 250
url: /sv/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(SignatureName) {#removesignature}

Ta bort signaturen enligt signaturens namn.

```csharp
public void RemoveSignature(SignatureName signName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |

## Exempel

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

### Se även

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## RemoveSignature(SignatureName, bool) {#removesignature_1}

Tar bort signaturen enligt signaturens namn.

```csharp
public void RemoveSignature(SignatureName signName, bool removeField)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| signName | SignatureName | Namnet på signaturen. |
| removeField | Boolean | Om satt till true tas både signatur och fält bort från dokumentet; annars tas endast signaturen bort. |

## Exempel

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

### Se även

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


