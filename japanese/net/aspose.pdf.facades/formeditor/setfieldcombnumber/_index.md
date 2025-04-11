---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。combNumber パラメータの値に応じて、通常の単一行テキストフィールドを自動的に等間隔の位置またはコンバに分割するためのコンバの数を設定します。
type: docs
weight: 300
url: /ja/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber メソッド

通常の単一行テキストフィールドのコンバの数を設定します（フィールドは、combNumber パラメータの値に応じて、自動的に等間隔の位置またはコンバに分割されます）。

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 修飾されたフィールド名。 |
| combNumber | Int32 | フィールドを分割するコンバの数。 |

### 戻り値

成功した場合は true を返し、そうでない場合は false を返します。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)