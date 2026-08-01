---
title: "FormEditor.AddSubmitBtn"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "FormEditor メソッド。フォームに送信ボタンを追加します"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

フォームに送信ボタンを追加します。

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 新しいボタンの名前。 |
| ページ | Int32 | ボタンが配置されるページ。 |
| label | String | ボタンのキャプション。 |
| url | String | 送信ボタンの URL。 |
| llx | Single | 左下隅の横座標。 |
| lly | Single | 左下隅の縦座標。 |
| urx | Single | 右上隅の横座標。 |
| ury | Single | 右上隅の縦座標。 |

## 例

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### 関連項目

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


