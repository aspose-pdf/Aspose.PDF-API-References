---
title: "PdfFileEditor.Append"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。portStreams の配列から選択されたページを追加します。結果の Document には firstInputFile と、portStreams の Document のページが startPage から endPage の範囲で含まれます。"
type: docs
weight: 250
url: /ja/net/aspose.pdf.facades/pdffileeditor/append/
---
## Append(Stream, Stream[], int, int, Stream) {#append_1}

portStreams のドキュメント配列から選択されたページを追加します。結果のドキュメントには firstInputFile と、portStreams のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。

```csharp
public bool Append(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
    Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 Pdf ストリーム。 |
| portStreams | Stream[] | ページをコピーする元の Document。 |
| startPage | Int32 | ページの開始は portStreams の Document にあります。 |
| endPage | Int32 | ページの終了は portStreams の Document にあります。 |
| outputStream | Stream | 出力 Pdf ストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string[], int, int, string) {#append_3}

portFiles のドキュメントから選択されたページを追加します。結果のドキュメントには firstInputFile と、portFiles のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。

```csharp
public bool Append(string inputFile, string[] portFiles, int startPage, int endPage, 
    string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| portFiles | String[] | ページをコピーする元の Document。 |
| startPage | Int32 | ページの開始は portFiles の Document にあります。 |
| endPage | Int32 | ページの終了は portFiles の Document にあります。 |
| outputFile | String | 出力 Pdf Document。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(string, string, int, int, string) {#append_2}

portFile から startPage から endPage の範囲で選択されたページを、firstInputFile の末尾にある portFile に追加します。

```csharp
public bool Append(string inputFile, string portFile, int startPage, int endPage, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| portFile | String | Pdf ファイルからのページ。 |
| startPage | Int32 | ページの開始は portFile にあります。 |
| endPage | Int32 | ページの終了は portFile にあります。 |
| outputFile | String | 出力 Pdf Document。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Append("input.pdf", "file1.pdf",  3, 5, "outfile.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Append(Stream, Stream, int, int, Stream) {#append}

portStream から startPage から endPage の範囲で選択されたページを、firstInputStream の末尾にある portStream に追加します。

```csharp
public bool Append(Stream inputStream, Stream portStream, int startPage, int endPage, 
    Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイル ストリーム。 |
| portStream | Stream | Pdf ファイル ストリームからのページ。 |
| startPage | Int32 | ページの開始は portFile ストリームにあります。 |
| endPage | Int32 | ページの終了は portFile ストリームにあります。 |
| outputStream | Stream | 出力 Pdf ファイル ストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Append(instream, stream1,  3, 5, "outfile.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


