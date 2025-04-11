---
title: PdfContentEditor.AddDocumentAdditionalAction
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。ドキュメントイベントの追加アクションを追加します。
type: docs
weight: 60
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/adddocumentadditionalaction/
---
## PdfContentEditor.AddDocumentAdditionalAction メソッド

ドキュメントイベントの追加アクションを追加します。

```csharp
public void AddDocumentAdditionalAction(string eventType, string code)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| eventType | String | ドキュメントイベントの種類。 |
| code | String | JavaScript のコード。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAdditionalAction(PdfContentEditor.DocumentClose, "app.alert('Good-bye!');");
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)