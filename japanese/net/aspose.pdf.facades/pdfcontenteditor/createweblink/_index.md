---
title: "PdfContentEditor.CreateWebLink"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。PDF ドキュメントにウェブリンクを作成します。"
type: docs
weight: 300
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

PDFドキュメントにウェブリンクを作成します。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| url | String | ウェブリンクの宛先。 |
| originalPage | Int32 | ウェブリンクにバインドされた矩形が作成される元のページ番号。 |
| clr | Color | クリック可能な領域の矩形の色。 |
| actionName | Enum[] | Acrobat ビューアでメニュー項目を実行することに対応するアクションの配列（PredefinedAction enum のメンバー）。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

PDFドキュメントにウェブリンクを作成します。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| url | String | ウェブリンクの宛先。 |
| originalPage | Int32 | ウェブリンクでバインドされた矩形が作成される元ページの番号。 |
| clr | Color | クリック可能な領域の矩形の色。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

PDFドキュメントにウェブリンクを作成します。

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | クリック可能な領域の矩形。 |
| url | String | ウェブリンクの宛先。 |
| originalPage | Int32 | ウェブリンクでバインドされた矩形が作成される元ページの番号。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


