---
title: PdfFileEditor.Extract
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。
type: docs
weight: 280
url: /ja/net/aspose.pdf.facades/pdffileeditor/extract/
---
## Extract(string, int, int, string) {#extract_2}

入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。

```csharp
public bool Extract(string inputFile, int startPage, int endPage, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイルのパス。 |
| startPage | Int32 | 開始ページ番号。 |
| endPage | Int32 | 終了ページ番号。 |
| outputFile | String | 出力 Pdf ファイルのパス。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", 3, 7, "output.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Extract(string, int[], string) {#extract_3}

番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。

```csharp
public bool Extract(string inputFile, int[] pageNumber, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイルのパス。 |
| pageNumber | Int32[] | 入力ファイルのページのインデックス。 |
| outputFile | String | 出力ファイルのパス。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Extract(Stream, int, int, Stream) {#extract}

入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。

```csharp
public bool Extract(Stream inputStream, int startPage, int endPage, Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイルストリーム。 |
| startPage | Int32 | 開始ページ番号。 |
| endPage | Int32 | 終了ページ番号。 |
| outputStream | Stream | 出力 Pdf ファイルストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, 1, 3, 6, outStream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Extract(Stream, int[], Stream) {#extract_1}

番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。

```csharp
public bool Extract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイルストリーム。 |
| pageNumber | Int32[] | 入力ファイルのページのインデックス。 |
| outputStream | Stream | 出力ファイルストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Extract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)