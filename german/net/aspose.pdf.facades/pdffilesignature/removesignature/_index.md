---
title: RemoveSignature
second_title: Aspose.PDF für .NET-API-Referenz
description: Entfernen Sie die Signatur gemäß dem Namen der Signatur.
type: docs
weight: 240
url: /de/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(string) {#removesignature}

Entfernen Sie die Signatur gemäß dem Namen der Signatur.

```csharp
public void RemoveSignature(string signName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signName | String | Der Name der Signatur. |

### Beispiele

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

### Siehe auch

* class [PdfFileSignature](../../pdffilesignature)
* namensraum [Aspose.Pdf.Facades](../../pdffilesignature)
* Montage [Aspose.PDF](../../../)

---

## RemoveSignature(string, bool) {#removesignature_1}

Entfernt die Signatur entsprechend dem Namen der Signatur.

```csharp
public void RemoveSignature(string signName, bool removeField)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signName | String | Der Name der Signatur. |
| removeField | Boolean | Wenn auf „true“ gesetzt, werden sowohl die Signatur als auch das Feld aus dem Dokument entfernt; ansonsten nur Unterschrift. |

### Beispiele

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

### Siehe auch

* class [PdfFileSignature](../../pdffilesignature)
* namensraum [Aspose.Pdf.Facades](../../pdffilesignature)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->