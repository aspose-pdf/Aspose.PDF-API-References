---
title: PdfContentEditor.CreateWebLink
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。PDF ドキュメントにウェブリンクを作成します。
type: docs
weight: 300
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

PDF ドキュメントにウェブリンクを作成します。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| url | String | ウェブリンクの宛先。 |
| originalPage | Int32 | ウェブリンクにバウンドされた矩形が作成される元のページの番号。 |
| clr | Color | アクティブクリック用の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行するのに対応するアクションの配列 (PredefinedAction 列挙型のメンバー)。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

PDF ドキュメントにウェブリンクを作成します。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| url | String | ウェブリンクの宛先。 |
| originalPage | Int32 | ウェブリンクにバウンドされた矩形が作成される元のページの番号。 |
| clr | Color | アクティブクリック用の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

PDF ドキュメントにウェブリンクを作成します。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | アクティブクリック用の矩形。 |
| url | String | ウェブリンクの宛先。 |
| originalPage | Int32 | ウェブリンクにバウンドされた矩形が作成される元のページの番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)