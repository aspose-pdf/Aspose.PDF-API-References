---
title: "PdfFileSignature.RemoveSignature"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSignature. إزالة التوقيع وفقًا لاسم التوقيع"
type: docs
weight: 250
url: /ar/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(SignatureName) {#removesignature}

إزالة التوقيع وفقًا لاسم التوقيع.

```csharp
public void RemoveSignature(SignatureName signName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |

## أمثلة

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

### انظر أيضًا

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## RemoveSignature(SignatureName, bool) {#removesignature_1}

يزيل التوقيع وفقًا لاسم التوقيع.

```csharp
public void RemoveSignature(SignatureName signName, bool removeField)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| signName | SignatureName | اسم التوقيع. |
| removeField | Boolean | إذا تم تعيينه إلى true، فإنه يزيل كلًا من التوقيع والحقل من المستند؛ وإلا، يزيل التوقيع فقط. |

## أمثلة

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

### انظر أيضًا

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


