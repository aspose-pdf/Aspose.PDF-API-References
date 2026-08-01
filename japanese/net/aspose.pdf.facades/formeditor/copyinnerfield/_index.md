---
title: "FormEditor.CopyInnerField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。指定されたページ番号の同じ位置に既存のフィールドをコピーします。新しいドキュメントが生成され、元のドキュメントが持つすべての内容を含みますが、新しくコピーされたフィールドは除外されます。"
type: docs
weight: 150
url: /ja/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

既存のフィールドを指定されたページ番号の同じ位置にコピーします。新しいドキュメントが生成され、元のドキュメントのすべての内容が含まれますが、新しくコピーされたフィールドは除外されます。

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 古い完全修飾フィールド名。 |
| newFieldName | String | 新しい完全修飾フィールド名。null の場合、fieldName + "~" と設定されます。 |
| pageNum | Int32 | 新しいフィールドを保持する page の番号。-1 の場合、新しいフィールドは元の page と同じ page にコピーされます。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//2ページ目にテキストフィールドのコピーを作成します。
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

既存のフィールドをページ番号と座標の両方で指定された新しい位置にコピーします。新しいドキュメントが生成され、元のドキュメントのすべての内容が含まれますが、新しくコピーされたフィールドは除外されます。

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 古い完全修飾フィールド名。 |
| newFieldName | String | 新しい完全修飾フィールド名。null の場合、fieldName + "~" と設定されます。 |
| pageNum | Int32 | 新しいフィールドを保持する page の番号。-1 の場合、新しいフィールドは元の page と同じ page にコピーされます。 |
| 横座標 | Single | 新しいフィールドの横座標。-1 の場合、横座標は元のものと同じになります。 |
| 縦座標 | Single | 新しいフィールドの縦座標です。-1 の場合、縦座標は元のものと同じになります。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//2ページ目にテキストフィールドのコピーを作成します。
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


