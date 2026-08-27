---
title: "FormEditor.CopyOuterField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。既存のフィールドを元のページ番号と座標を保持したまま、ある PDF document から別の document へコピーします。注意: ラジオボックスを除く AcroForm フィールドのみ対象です。"
type: docs
weight: 160
url: /ja/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

既存のフィールドを、元のページ番号と座標を保持したまま、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールド（ラジオボックスを除く）のみ対象です。

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcFileName | String | コピー対象のフィールドを含む PDF document の名前。 |
| fieldName | String | 元の完全修飾フィールド名。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//source.pdf から PdfForm.pdf へテキストフィールドをコピーします。
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

既存のフィールドを、指定されたページ番号と元の座標で、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールド（ラジオボックスを除く）のみ対象です。

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcFileName | String | コピー対象のフィールドを含む PDF document の名前。 |
| fieldName | String | 元の完全修飾フィールド名。 |
| pageNum | Int32 | 新しいフィールドを保持する page の番号。-1 の場合、新しいフィールドは元の page と同じ page にコピーされます。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

既存のフィールドを、指定されたページ番号と座標で、ある PDF ドキュメントから別のドキュメントへコピーします。注意: AcroForm フィールド（ラジオボックスを除く）のみ対象です。

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcFileName | String | コピー対象のフィールドを含む PDF document の名前。 |
| fieldName | String | 元の完全修飾フィールド名。 |
| pageNum | Int32 | 新しいフィールドを保持する page の番号。-1 の場合、新しいフィールドは元の page と同じ page にコピーされます。 |
| 横座標 | Single | 新しいフィールドの横座標。-1 の場合、横座標は元のものと同じになります。 |
| 縦座標 | Single | 新しいフィールドの縦座標です。-1 の場合、縦座標は元のものと同じになります。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


