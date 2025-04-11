---
title: PdfFileEditor.TryMakeBooklet
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。入力ファイルから出力ファイルにブックレットを作成します。
type: docs
weight: 430
url: /ja/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

ソースファイルからブックレットを作成し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, int[] leftPages, int[] rightPages, 
    HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイルのパス。 |
| pageSize | PageSize | 希望するページサイズ。 |
| leftPages | Int32[] | 左側に配置されるページ番号の配列。 |
| rightPages | Int32[] | 右側に配置されるページ番号の配列。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, int[], int[], HttpResponse) {#trymakebooklet}

PDFファイルからブックレットを作成し、HttpResponse に保存します。

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, int[] leftPages, 
    int[] rightPages, HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ドキュメントストリーム。 |
| pageSize | PageSize | 希望するページサイズ。 |
| leftPages | Int32[] | 左側に配置されるページ番号の配列。 |
| rightPages | Int32[] | 右側に配置されるページ番号の配列。 |
| response | HttpResponse | HttpResponse オブジェクト。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, PageSize, HttpResponse) {#trymakebooklet_7}

ソースファイルからブックレットを作成し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryMakeBooklet(string inputFile, PageSize pageSize, HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイルのパス。 |
| pageSize | PageSize | 出力ファイルの希望するページサイズ。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功した場合は true。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, PageSize, HttpResponse) {#trymakebooklet_1}

ソースファイルからブックレットを作成し、結果を HttpResponse に保存します。

```csharp
public bool TryMakeBooklet(Stream inputStream, PageSize pageSize, HttpResponse response)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ドキュメントストリーム。 |
| pageSize | PageSize | 出力ファイルの希望するページサイズ。 |
| response | HttpResponse | 結果が保存されるレスポンスオブジェクト。 |

### 戻り値

ブックレットが正常に構築された場合は true。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string) {#trymakebooklet_8}

入力ファイルから出力ファイルにブックレットを作成します。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream) {#trymakebooklet}

InputStream から outputStream へブックレットを作成します。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize) {#trymakebooklet_5}

inputFile から outputFile へブックレットを作成します。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が成功した場合は true。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4);
```

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize) {#trymakebooklet_1}

入力ストリームからブックレットを作成し、結果を出力ストリームに保存します。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4);
```

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, int[], int[]) {#trymakebooklet_7}

firstInputFile から outputFile へカスタマイズされたブックレットを作成します。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, int[] leftPages, int[] rightPages)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| leftPages | Int32[] | ブックレットの左ページ。 |
| rightPages | Int32[] | ブックレットの右ページ。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, int[], int[]) {#trymakebooklet_3}

firstInputStream から outputStream へカスタマイズされたブックレットを作成します。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, int[] leftPages, 
    int[] rightPages)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| leftPages | Int32[] | 左ページ。 |
| rightPages | Int32[] | 右ページ。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(string, string, PageSize, int[], int[]) {#trymakebooklet_6}

firstInputFile から outputFile へカスタマイズされたブックレットを作成します。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile, PageSize pageSize, int[] leftPages, 
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

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeBooklet(Stream, Stream, PageSize, int[], int[]) {#trymakebooklet_2}

firstInputStream から outputStream へブックレットを作成します。

```csharp
public bool TryMakeBooklet(Stream inputStream, Stream outputStream, PageSize pageSize, 
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

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドに似ていますが、TryMakeBooklet メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 });
```

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---