---
title: PdfFileEditor.ResizeContentsPct
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。ドキュメントページの内容をリサイズします。ページの内容を縮小し、マージンを追加します。新しい内容のサイズはパーセントで指定されます。
type: docs
weight: 330
url: /ja/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

ドキュメントページの内容をリサイズします。ページの内容を縮小し、マージンを追加します。新しい内容のサイズはパーセントで指定されます。

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | Stream | ソースドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。nullの場合はすべてのドキュメントページが処理されます。 |
| newWidth | Double | ページ内容の新しい幅（パーセント）。 |
| newHeight | Double | ページ内容の新しい高さ（パーセント）。 |

### 戻り値

リサイズが成功した場合はtrue。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

ドキュメントページの内容をリサイズします。ページの内容を縮小し、マージンを追加します。新しい内容のサイズはパーセントで指定されます。

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | String | ソースドキュメントへのパス。 |
| destination | String | 結果のドキュメントが保存されるパス。 |
| pages | Int32[] | ページインデックスの配列。nullの場合はすべてのドキュメントページが処理されます。 |
| newWidth | Double | ページ内容の新しい幅（パーセント）。 |
| newHeight | Double | ページ内容の新しい高さ（パーセント）。 |

### 戻り値

リサイズが成功した場合はtrue。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//resize all pages of document
null, 
//new contents width = 60% of initial size
60, 
//new contents height = 60% of initial size
60);
// Rest area of page will be empty (page margins).  Size of left and right margins is (100% - 60%) / 2 = 20%
// The same for top and bottom margins.
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)