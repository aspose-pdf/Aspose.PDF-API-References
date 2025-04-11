---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。単一行のテキストフィールドを複数行のものに変更します
type: docs
weight: 350
url: /ja/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple メソッド

単一行のテキストフィールドを複数行のものに変更します。

```csharp
public bool Single2Multiple(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 修飾されたフィールド名。 |

### 戻り値

成功した場合は true を返し、そうでない場合は false を返します。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)