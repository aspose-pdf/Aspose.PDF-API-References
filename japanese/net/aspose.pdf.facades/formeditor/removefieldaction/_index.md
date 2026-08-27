---
title: "FormEditor.RemoveFieldAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。フィールドの送信アクションを削除します。"
type: docs
weight: 220
url: /ja/net/aspose.pdf.facades/formeditor/removefieldaction/
---
## FormEditor.RemoveFieldAction method

フィールドの送信アクションを削除します。

```csharp
public void RemoveFieldAction(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | フィールドの名前。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


