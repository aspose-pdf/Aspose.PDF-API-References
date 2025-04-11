---
title: PdfFileEditor.MakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。2 つの入力 PDF ストリームから NUp ドキュメントを outputStream に作成します。
type: docs
weight: 310
url: /ja/net/aspose.pdf.facades/pdffileeditor/makenup/
---
## MakeNUp(Stream, Stream, Stream) {#makenup_2}

最初の入力ファイルから outputFile への N-Up ドキュメントを作成します。

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup_2}

入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_3}

最初の入力ストリームから出力ストリームへの N-Up ドキュメントを作成します。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_10}

2 つの入力 PDF ファイルから outputFile への N-Up ドキュメントを作成します。outputFile の各ページには 2 ページが含まれ、1 ページは最初の入力ファイルから、もう 1 ページは 2 番目の入力ファイルからです。2 ページは水平方向に重ねられます。

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstInputFile | String | 最初の入力ファイル。 |
| secondInputFile | String | 2 番目の入力ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, Stream) {#makenup_4}

2 つの入力 PDF ストリームから outputStream への N-Up ドキュメントを作成します。

```csharp
public bool MakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstInputStream | Stream | 最初の入力ストリーム。 |
| secondInputStream | Stream | 2 番目の入力ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
pfe.MakeNUp(input1, input2, output);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string[], string, bool) {#makenup_7}

複数の入力 PDF ファイルから outputFile への N-Up ドキュメントを作成します。outputFile の各ページには、同じページ番号の入力ファイルのページの組み合わせが含まれます。isSidewise が true の場合は水平方向に重ねられ、false の場合は垂直方向に重ねられます。

```csharp
public bool MakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFiles | String[] | 入力 PDF ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| isSidewise | Boolean | 重ね方、true は水平方向、false は垂直方向。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream[], Stream, bool) {#makenup_3}

複数の入力 PDF ストリームから outputStream への N-Up ドキュメントを作成します。outputStream の各ページには、同じページ番号の入力ストリームのページの組み合わせが含まれます。isSidewise が true の場合は水平方向に重ねられ、false の場合は垂直方向に重ねられます。

```csharp
public bool MakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStreams | Stream[] | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| isSidewise | Boolean | 重ね方、true は水平方向、false は垂直方向。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int, PageSize) {#makenup_5}

入力ファイルから outputFile への N-Up ドキュメントを作成します。

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, int, int) {#makenup_4}

最初の入力ファイルから outputFile への N-Up ドキュメントを作成します。

```csharp
public bool MakeNUp(string inputFile, string outputFile, int x, int y)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int) {#makenup}

入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(Stream, Stream, int, int, PageSize) {#makenup_1}

最初の入力ストリームから出力ストリームへの N-Up ドキュメントを作成します。

```csharp
public bool MakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が成功した場合は true。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 参照

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## MakeNUp(string, string, string) {#makenup_6}

2 つの入力 PDF ファイルから outputFile への N-Up ドキュメントを作成します。outputFile の各ページには 2 ページが含まれ、1 ページは最初の入力ファイルから、もう 1 ページは 2 番目の入力ファイルからです。2 ページは水平方向に重ねられます。

```csharp
public bool MakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| firstInputFile | String | 最初の入力ファイル。 |
| secondInputFile | String | 2 番目の入力ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |

### 戻り値

boolean - 成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.MakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)