---
title: PdfFileEditor.TryMakeNUp
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。firstInputFile から outputFile への NUp ドキュメントを作成します。
type: docs
weight: 440
url: /ja/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

N-up ドキュメントを作成し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, PageSize pageSize, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイルへのパス。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| pageSize | PageSize | 結果ファイルのページサイズ。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, PageSize, HttpResponse) {#trymakenup}

N-up ドキュメントを作成し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, PageSize pageSize, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソースドキュメントのストリーム。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| pageSize | PageSize | 結果ファイルのページサイズ。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, int, int, HttpResponse) {#trymakenup_7}

N-up ドキュメントを作成し、結果を HttpResponse に保存します。

```csharp
public bool TryMakeNUp(string inputFile, int x, int y, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイル名。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, int, int, HttpResponse) {#trymakenup_1}

N-up ドキュメントを作成し、結果を HttpResponse に保存します。

```csharp
public bool TryMakeNUp(Stream inputStream, int x, int y, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ドキュメントのストリーム。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| response | HttpResponse | 結果が保存される HttpResponse。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int) {#trymakenup_8}

firstInputFile から outputFile への N-Up ドキュメントを作成します。

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 pdf ファイルのパスと名前。 |
| outputFile | String | 出力 pdf ファイルのパスと名前。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int) {#trymakenup}

入力ストリームから N-Up ドキュメントを作成し、結果を出力ストリームに保存します。

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 pdf ストリーム。 |
| outputStream | Stream | 出力 pdf ストリーム。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, int, int, PageSize) {#trymakenup_1}

最初の入力ストリームから出力ストリームへの N-Up ドキュメントを作成します。

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 pdf ストリーム。 |
| outputStream | Stream | 出力 pdf ストリーム。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| pageSize | PageSize | 出力 pdf ファイルのページサイズ。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream inputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(inputStream, outputStream, 3, 3, PageSize.A4);
```

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, string) {#trymakenup_6}

2 つの入力 PDF ファイルから outputFile への N-Up ドキュメントを作成します。outputFile の各ページには 2 ページが含まれ、1 ページは最初の入力ファイルから、もう 1 ページは 2 番目の入力ファイルからのものです。2 ページは水平方向に重ねられます。

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputFile | String | 最初の入力ファイル。 |
| secondInputFile | String | 2 番目の入力ファイル。 |
| outputFile | String | 出力 pdf ファイルのパスと名前。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input1.pdf", "input2.pdf", "output.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream, Stream, Stream) {#trymakenup_2}

2 つの入力 PDF ストリームから outputStream への N-Up ドキュメントを作成します。

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputStream | Stream | 最初の入力ストリーム。 |
| secondInputStream | Stream | 2 番目の入力ストリーム。 |
| outputStream | Stream | 出力 pdf ストリーム。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream input1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream input2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf");
bool result = pfe.TryMakeNUp(input1, input2, output);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string[], string, bool) {#trymakenup_7}

複数の入力 PDF ファイルから outputFile への N-Up ドキュメントを作成します。outputFile の各ページには、同じページ番号の入力ファイルのページが組み合わさった複数のページが含まれます。isSidewise が true の場合は水平方向に重ねられ、false の場合は垂直方向に重ねられます。

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFiles | String[] | 入力 Pdf ファイル。 |
| outputFile | String | 出力 pdf ファイルのパスと名前。 |
| isSidewise | Boolean | 重ね方、true は水平方向、false は垂直方向。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp(new string[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(Stream[], Stream, bool) {#trymakenup_3}

複数の入力 PDF ストリームから outputStream への N-Up ドキュメントを作成します。outputStream の各ページには、同じページ番号の入力ストリームのページが組み合わさった複数のページが含まれます。isSidewise が true の場合は水平方向に重ねられ、false の場合は垂直方向に重ねられます。

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStreams | Stream[] | 入力 Pdf ストリーム。 |
| outputStream | Stream | 出力 pdf ストリーム。 |
| isSidewise | Boolean | 重ね方、true は水平方向、false は垂直方向。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("input1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("input2.pdf", FileMode.Open, FileAccess.Read);
Stream stream3 = new FileStream("input3.pdf", FileMode.Open, FileAccess.Read);
Stream output = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryMakeNUp(new Stream[] { stream1, stream2, stream3 }, output, false);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryMakeNUp(string, string, int, int, PageSize) {#trymakenup_5}

入力ファイルから outputFile への N-Up ドキュメントを作成します。

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 pdf ファイルのパスと名前。 |
| outputFile | String | 出力 pdf ファイルのパスと名前。 |
| x | Int32 | 列の数。 |
| y | Int32 | 行の数。 |
| pageSize | PageSize | 出力 pdf ファイルのページサイズ。 |

### 戻り値

操作が成功裏に完了した場合は true; それ以外の場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドに似ていますが、TryMakeNUp メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryMakeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4);
```

### 関連項目

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)