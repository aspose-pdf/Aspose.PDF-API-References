---
title: "FormEditor.Single2Multiple"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。単一行テキストフィールドを複数行テキストフィールドに変更します"
type: docs
weight: 350
url: /ja/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

単一行テキストフィールドを複数行テキストフィールドに変更します。

```csharp
public bool Single2Multiple(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名です。 |

### 戻り値

成功した場合は true を返し、そうでなければ false を返します。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


