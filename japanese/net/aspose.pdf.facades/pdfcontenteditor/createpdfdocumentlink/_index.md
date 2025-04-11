---
title: PdfContentEditor.CreatePdfDocumentLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。別の PDF ドキュメントページへのリンクを作成します。
type: docs
weight: 220
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## CreatePdfDocumentLink(Rectangle, string, int, int, Color, Enum[]) {#createpdfdocumentlink_2}

別の PDF ドキュメントページへのリンクを作成します。

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| remotePdf | String | 開かれる PDF ドキュメント。 |
| originalPage | Int32 | リンクにバウンドされた矩形が作成される元のページの番号。 |
| destinationPage | Int32 | 目的のページ。 |
| clr | Color | アクティブクリック用の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行するのに対応するアクションの配列 (PredefinedAction 列挙型のメンバー)。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

別の PDF ドキュメントページへのリンクを作成します。

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| remotePdf | String | 開かれる PDF ドキュメント。 |
| originalPage | Int32 | リンクにバウンドされた矩形が作成される元のページの番号。 |
| destinationPage | Int32 | 目的のページ。 |
| clr | Color | アクティブクリック用の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

別の PDF ドキュメントページへのリンクを作成します。

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| remotePdf | String | 開かれる PDF ドキュメント。 |
| originalPage | Int32 | リンクにバウンドされた矩形が作成される元のページの番号。 |
| destinationPage | Int32 | 目的のページ。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)