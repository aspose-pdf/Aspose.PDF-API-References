---
title: "PdfFileSignature.RemoveSignature"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileSignature メソッド。署名の名前に基づいて署名を削除します。"
type: docs
weight: 250
url: /ja/net/aspose.pdf.facades/pdffilesignature/removesignature/
---
## RemoveSignature(SignatureName) {#removesignature}

署名名に基づいて署名を削除します。

```csharp
public void RemoveSignature(SignatureName signName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |

## 例

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

### 関連項目

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## RemoveSignature(SignatureName, bool) {#removesignature_1}

署名名に基づいて署名を削除します。

```csharp
public void RemoveSignature(SignatureName signName, bool removeField)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| signName | SignatureName | 署名の名前。 |
| removeField | Boolean | true に設定すると、署名とフィールドの両方がドキュメントから削除されます。false の場合は署名のみが削除されます。 |

## 例

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

### 関連項目

* class [SignatureName](../../signaturename/)
* class [PdfFileSignature](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


