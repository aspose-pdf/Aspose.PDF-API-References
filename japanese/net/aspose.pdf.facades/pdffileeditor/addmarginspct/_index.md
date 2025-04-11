---
title: PdfFileEditor.AddMarginsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。ページの内容をリサイズし、指定されたマージンを追加します。マージンは初期ページサイズのパーセントで指定されます。
type: docs
weight: 230
url: /ja/net/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## AddMarginsPct(Stream, Stream, int[], double, double, double, double) {#addmarginspct}

ページの内容をリサイズし、指定されたマージンを追加します。マージンは初期ページサイズのパーセントで指定されます。

```csharp
public bool AddMarginsPct(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | Stream | ソースドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。nullの場合はすべてのドキュメントページが処理されます。 |
| leftMargin | Double | 初期ページサイズのパーセントで指定された左マージン。 |
| rightMargin | Double | 初期ページサイズのパーセントで指定された右マージン。 |
| topMargin | Double | 初期ページサイズのパーセントで指定された上マージン。 |
| bottomMargin | Double | 初期ページサイズのパーセントで指定された下マージン。 |

### 戻り値

アクションが成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMarginsPct(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
    dest.Close();
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddMarginsPct(string, string, int[], double, double, double, double) {#addmarginspct_1}

ページの内容をリサイズし、指定されたマージンを追加します。マージンは初期ページサイズのパーセントで指定されます。

```csharp
public bool AddMarginsPct(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | String | ソースドキュメントへのパス。 |
| destination | String | 結果のドキュメントが保存されるパス。 |
| pages | Int32[] | ページインデックスの配列。nullの場合はすべてのドキュメントページが処理されます。 |
| leftMargin | Double | 初期ページサイズのパーセントで指定された左マージン。 |
| rightMargin | Double | 初期ページサイズのパーセントで指定された右マージン。 |
| topMargin | Double | 初期ページサイズのパーセントで指定された上マージン。 |
| bottomMargin | Double | 初期ページサイズのパーセントで指定された下マージン。 |

### 戻り値

リサイズが成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMarginsPct("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 15% of page width 
    15, 
    //right margin is 10% of page width
    10, 
    //top margin is 20% of page width
    20, 
    //bottom margin is 5% of page width
    5);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)