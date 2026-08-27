---
title: "PdfFileEditor.TryAppend"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。portStreams の配列から選択されたページを追加します。結果の Document には firstInputFile と、portStreams の Document のページが startPage から endPage の範囲で含まれます。"
type: docs
weight: 380
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryappend/
---
## TryAppend(Stream, Stream[], int, int, Stream) {#tryappend}

portStreams のドキュメント配列から選択されたページを追加します。結果のドキュメントには firstInputFile と、portStreams のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。

```csharp
public bool TryAppend(Stream inputStream, Stream[] portStreams, int startPage, int endPage, 
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

## 備考

TryAppend メソッドは Append メソッドと同様ですが、操作が失敗した場合に TryAppend メソッドは例外をスローしません。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream instream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = fileEditor.TryAppend(instream, new Stream[] { stream1, stream2}, 3, 5, outstream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryAppend(string, string[], int, int, string) {#tryappend_1}

portFiles のドキュメントから選択されたページを追加します。結果のドキュメントには firstInputFile と、portFiles のすべてのドキュメントの startPage から endPage の範囲のページが含まれます。

```csharp
public bool TryAppend(string inputFile, string[] portFiles, int startPage, int endPage, 
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

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryAppend メソッドは Append メソッドと同様ですが、操作が失敗した場合に TryAppend メソッドは例外をスローしません。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryAppend("input.pdf", new string[] { "file1.pdf", "file2.pdf"}, 3, 5, "outfile.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


