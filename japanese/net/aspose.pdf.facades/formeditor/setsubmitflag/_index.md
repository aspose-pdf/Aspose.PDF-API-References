---
title: "FormEditor.SetSubmitFlag"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。送信ボタンの submit フラグを設定します。"
type: docs
weight: 330
url: /ja/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

送信ボタンの submit フラグを設定します。

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 送信ボタンの名前です。 |
| submitFormFlag | SubmitFormFlag | Submit フラグです。 |

### 戻り値

フィールドが見つかり、submit フラグが正常に設定された場合は true です。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### 関連項目

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


