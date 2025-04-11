---
title: PdfFileEditor.AddMargins
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。ページの内容をサイズ変更し、指定されたマージンを追加します。マージンはデフォルトの空間単位で指定されます。
type: docs
weight: 220
url: /ja/net/aspose.pdf.facades/pdffileeditor/addmargins/
---
## AddMargins(Stream, Stream, int[], double, double, double, double) {#addmargins}

ページの内容をサイズ変更し、指定されたマージンを追加します。マージンはデフォルトの空間単位で指定されます。

```csharp
public bool AddMargins(Stream source, Stream destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | Stream | ソースドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。nullの場合、すべてのドキュメントページが処理されます。 |
| leftMargin | Double | 左マージン。 |
| rightMargin | Double | 右マージン。 |
| topMargin | Double | 上マージン。 |
| bottomMargin | Double | 下マージン。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.AddMargins(src, dest, 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
    dest.Close();
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddMargins(string, string, int[], double, double, double, double) {#addmargins_1}

ページの内容をサイズ変更し、指定されたマージンを追加します。マージンはデフォルトの空間単位で指定されます。

```csharp
public bool AddMargins(string source, string destination, int[] pages, double leftMargin, 
    double rightMargin, double topMargin, double bottomMargin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | String | ソースドキュメントへのパス。 |
| destination | String | 結果のドキュメントが保存されるパス。 |
| pages | Int32[] | ページインデックスの配列。nullの場合、すべてのドキュメントページが処理されます。 |
| leftMargin | Double | 左マージン。 |
| rightMargin | Double | 右マージン。 |
| topMargin | Double | 上マージン。 |
| bottomMargin | Double | 下マージン。 |

### 戻り値

サイズ変更が成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.AddMargins("input.pdf", "output.pdf", 
    //process pages 1, 2, 3
    new int[] { 1, 2, 3}, 
    //left margin is 10 units
    10, 
    //right margin is 5 units
    5, 
    //top margin is 5 units
    5, 
    //bottom margin is 5 units
    5);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)