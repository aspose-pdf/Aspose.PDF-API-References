---
title: PdfFileEditor.Insert
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。別のファイルから Pdf ファイルの位置にページを挿入します。
type: docs
weight: 290
url: /ja/net/aspose.pdf.facades/pdffileeditor/insert/
---
## Insert(string, int, string, int, int, string) {#insert_2}

別のファイルから Pdf ファイルの位置にページを挿入します。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int startPage, 
    int endPage, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| insertLocation | Int32 | 入力ファイル内の位置。 |
| portFile | String | ポーティング Pdf ファイル。 |
| startPage | Int32 | portFile の開始位置。 |
| endPage | Int32 | portFile の終了位置。 |
| outputFile | String | 出力 Pdf ファイル。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", 2, 6, "out.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int, int, Stream) {#insert}

別のファイルから入力 Pdf ファイルにページを挿入します。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int startPage, 
    int endPage, Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | Pdf ファイルの入力ストリーム。 |
| insertLocation | Int32 | 入力ファイル内の挿入位置。 |
| portStream | Stream | ページ用の Pdf ファイルのストリーム。 |
| startPage | Int32 | どのページから開始するか。 |
| endPage | Int32 | どのページで終了するか。 |
| outputStream | Stream | 出力ストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, 2, 6, outStream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Insert(string, int, string, int[], string) {#insert_3}

別のファイルから入力 Pdf ファイルにページを挿入します。

```csharp
public bool Insert(string inputFile, int insertLocation, string portFile, int[] pageNumber, 
    string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 Pdf ファイル。 |
| insertLocation | Int32 | 入力ファイル内の挿入位置。 |
| portFile | String | Pdf ファイルからのページ。 |
| pageNumber | Int32[] | portFile にポーティングされたページ番号。 |
| outputFile | String | 出力 Pdf ファイル。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Insert("file1.pdf", 1, "file2.pdf", new int[] { 2, 6 }, "out.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Insert(Stream, int, Stream, int[], Stream) {#insert_1}

別のファイルから入力 Pdf ファイルにページを挿入します。

```csharp
public bool Insert(Stream inputStream, int insertLocation, Stream portStream, int[] pageNumber, 
    Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | Pdf ファイルの入力ストリーム。 |
| insertLocation | Int32 | 入力ファイル内の挿入位置。 |
| portStream | Stream | ページ用の Pdf ファイルのストリーム。 |
| pageNumber | Int32[] | portFile にポーティングされたページ番号。 |
| outputStream | Stream | 出力ストリーム。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream insertedStream = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)