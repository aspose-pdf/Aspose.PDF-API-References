---
title: PdfFileEditor.TryConcatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。2 つのファイルを連結します。
type: docs
weight: 390
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryconcatenate/
---
## TryConcatenate(string, string, string) {#tryconcatenate_3}

2 つのファイルを連結します。

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputFile | String | 連結する最初のファイル。 |
| secInputFile | String | 連結する2 番目のファイル。 |
| outputFile | String | 出力ファイル。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryConcatenate メソッドは Concatenate メソッドと似ていますが、TryConcatenate メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
bool result = fileEditor.TryConcatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryConcatenate(Document[], Document) {#tryconcatenate}

ドキュメントを連結します。

```csharp
public bool TryConcatenate(Document[] src, Document dest)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| src | Document[] | ソースドキュメントの配列。 |
| dest | Document | 宛先ドキュメント。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryConcatenate メソッドは Concatenate メソッドと似ていますが、TryConcatenate メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryConcatenate(string[], string) {#tryconcatenate_5}

ファイルを 1 つのファイルに連結します。

```csharp
public bool TryConcatenate(string[] inputFiles, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFiles | String[] | 連結するファイルの配列。 |
| outputFile | String | 出力ファイルの名前。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryConcatenate メソッドは Concatenate メソッドと似ていますが、TryConcatenate メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate(new string[] { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], Stream) {#tryconcatenate_2}

ファイルを連結します。

```csharp
public bool TryConcatenate(Stream[] inputStream, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream[] | 連結するストリームの配列。 |
| outputStream | Stream | 結果ファイルが保存されるストリーム。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryConcatenate メソッドは Concatenate メソッドと似ていますが、TryConcatenate メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2 } , outstream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryConcatenate(string, string, string, string) {#tryconcatenate_4}

2 つの Pdf ドキュメントを新しい Pdf ドキュメントにマージし、ページを交互に配置し、空白の場所を空白のページで埋めます。例: document1 には 5 ページがあります: p1, p2, p3, p4, p5。 document2 には 3 ページがあります: p1', p2', p3'。 2 つの Pdf ドキュメントをマージすると、結果のドキュメントは次のページになります: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage。

```csharp
public bool TryConcatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputFile | String | 最初のファイル。 |
| secInputFile | String | 2 番目のファイル。 |
| blankPageFile | String | 空白ページのある PDF ファイル。 |
| outputFile | String | 結果ファイル。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryConcatenate メソッドは Concatenate メソッドと似ていますが、TryConcatenate メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryConcatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryConcatenate(Stream, Stream, Stream, Stream) {#tryconcatenate_1}

2 つの Pdf ドキュメントを新しい Pdf ドキュメントにマージし、ページを交互に配置し、空白の場所を空白のページで埋めます。例: document1 には 5 ページがあります: p1, p2, p3, p4, p5。 document2 には 3 ページがあります: p1', p2', p3'。 2 つの Pdf ドキュメントをマージすると、結果のドキュメントは次のページになります: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage。

```csharp
public bool TryConcatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputStream | Stream | 最初の Pdf ストリーム。 |
| secInputStream | Stream | 2 番目の Pdf ストリーム。 |
| blankPageStream | Stream | 空白ページのある Pdf ストリーム。 |
| outputStream | Stream | 出力 Pdf ストリーム。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryConcatenate メソッドは Concatenate メソッドと似ていますが、TryConcatenate メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryConcatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)


## TryConcatenate(string[], HttpResponse) {#tryconcatenate_7}

ファイルを連結し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryConcatenate(string[] inputFiles, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFiles | String[] | 連結するファイルの配列。 |
| response | HttpResponse | レスポンスオブジェクト。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryConcatenate メソッドは Concatenate メソッドと似ていますが、TryConcatenate メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## TryConcatenate(Stream[], HttpResponse) {#tryconcatenate_3}

ファイルを連結し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TryConcatenate(Stream[] inputStream, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream[] | 連結するファイルを含むストリームの配列。 |
| response | HttpResponse | レスポンスオブジェクト。 |

### 戻り値

操作が成功した場合は true; それ以外の場合は false。

## 備考

TryConcatenate メソッドは Concatenate メソッドと似ていますが、TryConcatenate メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)