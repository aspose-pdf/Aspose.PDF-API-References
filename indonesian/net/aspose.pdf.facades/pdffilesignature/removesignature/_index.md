---
title: "PdfFileSignature.RemoveSignature"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileSignature. Menghapus tanda tangan berdasarkan nama tanda tangan"
type: docs
weight: 250
url: /id/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(SignatureName) {#removesignature}

Menghapus tanda tangan berdasarkan nama tanda tangan.

```csharp
public void RemoveSignature(SignatureName signName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |

## Contoh

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

### Lihat Juga

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## RemoveSignature(SignatureName, bool) {#removesignature_1}

Menghapus tanda tangan berdasarkan nama tanda tangan.

```csharp
public void RemoveSignature(SignatureName signName, bool removeField)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| signName | SignatureName | Nama tanda tangan. |
| removeField | Boolean | Jika disetel ke true, maka menghapus baik tanda tangan maupun bidang dari dokumen; jika tidak, hanya tanda tangan. |

## Contoh

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

### Lihat Juga

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


