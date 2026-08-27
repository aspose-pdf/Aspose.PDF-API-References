---
title: "PdfFileEditor.ResizeContents"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。ドキュメントのページの内容をリサイズします"
type: docs
weight: 320
url: /ja/net/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## ResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#resizecontents}

ドキュメントのページ内容のサイズを変更します。

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | Stream | ソース文書のストリームです。 |
| destination | Stream | 宛先文書のストリームです。 |
| pages | Int32[] | ページインデックスの配列です。 |
| パラメータ | ContentsResizeParameters | リサイズパラメータです。 |

### 戻り値

成功した場合は true を返します。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左余白 = ページ幅の10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新しいコンテンツ幅は幅 - 左余白 - 右余白として自動的に計算されます (100% - 10% - 10% = 80%)
    null,
    //右余白はページの10%です
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上余白 = 高さの10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新しいコンテンツ高さは自動的に計算されます (幅と同様)
    null,
    //下余白は10%です
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(src, dest, new int[] { 1, 2,.3}, parameters);
dest.Close();
```

### 関連項目

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Stream, Stream, int[], double, double) {#resizecontents_1}

ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。

```csharp
public bool ResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | Stream | ソース ドキュメントを含むストリーム。 |
| destination | Stream | 結果のドキュメントが保存されるストリーム。 |
| pages | Int32[] | ページインデックスの配列。null の場合、すべてのドキュメントページが処理されます。 |
| newWidth | Double | デフォルトの空間単位でのページコンテンツの新しい幅です。 |
| newHeight | Double | デフォルトの空間単位でのページコンテンツの新しい高さです。 |

### 戻り値

サイズ変更が成功した場合は True。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
fileEditor.ResizeContents(src, dest, 
//文書のすべてのページをリサイズします
null, 
//新しいコンテンツの幅 = 200
200, 
//新しいコンテンツの高さ = 300
300);
// ページの残り領域は空になります
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], double, double) {#resizecontents_3}

ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。

```csharp
public bool ResizeContents(string source, string destination, int[] pages, double newWidth, 
    double newHeight)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | String | ソース文書へのパスです。 |
| destination | String | 結果文書が保存されるパスです。 |
| pages | Int32[] | ページインデックスの配列。null の場合、すべてのドキュメントページが処理されます。 |
| newWidth | Double | デフォルトの空間単位でのページコンテンツの新しい幅です。 |
| newHeight | Double | デフォルトの空間単位でのページコンテンツの新しい高さです。 |

### 戻り値

リサイズが成功した場合は true です。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.ResizeContents("input.pdf", "output.pdf", 
//文書のすべてのページをリサイズします
null, 
//新しいコンテンツの幅 = 200
200, 
//新しいコンテンツの高さ = 300
300);
// ページの残り領域は空になります
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(string, string, int[], ContentsResizeParameters) {#resizecontents_2}

ドキュメント内のページ内容のサイズを変更します。ページが縮小された場合、ページの周囲に空白の余白が追加されます。

```csharp
public bool ResizeContents(string source, string destination, int[] pages, 
    ContentsResizeParameters parameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | String | ソースドキュメントのパス。 |
| destination | String | 宛先ドキュメントのパス。 |
| pages | Int32[] | ページインデックスの配列（ページインデックスは 1 から開始）。 |
| パラメータ | ContentsResizeParameters | ページリサイズのパラメータ。 |

### 戻り値

リサイズが成功した場合は true です。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左余白 = ページ幅の10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新しいコンテンツ幅は幅 - 左余白 - 右余白として自動的に計算されます (100% - 10% - 10% = 80%)
    null,
    //右余白はページの10%です
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上余白 = 高さの10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新しいコンテンツ高さは自動的に計算されます (幅と同様)
    null,
    //下余白は10%です
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3 }, parameters);
```

### 関連項目

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, int[], ContentsResizeParameters) {#resizecontents_5}

ドキュメントのページサイズを変更します。縮小されたページの周囲に空白の余白が追加されます。

```csharp
public void ResizeContents(Document source, int[] pages, ContentsResizeParameters parameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | Document | ソース文書。 |
| pages | Int32[] | ページインデックスの一覧。 |
| パラメータ | ContentsResizeParameters | リサイズパラメータです。 |

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左余白 = ページ幅の10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新しいコンテンツ幅は幅 - 左余白 - 右余白として自動的に計算されます (100% - 10% - 10% = 80%)
    null,
    //右余白はページの10%です
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上余白 = 高さの10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新しいコンテンツ高さは自動的に計算されます (幅と同様)
    null,
    //下余白は10%です
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, new int[] { 1, 2, 3 }, parameters);
doc.Save("output.pdf");
```

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ResizeContents(Document, ContentsResizeParameters) {#resizecontents_4}

ドキュメントのページサイズを変更します。縮小されたページの周囲に空白の余白が追加されます。

```csharp
public void ResizeContents(Document source, ContentsResizeParameters parameters)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| source | Document | ソース文書。 |
| パラメータ | ContentsResizeParameters | リサイズパラメータです。 |

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Document doc = new Document("input.pdf");
PdfFileEditor.ContentsResizeParameters parameters = new PdfFileEditor.ContentsResizeParameters(
    //左余白 = ページ幅の10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新しいコンテンツ幅は幅 - 左余白 - 右余白として自動的に計算されます (100% - 10% - 10% = 80%)
    null,
    //右余白はページの10%です
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //上余白 = 高さの10%
    PdfFileEditor.ContentsResizeValue.Percents(10),
    //新しいコンテンツ高さは自動的に計算されます (幅と同様)
    null,
    //下余白は10%です
    PdfFileEditor.ContentsResizeValue.Percents(10)
       );
fileEditor.ResizeContents(doc, parameters);
doc.Save("output.pdf");
```

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


