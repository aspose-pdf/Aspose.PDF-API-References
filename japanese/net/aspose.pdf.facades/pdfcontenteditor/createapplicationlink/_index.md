---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメントでアプリケーションを起動するリンクを作成します。
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

PDF ドキュメントでアプリケーションを起動するリンクを作成します。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| application | String | 起動するアプリケーションのパス。 |
| page | Int32 | リンクにバウンドされた矩形が作成される元のページの番号。 |
| clr | Color | アクティブクリック用の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行することに対応するアクションの配列 (PredefinedAction 列挙型のメンバー)。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

PDF ドキュメントでアプリケーションを起動するリンクを作成します。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| application | String | 起動するアプリケーションのパス。 |
| page | Int32 | リンクにバウンドされた矩形が作成される元のページの番号。 |
| clr | Color | アクティブクリック用の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

PDF ドキュメントでアプリケーションを起動するリンクを作成します。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| application | String | 起動するアプリケーションのパス。 |
| page | Int32 | リンクにバウンドされた矩形が作成される元のページの番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)