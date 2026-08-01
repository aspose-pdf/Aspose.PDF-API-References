---
title: "PdfFileEditor.TryInsert"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。別のファイルからページを挿入して、入力 PDF ファイルに追加します。"
type: docs
weight: 420
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

別のファイルからページを挿入し、入力 Pdf ファイルに追加します。

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| insertLocation | Int32 | 入力ファイル内の挿入位置。 |
| portFile | String | Pdf ファイルからのページ。 |
| pageNumber | Int32[] | portFileにポートされたページ番号。 |
| outputFile | String | 出力 Pdf ファイル。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TryInsert メソッドは Insert メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

別のファイルからページを挿入し、入力 Pdf ファイルに追加します。

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | Pdf ファイルの入力ストリーム。 |
| insertLocation | Int32 | 入力ファイル内の挿入位置。 |
| portStream | Stream | ページ用の Pdf ファイルストリーム。 |
| pageNumber | Int32[] | portFileにポートされたページ番号。 |
| outputStream | Stream | 出力ストリーム。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryInsert メソッドは Insert メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


