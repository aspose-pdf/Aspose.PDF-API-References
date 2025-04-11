---
title: FormEditor.RenameField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。フィールドの名前を変更します。
type: docs
weight: 230
url: /ja/net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField メソッド

フィールドの名前を変更します。

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | フィールドの旧名。 |
| newFieldName | String | フィールドの新名。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)