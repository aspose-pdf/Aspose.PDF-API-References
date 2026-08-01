---
title: "PdfFileEditor.AddMarginsPct"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。ページ内容のサイズを変更し、指定された余白を追加します。余白は初期ページサイズのパーセンテージで指定されます。"
type: docs
weight: 230
url: /ja/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

ページ内容のサイズを変更し、指定された余白を追加します。余白は初期ページサイズのパーセンテージで指定されます。

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | Stream | ソース ドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。null の場合、すべてのドキュメントページが処理されます。 |
| leftMargin | Double | 左余白は初期ページサイズのパーセンテージで指定されます。 |
| rightMargin | Double | 右余白は初期ページサイズのパーセンテージで指定されます。 |
| topMargin | Double | 上余白は初期ページサイズのパーセンテージで指定されます。 |
| bottomMargin | Double | 下余白は初期ページサイズのパーセンテージで指定されます。 |

### 戻り値

アクションが正常に実行された場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //ページ 1, 2, 3 を処理する。
    new int[] { 1, 2, 3}, 
    //左余白はページ幅の 15% です。
    15, 
    //右余白はページ幅の 10% です。
    10, 
    //上余白はページ幅の 20% です。
    20, 
    //下余白はページ幅の 5% です。
    5);
    dest.Close();
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

ページ内容のサイズを変更し、指定された余白を追加します。余白は初期ページサイズのパーセンテージで指定されます。

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | String | ソース文書へのパスです。 |
| destination | String | 結果文書が保存されるパスです。 |
| pages | Int32[] | ページインデックスの配列。null の場合、すべてのドキュメントページが処理されます。 |
| leftMargin | Double | 左余白は初期ページサイズのパーセンテージで指定されます。 |
| rightMargin | Double | 右余白は初期ページサイズのパーセンテージで指定されます。 |
| topMargin | Double | 上余白は初期ページサイズのパーセンテージで指定されます。 |
| bottomMargin | Double | 下余白は初期ページサイズのパーセンテージで指定されます。 |

### 戻り値

サイズ変更が成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //ページ 1, 2, 3 を処理する。
    new int[] { 1, 2, 3}, 
    //左余白はページ幅の 15% です。
    15, 
    //右余白はページ幅の 10% です。
    10, 
    //上余白はページ幅の 20% です。
    20, 
    //下余白はページ幅の 5% です。
    5);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


