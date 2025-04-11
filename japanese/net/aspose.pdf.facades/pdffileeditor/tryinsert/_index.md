---
title: PdfFileEditor.TryInsert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。別のファイルからページを入力 Pdf ファイルに挿入します。
type: docs
weight: 420
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryinsert/
---
## TryInsert(string, int, string, int[], string) {#tryinsert_1}

別のファイルからページを入力 Pdf ファイルに挿入します。

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| insertLocation | Int32 | 入力ファイル内の挿入位置。 |
| portFile | String | Pdf ファイルからのページ。 |
| pageNumber | Int32[] | portFile にポートされたページ番号。 |
| outputFile | String | 出力 Pdf ファイル。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TryInsert メソッドは Insert メソッドに似ていますが、TryInsert メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryInsert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], Stream) {#tryinsert}

別のファイルからページを入力 Pdf ファイルに挿入します。

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | Pdf ファイルの入力ストリーム。 |
| insertLocation | Int32 | 入力ファイル内の挿入位置。 |
| portStream | Stream | ページ用の Pdf ファイルのストリーム。 |
| pageNumber | Int32[] | portFile にポートされたページ番号。 |
| outputStream | Stream | 出力ストリーム。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryInsert メソッドは Insert メソッドに似ていますが、TryInsert メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryInsert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)


## TryInsert(string, int, string, int[], HttpResponse) {#tryinsert_3}

ファイルの内容をソースファイルに挿入し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryInsert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイル名。 |
| insertLocation | Int32 | 2 番目のファイルが挿入されるページ番号。 |
| portFile | String | 挿入されるファイルへのパス。 |
| pageNumber | Int32[] | 挿入されるソースファイルのページ番号の配列。 |
| response | HttpResponse | 結果が保存されるレスポンスオブジェクト。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryInsert メソッドは Insert メソッドに似ていますが、TryInsert メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryInsert(Stream, int, Stream, int[], HttpResponse) {#tryinsert_1}

ドキュメントを別のドキュメントに挿入し、結果をレスポンスオブジェクトに保存します。

```csharp
public bool TryInsert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソースドキュメントのストリーム |
| insertLocation | Int32 | 別のドキュメントが挿入される位置。 |
| portStream | Stream | 挿入されるドキュメント。 |
| pageNumber | Int32[] | 挿入される2 番目のドキュメントのページ番号の配列。 |
| response | HttpResponse | 結果が保存されるレスポンスオブジェクト。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryInsert メソッドは Insert メソッドに似ていますが、TryInsert メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)