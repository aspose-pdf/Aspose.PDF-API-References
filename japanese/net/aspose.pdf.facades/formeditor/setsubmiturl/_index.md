---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: FormEditorメソッド。ボタンのURLを設定します。
type: docs
weight: 340
url: /ja/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrlメソッド

ボタンのURLを設定します。

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 送信ボタンの名前。 |
| url | String | 完全修飾URL。 |

### 戻り値

ボタンのURLが正常に設定された場合はtrue。

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### 参照

* クラス [FormEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)