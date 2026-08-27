---
title: "PdfFileEditor.TryMakeNUp"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor method. firstInputFile から outputFile へ NUp ドキュメントを作成します"
type: docs
weight: 440
url: /ja/net/aspose.pdf.facades/pdffileeditor/trymakenup/
---
## TryMakeNUp(string, string, int, int) {#trymakenup_4}

firstInputFile から N-Up ドキュメントを作成し、outputFile に出力します。

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドと同様ですが、操作が失敗した場合に TryMakeNUp メソッドは例外をスローしません。

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドと同様ですが、操作が失敗した場合に TryMakeNUp メソッドは例外をスローしません。

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

最初の入力ストリームから N-Up ドキュメントを作成し、出力ストリームに出力します。

```csharp
public bool TryMakeNUp(Stream inputStream, Stream outputStream, int x, int y, PageSize pageSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドと同様ですが、操作が失敗した場合に TryMakeNUp メソッドは例外をスローしません。

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

2つの入力 PDF ファイルから outputFile へ N-Up ドキュメントを作成します。outputFile の各ページは2ページを含み、1ページは最初の入力ファイルから、もう1ページは2番目の入力ファイルから取られます。これらの2ページは横方向に並べられます。

```csharp
public bool TryMakeNUp(string firstInputFile, string secondInputFile, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| firstInputFile | String | 最初の入力ファイル。 |
| secondInputFile | String | 2 番目の入力ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false

## 備考

TryMakeNUp メソッドは MakeNUp メソッドと同様ですが、操作が失敗した場合に TryMakeNUp メソッドは例外をスローしません。

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

2つの入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。

```csharp
public bool TryMakeNUp(Stream firstInputStream, Stream secondInputStream, Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| firstInputStream | Stream | 最初の入力ストリーム。 |
| secondInputStream | Stream | 2 番目の入力ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false

## 備考

TryMakeNUp メソッドは MakeNUp メソッドと同様ですが、操作が失敗した場合に TryMakeNUp メソッドは例外をスローしません。

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

複数の入力 PDF ファイルから N-Up ドキュメントを作成し、outputFile に出力します。outputFile の各ページには、同じページ番号の入力ファイルのページを組み合わせた複数ページが含まれます。isSidewise が true の場合はページが横方向に積み重ねられ、false の場合は縦方向に積み重ねられます。

```csharp
public bool TryMakeNUp(string[] inputFiles, string outputFile, bool isSidewise)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFiles | String[] | 入力 Pdf ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| isSidewise | Boolean | 積み上げ方式で、水平の場合は true、垂直の場合は false。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドと同様ですが、操作が失敗した場合に TryMakeNUp メソッドは例外をスローしません。

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

複数の入力 PDF ストリームから outputStream へ N-Up ドキュメントを作成します。outputStream の各ページは、同じページ番号の入力ストリームのページを組み合わせた複数ページを含みます。isSidewise が true の場合は横方向に、false の場合は縦方向にページが積み重ねられます。

```csharp
public bool TryMakeNUp(Stream[] inputStreams, Stream outputStream, bool isSidewise)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStreams | Stream[] | 入力 Pdf ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| isSidewise | Boolean | 積み上げ方式で、水平の場合は true、垂直の場合は false。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドと同様ですが、操作が失敗した場合に TryMakeNUp メソッドは例外をスローしません。

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

入力ファイルから N-Up ドキュメントを作成し、outputFile に出力します。

```csharp
public bool TryMakeNUp(string inputFile, string outputFile, int x, int y, PageSize pageSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| x | Int32 | 列数。 |
| y | Int32 | 行数。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeNUp メソッドは MakeNUp メソッドと同様ですが、操作が失敗した場合に TryMakeNUp メソッドは例外をスローしません。

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


