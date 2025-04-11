---
title: PdfFileEditor.TryResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。ドキュメントのページの内容をリサイズします
type: docs
weight: 450
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

ドキュメントのページの内容をリサイズします。ページが縮小されると、ページの周りに空白のマージンが追加されます。結果は HttpResponse オブジェクトに保存されます。

```csharp
public bool TryResizeContents(string source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | String | ソースファイルへのパス。 |
| pages | Int32[] | リサイズするページの配列。 |
| parameters | ContentsResizeParameters | リサイズパラメータ。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryResizeContents メソッドは ResizeContents メソッドに似ていますが、TryResizeContents メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, int[], ContentsResizeParameters, HttpResponse) {#tryresizecontents}

ドキュメントのページの内容をリサイズします。ページが縮小されると、ページの周りに空白のマージンが追加されます。結果は HttpResponse オブジェクトに保存されます。

```csharp
public bool TryResizeContents(Stream source, int[] pages, ContentsResizeParameters parameters, 
    HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | Stream | ソースファイルのストリーム。 |
| pages | Int32[] | リサイズするページの配列。 |
| parameters | ContentsResizeParameters | リサイズパラメータ。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryResizeContents メソッドは ResizeContents メソッドに似ていますが、TryResizeContents メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents_1}

ドキュメントのページの内容をリサイズします。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | Stream | ソースドキュメントのストリーム。 |
| destination | Stream | 目的のドキュメントのストリーム。 |
| pages | Int32[] | ページインデックスの配列。 |
| parameters | ContentsResizeParameters | リサイズパラメータ。 |

### 戻り値

成功した場合は true を返します。

## 備考

TryResizeContents メソッドは ResizeContents メソッドに似ていますが、TryResizeContents メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents(src, dest, new int[] { 1, 2, 3 }, parameters);
dest.Close();
```

### 関連項目

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(Stream, Stream, int[], double, double) {#tryresizecontents_1}

ドキュメントページの内容をリサイズします。ページの内容を縮小し、マージンを追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | Stream | ソースドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。null の場合はすべてのドキュメントページが処理されます。 |
| newWidth | Double | デフォルトの空間単位でのページ内容の新しい幅。 |
| newHeight | Double | デフォルトの空間単位でのページ内容の新しい高さ。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryResizeContents メソッドは ResizeContents メソッドに似ていますが、TryResizeContents メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

ドキュメントのページの内容をリサイズします。ページが縮小されると、ページの周りに空白のマージンが追加されます。

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| source | String | ソースドキュメントのパス。 |
| destination | String | 目的のドキュメントのパス。 |
| pages | Int32[] | ページインデックスの配列（ページインデックスは 1 から始まります）。 |
| parameters | ContentsResizeParameters | ページリサイズのパラメータ。 |

### 戻り値

リサイズが成功した場合は true。

## 備考

TryResizeContents メソッドは ResizeContents メソッドに似ていますが、TryResizeContents メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //left margin = 10% of page width
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents width calculated automatically as width - left margin - right margin (100% - 10% - 10% = 80%)
    null,
    //right margin is 10% of page 
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //top margin = 10% of height
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //new contents height is calculated automatically (similar to width)
    null,
    //bottom margin is 10%
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### 関連項目

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)