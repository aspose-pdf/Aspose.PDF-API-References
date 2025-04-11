---
title: PdfFileEditor.TryAppend
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。portStreams のドキュメントの配列から選択されたページを追加します。結果のドキュメントには firstInputFile と startPage から endPage の範囲内のすべての portStreams ドキュメントのページが含まれます。
type: docs
weight: 380
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

portStreams のドキュメントの配列から選択されたページを追加します。結果のドキュメントには firstInputFile と startPage から endPage の範囲内のすべての portStreams ドキュメントのページが含まれます。

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 Pdf ストリーム。 |
| portStreams | Stream[] | ページをコピーするドキュメント。 |
| startPage | Int32 | portStreams ドキュメントのページ開始。 |
| endPage | Int32 | portStreams ドキュメントのページ終了。 |
| outputStream | Stream | 出力 Pdf ストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TryAppend メソッドは Append メソッドに似ていますが、TryAppend メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

portFiles ドキュメントから選択されたページを追加します。結果のドキュメントには firstInputFile と startPage から endPage の範囲内のすべての portFiles ドキュメントのページが含まれます。

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| portFiles | String[] | ページをコピーするドキュメント。 |
| startPage | Int32 | portFiles ドキュメントのページ開始。 |
| endPage | Int32 | portFiles ドキュメントのページ終了。 |
| outputFile | String | 出力 Pdf ドキュメント。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryAppend メソッドは Append メソッドに似ていますが、TryAppend メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)


## TryAppend(Stream, Stream[], int, int, HttpResponse) {#tryappend_1}

ソースドキュメントにドキュメントを追加し、結果をレスポンスオブジェクトに保存します。

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソースドキュメントを含むストリーム。 |
| portStreams | Stream[] | 追加されるドキュメントを含むストリームの配列。 |
| startPage | Int32 | 追加されたページの開始ページ。 |
| endPage | Int32 | 追加されたページの終了ページ。 |
| response | HttpResponse | ドキュメントが保存されるレスポンスオブジェクト。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryAppend メソッドは Append メソッドに似ていますが、TryAppend メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, HttpResponse) {#tryappend_3}

ソースドキュメントにドキュメントを追加し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
    HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースドキュメントを含むファイルの名前。 |
| portFiles | String[] | 追加されたドキュメントを含むファイル名の配列。 |
| startPage | Int32 | 追加されたページの開始ページ。 |
| endPage | Int32 | 追加されたページの終了ページ。 |
| response | HttpResponse | ドキュメントが保存されるレスポンスオブジェクト。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryAppend メソッドは Append メソッドに似ていますが、TryAppend メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)