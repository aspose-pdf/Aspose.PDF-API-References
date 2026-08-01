---
title: "PdfContentEditor.CreateLocalLink"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF ドキュメントにローカルリンクを作成します。"
type: docs
weight: 190
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createlocallink/
---
## CreateLocalLink(Rectangle, int, int, Color, Enum[]) {#createlocallink_2}

PDF ドキュメント内にローカルリンクを作成します。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr, 
    Enum[] actionName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| desPage | Int32 | 宛先ページ。 |
| originalPage | Int32 | ローカルリンクでバインドされた矩形が作成される元ページの番号。 |
| clr | Color | クリック可能な領域の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行することに対応するアクションの配列（PredefinedAction enum のメンバー）。 |

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

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int, Color) {#createlocallink_1}

PDF ドキュメント内にローカルリンクを作成します。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage, Color clr)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| desPage | Int32 | 宛先ページ。 |
| originalPage | Int32 | ローカルリンクでバインドされた矩形が作成される元ページの番号。 |
| clr | Color | クリック可能な領域の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    2, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateLocalLink(Rectangle, int, int) {#createlocallink}

PDF ドキュメント内にローカルリンクを作成します。

```csharp
public void CreateLocalLink(Rectangle rect, int desPage, int originalPage)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| desPage | Int32 | 宛先ページ。 |
| originalPage | Int32 | ローカルリンクでバインドされた矩形が作成される元ページの番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLocalLink(new System.Drawing.Rectangle(0, 0, 100, 100), 2, 1});
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


