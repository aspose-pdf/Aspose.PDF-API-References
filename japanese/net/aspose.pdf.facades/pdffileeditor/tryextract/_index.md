---
title: PdfFileEditor.TryExtract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。
type: docs
weight: 410
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイルのパス。 |
| startPage | Int32 | 開始ページ番号。 |
| endPage | Int32 | 終了ページ番号。 |
| outputFile | String | 出力 Pdf ファイルのパス。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TryExtract メソッドは Extract メソッドに似ていますが、TryExtract メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイルのパス。 |
| pageNumber | Int32[] | 入力ファイル内のページのインデックス。 |
| outputFile | String | 出力ファイルのパス。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryExtract メソッドは Extract メソッドに似ていますが、TryExtract メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイルのストリーム。 |
| pageNumber | Int32[] | 入力ファイル内のページのインデックス。 |
| outputStream | Stream | 出力ファイルのストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TryExtract メソッドは Extract メソッドに似ていますが、TryExtract メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)


## TryExtract(Stream, int[], HttpResponse) {#tryextract_1}

指定されたページをソースファイルから抽出し、結果を HttpResponse オブジェクトに格納します。

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソースドキュメントのストリーム。 |
| pageNumber | Int32[] | 抽出されるページ番号の配列。 |
| response | HttpResponse | 結果が格納される HttpResponse オブジェクト。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryExtract メソッドは Extract メソッドに似ていますが、TryExtract メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryExtract(string, int[], HttpResponse) {#tryextract_4}

指定されたページをソースファイルから抽出し、結果を HttpResponse オブジェクトに格納します。

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイルのパス。 |
| pageNumber | Int32[] | 抽出されるページ番号の配列。 |
| response | HttpResponse | 結果が格納される HttpResponse オブジェクト。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TryExtract メソッドは Extract メソッドに似ていますが、TryExtract メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)