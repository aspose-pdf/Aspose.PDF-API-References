---
title: "PdfPageEditor.Save"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfPageEditor メソッド。変更されたドキュメントをファイルに保存します。"
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

変更された Document をファイルに保存します。

```csharp
public override void Save(string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | ドキュメントが保存されるファイルへのパス。 |

## 例

以下のサンプルは変更された PDF ドキュメントを保存する方法を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 関連項目

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

変更された Document をストリームに保存します。

```csharp
public override void Save(Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | 変更された PDF ドキュメントが保存されるストリーム。 |

## 例

以下のサンプルは変更された PDF ドキュメントをストリームに保存する方法を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 関連項目

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


