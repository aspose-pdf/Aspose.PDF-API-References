---
title: "PdfFileEditor.TryMakeBooklet"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。入力ファイルから出力ファイルへブックレットを作成します。"
type: docs
weight: 430
url: /ja/net/aspose.pdf.facades/pdffileeditor/trymakebooklet/
---
## TryMakeBooklet(string, string) {#trymakebooklet_4}

入力ファイルから出力ファイルへブックレットを作成します。

```csharp
public bool TryMakeBooklet(string inputFile, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルのパスと名前。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が成功した場合は True。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| leftPages | Int32[] | ブックレットの左ページ。 |
| rightPages | Int32[] | ブックレットの右ページ。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| leftPages | Int32[] | 左側のページ。 |
| rightPages | Int32[] | 右側のページ。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイル。 |
| outputFile | String | 出力 PDF ファイルのパスと名前。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |
| leftPages | Int32[] | 左側のページ。 |
| rightPages | Int32[] | 右側のページ。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

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

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ストリーム。 |
| outputStream | Stream | 出力 PDF ストリーム。 |
| pageSize | PageSize | 出力 PDF ファイルのページサイズ。 |
| leftPages | Int32[] | 左側のページ。 |
| rightPages | Int32[] | 右側のページ。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryMakeBooklet メソッドは MakeBooklet メソッドと同様ですが、操作が失敗した場合に例外をスローしません。

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


