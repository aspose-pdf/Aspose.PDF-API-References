---
title: "PdfContentEditor.AddDocumentAdditionalAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。ドキュメントイベントの追加アクションを追加します"
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction method

ドキュメントイベントに対して追加のアクションを追加します。

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| eventType | String | ドキュメントイベントの種類。 |
| コード | String | JavaScript のコード。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


