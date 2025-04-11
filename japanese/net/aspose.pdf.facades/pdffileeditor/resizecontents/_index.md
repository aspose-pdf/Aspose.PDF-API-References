---
title: PdfFileEditor.ResizeContents
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。ドキュメントのページの内容をリサイズします
type: docs
weight: 320
url: /ja/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

ドキュメントのページの内容をリサイズします。

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | Stream | ソースドキュメントを含むストリーム。 |
| destination | Stream | 目的のドキュメントを含むストリーム。 |
| pages | Int32[] | ページインデックスの配列。 |
| parameters | ContentsResizeParameters | リサイズパラメーター。 |

### 戻り値

成功した場合は true を返します。

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
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### 参照

* クラス [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

ドキュメントページの内容をリサイズします。ページの内容を縮小し、マージンを追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | Stream | ソースドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。nullの場合はすべてのドキュメントページが処理されます。 |
| newWidth | Double | デフォルトの空間単位でのページ内容の新しい幅。 |
| newHeight | Double | デフォルトの空間単位でのページ内容の新しい高さ。 |

### 戻り値

リサイズが成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

ドキュメントページの内容をリサイズします。ページの内容を縮小し、マージンを追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | String | ソースドキュメントへのパス。 |
| destination | String | 結果のドキュメントが保存されるパス。 |
| pages | Int32[] | ページインデックスの配列。nullの場合はすべてのドキュメントページが処理されます。 |
| newWidth | Double | デフォルトの空間単位でのページ内容の新しい幅。 |
| newHeight | Double | デフォルトの空間単位でのページ内容の新しい高さ。 |

### 戻り値

リサイズが成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//resize all pages of document
null, 
//new contents width = 200
200, 
//new contents height = 300
300);
// rest area of page will be empty
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

ドキュメントのページの内容をリサイズします。ページが縮小されると、ページの周りに空白のマージンが追加されます。

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | String | ソースドキュメントのパス。 |
| destination | String | 目的のドキュメントのパス。 |
| pages | Int32[] | ページインデックスの配列（ページインデックスは1から始まります）。 |
| parameters | ContentsResizeParameters | ページリサイズのパラメーター。 |

### 戻り値

リサイズが成功した場合は true。

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
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### 参照

* クラス [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

ドキュメントのページをリサイズします。縮小されたページの周りに空白のマージンが追加されます。

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | Document | ソースドキュメント。 |
| pages | Int32[] | ページインデックスのリスト。 |
| parameters | ContentsResizeParameters | リサイズパラメーター。 |

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* クラス [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

ドキュメントのページをリサイズします。縮小されたページの周りに空白のマージンが追加されます。

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| source | Document | ソースドキュメント。 |
| parameters | ContentsResizeParameters | リサイズパラメーター。 |

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
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
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* クラス [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)