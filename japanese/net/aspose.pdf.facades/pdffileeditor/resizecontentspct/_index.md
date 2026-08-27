---
title: "PdfFileEditor.ResizeContentsPct"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはパーセンテージで指定されます。"
type: docs
weight: 330
url: /ja/net/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## ResizeContentsPct(Stream, Stream, int[], double, double) {#resizecontentspct}

ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはパーセンテージで指定されます。

```csharp
public bool ResizeContentsPct(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | Stream | ソース ドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。null の場合、すべてのドキュメントページが処理されます。 |
| newWidth | Double | ページ内容の新しい幅（パーセンテージ）。 |
| newHeight | Double | ページ内容の新しい高さ（パーセンテージ）。 |

### 戻り値

リサイズが成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizePct(src, dest, 
//文書のすべてのページをリサイズします
null, 
//新しい内容の幅 = 初期サイズの 60%。
60, 
//新しい内容の高さ = 初期サイズの 60%。
60);
// ページの残りの領域は空白になります（ページ余白）。左右余白のサイズは (100% - 60%) / 2 = 20% です。
// 上下余白も同様です。
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContentsPct(string, string, int[], double, double) {#resizecontentspct_1}

ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはパーセンテージで指定されます。

```csharp
public bool ResizeContentsPct(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | String | ソース文書へのパスです。 |
| destination | String | 結果文書が保存されるパスです。 |
| pages | Int32[] | ページインデックスの配列。null の場合、すべてのドキュメントページが処理されます。 |
| newWidth | Double | ページ内容の新しい幅（パーセンテージ）。 |
| newHeight | Double | ページ内容の新しい高さ（パーセンテージ）。 |

### 戻り値

リサイズが成功した場合は true です。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizePct("input.pdf", "output.pdf",
//文書のすべてのページをリサイズします
null, 
//新しい内容の幅 = 初期サイズの 60%。
60, 
//新しい内容の高さ = 初期サイズの 60%。
60);
// ページの残りの領域は空白になります（ページ余白）。左右余白のサイズは (100% - 60%) / 2 = 20% です。
// 上下余白も同様です。
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


