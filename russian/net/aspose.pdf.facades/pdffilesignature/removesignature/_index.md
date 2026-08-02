---
title: "PdfFileSignature.RemoveSignature"
second_title: "Справочник API Aspose.PDF для .NET"
description: "PdfFileSignature метод. Удаляет подпись по её имени."
type: docs
weight: 250
url: /ru/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(SignatureName) {#removesignature}

Удаляет подпись по её имени.

```csharp
public void RemoveSignature(SignatureName signName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | SignatureName | Имя подписи. |

## Примеры

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

### См. также

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## RemoveSignature(SignatureName, bool) {#removesignature_1}

Удаляет подпись по её имени.

```csharp
public void RemoveSignature(SignatureName signName, bool removeField)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | SignatureName | Имя подписи. |
| removeField | Boolean | Если установлено в true, удаляет как подпись, так и поле из документа; иначе удаляется только подпись. |

## Примеры

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

### См. также

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


