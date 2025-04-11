---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。指定されたページ番号の同じ位置に既存のフィールドをコピーします。新しいドキュメントが生成され、ソースドキュメントにあるすべての内容が含まれますが、新しくコピーされたフィールドは含まれません。
type: docs
weight: 150
url: /ja/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

指定されたページ番号の同じ位置に既存のフィールドをコピーします。新しいドキュメントが生成され、ソースドキュメントにあるすべての内容が含まれますが、新しくコピーされたフィールドは含まれません。

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 古い完全修飾フィールド名。 |
| newFieldName | String | 新しい完全修飾フィールド名。nullの場合、fieldName + "~"として設定されます。 |
| pageNum | Int32 | 新しいフィールドを保持するページ番号。-1の場合、新しいフィールドは古いフィールドがホストされているのと同じページにコピーされます。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### 参照

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

ページ番号と座標によって指定された新しい位置に既存のフィールドをコピーします。新しいドキュメントが生成され、ソースドキュメントにあるすべての内容が含まれますが、新しくコピーされたフィールドは含まれません。

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 古い完全修飾フィールド名。 |
| newFieldName | String | 新しい完全修飾フィールド名。nullの場合、fieldName + "~"として設定されます。 |
| pageNum | Int32 | 新しいフィールドを保持するページ番号。-1の場合、新しいフィールドは古いフィールドがホストされているのと同じページにコピーされます。 |
| abscissa | Single | 新しいフィールドの横座標。-1の場合、横座標は元のものと等しくなります。 |
| ordinate | Single | 新しいフィールドの縦座標。-1の場合、縦座標は元のものと等しくなります。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### 参照

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)