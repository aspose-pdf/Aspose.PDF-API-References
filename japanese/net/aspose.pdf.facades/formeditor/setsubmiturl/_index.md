---
title: "FormEditor.SetSubmitUrl"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。ボタンの URL を設定します。"
type: docs
weight: 340
url: /ja/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

ボタンの URL を設定します。

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 送信ボタンの名前です。 |
| url | String | 完全修飾 URL です。 |

### 戻り値

ボタンの URL が正常に設定された場合は true です。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


