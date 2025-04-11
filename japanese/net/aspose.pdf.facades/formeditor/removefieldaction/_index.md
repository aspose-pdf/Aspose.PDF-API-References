---
title: FormEditor.RemoveFieldAction
second_title: Aspose.PDF for .NET API Reference
description: FormEditorメソッド。フィールドの送信アクションを削除します。
type: docs
weight: 220
url: /ja/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldActionメソッド

フィールドの送信アクションを削除します。

```csharp
public void RemoveFieldAction(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | フィールドの名前。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### 関連項目

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)