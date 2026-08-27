---
title: "PdfContentEditor.CreateApplicationLink"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF ドキュメントでアプリケーションを起動するリンクを作成します。"
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

PDF ドキュメント内でアプリケーションを起動するリンクを作成します。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| アプリケーション | String | 起動するアプリケーションのパスです。 |
| ページ | Int32 | リンクでバインドされた矩形が作成される元のページ番号。 |
| clr | Color | クリック可能な領域の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行することに対応するアクションの配列（PredefinedAction enum のメンバー）。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

PDF ドキュメント内でアプリケーションを起動するリンクを作成します。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| アプリケーション | String | 起動するアプリケーションのパスです。 |
| ページ | Int32 | リンクでバインドされた矩形が作成される元のページ番号。 |
| clr | Color | クリック可能な領域の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

PDF ドキュメント内でアプリケーションを起動するリンクを作成します。

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| アプリケーション | String | 起動するアプリケーションのパスです。 |
| ページ | Int32 | リンクでバインドされた矩形が作成される元のページ番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


