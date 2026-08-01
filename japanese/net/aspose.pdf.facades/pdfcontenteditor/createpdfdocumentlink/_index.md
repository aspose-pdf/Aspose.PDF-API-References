---
title: "PdfContentEditor.CreatePdfDocumentLink"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。別の PDF ドキュメントページへのリンクを作成します"
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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| remotePdf | String | 開かれるページを含む PDF ドキュメント。 |
| originalPage | Int32 | リンクでバインドされた矩形が作成される元のページ番号。 |
| destinationPage | Int32 | 宛先ページ。 |
| clr | Color | クリック可能な領域の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行することに対応するアクションの配列（PredefinedAction enum のメンバー）。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

別の PDF ドキュメントページへのリンクを作成します。

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| remotePdf | String | 開かれるページを含む PDF ドキュメント。 |
| originalPage | Int32 | リンクでバインドされた矩形が作成される元のページ番号。 |
| destinationPage | Int32 | 宛先ページ。 |
| clr | Color | クリック可能な領域の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

別の PDF ドキュメントページへのリンクを作成します。

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| remotePdf | String | 開かれるページを含む PDF ドキュメント。 |
| originalPage | Int32 | リンクでバインドされた矩形が作成される元のページ番号。 |
| destinationPage | Int32 | 宛先ページ。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


