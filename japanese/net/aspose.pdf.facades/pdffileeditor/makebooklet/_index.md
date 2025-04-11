---
title: PdfFileEditor.MakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。入力ファイルから出力ファイルへのブックレットを作成します。
type: docs
weight: 300
url: /ja/net/aspose.pdf.facades/pdffileeditor/makebooklet/
---
## MakeBooklet(string, string) {#makebooklet_4}

入力ファイルから出力ファイルへのブックレットを作成します。

```csharp
public bool MakeBooklet(string inputFile, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf");
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream) {#makebooklet}

InputStream から outputStream へのブックレットを作成します。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize) {#makebooklet_5}

inputFile から outputFile へのブックレットを作成します。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize) {#makebooklet_1}

入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4);
```

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, int[], int[]) {#makebooklet_7}

firstInputFile から outputFile へのカスタマイズされたブックレットを作成します。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| leftPages | Int32[] | ブックレットの左ページ。 |
| rightPages | Int32[] | ブックレットの右ページ。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, int[], int[]) {#makebooklet_3}

firstInputStream から outputStream へのカスタマイズされたブックレットを作成します。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, int[] rightPages)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| leftPages | Int32[] | 左ページ。 |
| rightPages | Int32[] | 右ページ。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, string, PageSize, int[], int[]) {#makebooklet_6}

firstInputFile から outputFile へのカスタマイズされたブックレットを作成します。

```csharp
public bool MakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
    int[] rightPages)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |
| leftPages | Int32[] | 左ページ。 |
| rightPages | Int32[] | 右ページ。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, Stream, PageSize, int[], int[]) {#makebooklet_2}

firstInputStream から outputStream へのブックレットを作成します。

```csharp
public bool MakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
    int[] leftPages, int[] rightPages)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |
| leftPages | Int32[] | 左ページ。 |
| rightPages | Int32[] | 右ページ。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## MakeBooklet(string, PageSize, int[], int[], HttpResponse) {#makebooklet_6}

ソースファイルからブックレットを作成し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイルのパス。 |
| pageSize | PageSize | 希望するページサイズ。 |
| leftPages | Int32[] | 左に配置されるページ番号の配列。 |
| rightPages | Int32[] | 右に配置されるページ番号の配列。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功した場合は true。

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#makebooklet}

PDF ファイルからブックレットを作成し、HttpResponse に保存します。

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ドキュメントストリーム。 |
| pageSize | PageSize | 希望するページサイズ。 |
| leftPages | Int32[] | 左に配置されるページ番号の配列。 |
| rightPages | Int32[] | 右に配置されるページ番号の配列。 |
| response | HttpResponse | HttpResponse オブジェクト。 |

### 戻り値

操作が成功した場合は true。

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(string, PageSize, HttpResponse) {#makebooklet_7}

ソースファイルからブックレットを作成し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool MakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイルのパス。 |
| pageSize | PageSize | 出力ファイルの希望するページサイズ。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功した場合は true。

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeBooklet(Stream, PageSize, HttpResponse) {#makebooklet_1}

ソースファイルからブックレットを作成し、結果を HttpResponse に保存します。

```csharp
public bool MakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ドキュメントストリーム。 |
| pageSize | PageSize | 出力ファイルの希望するページサイズ。 |
| response | HttpResponse | 結果が保存されるレスポンスオブジェクト。 |

### 戻り値

ブックレットが正常に構築された場合は true。

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)