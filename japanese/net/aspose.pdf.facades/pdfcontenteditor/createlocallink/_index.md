---
title: PdfContentEditor.CreateLocalLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメントにローカルリンクを作成します。
type: docs
weight: 190
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

PDF ドキュメントにローカルリンクを作成します。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| desPage | Int32 | 目的のページ。 |
| originalPage | Int32 | ローカルリンクにバウンドされた矩形が作成される元のページの番号。 |
| clr | Color | アクティブクリック用の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行するのに対応するアクションの配列 (PredefinedAction 列挙型のメンバー)。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

PDF ドキュメントにローカルリンクを作成します。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| desPage | Int32 | 目的のページ。 |
| originalPage | Int32 | ローカルリンクにバウンドされた矩形が作成される元のページの番号。 |
| clr | Color | アクティブクリック用の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

PDF ドキュメントにローカルリンクを作成します。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| desPage | Int32 | 目的のページ。 |
| originalPage | Int32 | ローカルリンクにバウンドされた矩形が作成される元のページの番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)