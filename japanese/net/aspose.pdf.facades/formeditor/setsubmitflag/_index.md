---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: FormEditor メソッド。送信ボタンの送信フラグを設定します。
type: docs
weight: 330
url: /ja/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag メソッド

送信ボタンの送信フラグを設定します。

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 送信ボタンの名前。 |
| submitFormFlag | SubmitFormFlag | 送信フラグ。 |

### 戻り値

フィールドが見つかり、送信フラグが正常に設定された場合は true。

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