---
title: PdfFileSignature.RemoveSignature
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSignature-Methode. Entfernen Sie die Signatur gemäß dem Namen der Signatur
type: docs
weight: 250
url: /de/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(SignatureName) {#removesignature}

Entfernen Sie die Signatur gemäß dem Namen der Signatur.

```csharp
public void RemoveSignature(SignatureName signName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signName | SignatureName | Der Name der Signatur. |

## Beispiele

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

### Siehe auch

* Klasse [SignatureName](../../signaturename/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)

---

## RemoveSignature(SignatureName, bool) {#removesignature_1}

Entfernt die Signatur gemäß dem Namen der Signatur.

```csharp
public void RemoveSignature(SignatureName signName, bool removeField)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signName | SignatureName | Der Name der Signatur. |
| removeField | Boolean | Wenn auf true gesetzt, entfernt es sowohl die Signatur als auch das Feld aus dem Dokument; andernfalls nur die Signatur. |

## Beispiele

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

### Siehe auch

* Klasse [SignatureName](../../signaturename/)
* Klasse [PdfFileSignature](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)