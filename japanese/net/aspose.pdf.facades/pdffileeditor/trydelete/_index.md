---
title: PdfFileEditor.TryDelete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。入力ファイルから指定されたページを番号配列で削除し、新しい Pdf ファイルとして保存します。
type: docs
weight: 400
url: /ja/net/aspose.pdf.facades/pdffileeditor/trydelete/
---
## TryDelete(string, int[], string) {#trydelete_1}

入力ファイルから指定されたページを番号配列で削除し、新しい Pdf ファイルとして保存します。

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイルのパス。 |
| pageNumber | Int32[] | 入力ファイルのページのインデックス。 |
| outputFile | String | 出力ファイルのパス。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryDelete メソッドは Delete メソッドに似ていますが、TryDelete メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryDelete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], Stream) {#trydelete}

入力ファイルから指定されたページを番号配列で削除し、新しい Pdf ファイルとして保存します。

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイルのストリーム。 |
| pageNumber | Int32[] | 入力ファイルのページのインデックス。 |
| outputStream | Stream | 出力ファイルのストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 備考

TryDelete メソッドは Delete メソッドに似ていますが、TryDelete メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryDelete(inputStream, new int[] { 2, 3 }, outputStream);
```

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)


## TryDelete(string, int[], HttpResponse) {#trydelete_3}

ドキュメントから指定されたページを削除し、結果を HttpResponse オブジェクトに格納します。

```csharp
public bool TryDelete(string inputFile, int[] pageNumber, HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイルのパス。 |
| pageNumber | Int32[] | 削除する必要があるページ番号の配列。 |
| response | HttpResponse | 結果のドキュメントが格納されるレスポンスオブジェクト。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryDelete メソッドは Delete メソッドに似ていますが、TryDelete メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryDelete(Stream, int[], HttpResponse) {#trydelete_1}

ドキュメントから指定されたページを削除し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryDelete(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソースドキュメントのストリーム。 |
| pageNumber | Int32[] | 削除されるページ番号の配列。 |
| response | HttpResponse | HttpResponse オブジェクト |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryDelete メソッドは Delete メソッドに似ていますが、TryDelete メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)