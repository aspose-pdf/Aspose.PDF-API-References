---
title: "FormEditor.SetFieldCombNumber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。通常の単一行テキストフィールドのコンブ数を設定します。フィールドは combNumber パラメータの値に応じて、等間隔の位置（コンブ）に自動的に分割されます。"
type: docs
weight: 300
url: /ja/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

通常の単一行テキストフィールドのコンブ数を設定します（フィールドは combNumber パラメータの値に応じて、同じ間隔の位置（コンブ）に自動的に分割されます）。

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名です。 |
| combNumber | Int32 | フィールドを分割するコンブの数です。 |

### 戻り値

成功した場合は true を返し、そうでなければ false を返します。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


