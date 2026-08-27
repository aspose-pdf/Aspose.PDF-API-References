---
title: "Form.GetSubmitFlags"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。送信ボタンの送信フラグを返します。"
type: docs
weight: 270
url: /ja/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags method

送信ボタンの送信フラグを返します。

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名です。 |

### 戻り値

ボタンの送信フラグです。

## 例

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### 関連項目

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


