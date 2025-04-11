---
title: PdfFileEditor.Append
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。portStreams のドキュメントの配列から選択されたページを追加します。結果のドキュメントには firstInputFile と startPage から endPage の範囲内のすべての portStreams ドキュメントのページが含まれます。
type: docs
weight: 250
url: /ja/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

portStreams のドキュメントの配列から選択されたページを追加します。結果のドキュメントには firstInputFile と startPage から endPage の範囲内のすべての portStreams ドキュメントのページが含まれます。

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 Pdf ストリーム。 |
| portStreams | Stream[] | ページをコピーするドキュメント。 |
| startPage | Int32 | portStreams ドキュメントでのページの開始。 |
| endPage | Int32 | portStreams ドキュメントでのページの終了。 |
| outputStream | Stream | 出力 Pdf ストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

portFiles ドキュメントから選択されたページを追加します。結果のドキュメントには firstInputFile と startPage から endPage の範囲内のすべての portFiles ドキュメントのページが含まれます。

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| portFiles | String[] | ページをコピーするドキュメント。 |
| startPage | Int32 | portFiles ドキュメントでのページの開始。 |
| endPage | Int32 | portFiles ドキュメントでのページの終了。 |
| outputFile | String | 出力 Pdf ドキュメント。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

startPage から endPage の範囲内の portFile から選択されたページを firstInputFile の最後に追加します。

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| portFile | String | Pdf ファイルからのページ。 |
| startPage | Int32 | portFile でのページの開始。 |
| endPage | Int32 | portFile でのページの終了。 |
| outputFile | String | 出力 Pdf ドキュメント。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

startPage から endPage の範囲内の portStream から選択されたページを firstInputStream の最後に追加します。

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイル ストリーム。 |
| portStream | Stream | Pdf ファイル ストリームからのページ。 |
| startPage | Int32 | portFile ストリームでのページの開始。 |
| endPage | Int32 | portFile ストリームでのページの終了。 |
| outputStream | Stream | 出力 Pdf ファイル ストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)