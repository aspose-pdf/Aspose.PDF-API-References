---
title: "PdfFileEditor.TryResizeContents"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。ドキュメントのページの内容をリサイズします"
type: docs
weight: 450
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## TryResizeContents(Stream, Stream, int[], ContentsResizeParameters) {#tryresizecontents}

ドキュメントのページ内容のサイズを変更します。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, 
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

## 備考

TryResizeContents メソッドは ResizeContents メソッドと同様ですが、操作が失敗した場合に例外をスローしない点が異なります。

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

ドキュメントページの内容のサイズを変更します。ページの内容を縮小し、余白を追加します。新しい内容のサイズはデフォルトの空間単位で指定されます。

```csharp
public bool TryResizeContents(Stream source, Stream destination, int[] pages, double newWidth, 
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

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryResizeContents メソッドは ResizeContents メソッドと同様ですが、操作が失敗した場合に例外をスローしない点が異なります。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream src = new Stream("input.pdf", FileMode.Open);
Stream dest = new Stream("output.pdf", FileMode.Create);
bool result = fileEditor.TryResizeContents(src, dest, 
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

## TryResizeContents(string, string, int[], ContentsResizeParameters) {#tryresizecontents_2}

ドキュメント内のページ内容のサイズを変更します。ページが縮小された場合、ページの周囲に空白の余白が追加されます。

```csharp
public bool TryResizeContents(string source, string destination, int[] pages, 
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

## 備考

TryResizeContents メソッドは ResizeContents メソッドと同様ですが、操作が失敗した場合に例外をスローしない点が異なります。

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
bool result = fileEditor.TryResizeContents("input.pdf", "output.pdf", new int[] { 1, 2, 3}, parameters);
```

### 関連項目

* class [ContentsResizeParameters](../../pdffileeditor.contentsresizeparameters/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


