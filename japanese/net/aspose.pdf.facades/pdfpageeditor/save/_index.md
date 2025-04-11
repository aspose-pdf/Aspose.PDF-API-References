---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: PdfPageEditor メソッド。変更されたドキュメントをファイルに保存します
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

変更されたドキュメントをファイルに保存します。

```csharp
public override void Save(string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | ドキュメントが保存されるファイルへのパス。 |

## 例

以下のサンプルは、変更されたPDFドキュメントを保存する方法を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 関連項目

* クラス [PdfPageEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

変更されたドキュメントをストリームに保存します。

```csharp
public override void Save(Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | 変更されたPDFドキュメントが保存されるストリーム。 |

## 例

以下のサンプルは、変更されたPDFドキュメントをストリームに保存する方法を示しています。

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 関連項目

* クラス [PdfPageEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)