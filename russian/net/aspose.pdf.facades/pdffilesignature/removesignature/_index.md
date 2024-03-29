---
title: RemoveSignature
second_title: Aspose.PDF для справочника API .NET
description: Удалить подпись по названию подписи.
type: docs
weight: 240
url: /ru/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(string) {#removesignature}

Удалить подпись по названию подписи.

```csharp
public void RemoveSignature(string signName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | String | Название подписи. |

### Примеры

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

### Смотрите также

* class [PdfFileSignature](../../pdffilesignature)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesignature)
* сборка [Aspose.PDF](../../../)

---

## RemoveSignature(string, bool) {#removesignature_1}

Удаляет подпись по имени подписи.

```csharp
public void RemoveSignature(string signName, bool removeField)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| signName | String | Название подписи. |
| removeField | Boolean | Если установлено значение true, то из документа удаляются и подпись, и поле; в противном случае только подпись. |

### Примеры

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

### Смотрите также

* class [PdfFileSignature](../../pdffilesignature)
* пространство имен [Aspose.Pdf.Facades](../../pdffilesignature)
* сборка [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
