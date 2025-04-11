---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。既存のフィールドを1つのPDFドキュメントから別のドキュメントに、元のページ番号と座標でコピーします。注意: ラジオボックスを除くAcroFormフィールドのみ対象です。
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

既存のフィールドを1つのPDFドキュメントから別のドキュメントに、元のページ番号と座標でコピーします。注意: AcroFormフィールドのみ対象です（ラジオボックスを除く）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcFileName | String | コピーするフィールドを含むPDFドキュメントの名前。 |
| fieldName | String | 元の完全修飾フィールド名。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### 関連項目

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

既存のフィールドを1つのPDFドキュメントから別のドキュメントに、指定されたページ番号と元の座標でコピーします。注意: AcroFormフィールドのみ対象です（ラジオボックスを除く）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcFileName | String | コピーするフィールドを含むPDFドキュメントの名前。 |
| fieldName | String | 元の完全修飾フィールド名。 |
| pageNum | Int32 | 新しいフィールドを保持するページの番号。-1の場合、新しいフィールドは古いフィールドがホストされているのと同じページにコピーされます。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### 関連項目

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

既存のフィールドを1つのPDFドキュメントから別のドキュメントに、指定されたページ番号と座標でコピーします。注意: AcroFormフィールドのみ対象です（ラジオボックスを除く）。

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcFileName | String | コピーするフィールドを含むPDFドキュメントの名前。 |
| fieldName | String | 元の完全修飾フィールド名。 |
| pageNum | Int32 | 新しいフィールドを保持するページの番号。-1の場合、新しいフィールドは古いフィールドがホストされているのと同じページにコピーされます。 |
| abscissa | Single | 新しいフィールドの横座標。-1の場合、横座標は元のものと等しくなります。 |
| ordinate | Single | 新しいフィールドの縦座標。-1の場合、縦座標は元のものと等しくなります。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### 関連項目

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)