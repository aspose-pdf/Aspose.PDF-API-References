---
title: PdfFileEditor.Concatenate
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。2 つのファイルを連結します
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

2 つのファイルを連結します。

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputFile | String | 連結する最初のファイル。 |
| secInputFile | String | 連結する2番目のファイル。 |
| outputFile | String | 出力ファイル。 |

### 戻り値

操作が成功した場合は真。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

2 つのファイルを連結します。

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputStream | Stream | 最初のファイルのストリーム。 |
| secInputStream | Stream | 2 番目のファイルのストリーム。 |
| outputStream | Stream | 結果ファイルが保存されるストリーム。 |

### 戻り値

操作が成功した場合は真。

操作が成功した場合は真。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

ドキュメントを連結します。

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| src | Document[] | ソースドキュメントの配列。 |
| dest | Document | 目的のドキュメント。 |

### 戻り値

連結が成功した場合は真。

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

ファイルを1つのファイルに連結します。

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFiles | String[] | 連結するファイルの配列。 |
| outputFile | String | 出力ファイルの名前。 |

### 戻り値

操作が成功した場合は真。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

ファイルを連結します。

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream[] | 連結されるストリームの配列。 |
| outputStream | Stream | 結果ファイルが保存されるストリーム。 |

### 戻り値

操作が成功した場合は真。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

2 つの Pdf ドキュメントを新しい Pdf ドキュメントにマージし、ページを交互に配置し、空白の場所を空白のページで埋めます。例：document1 は 5 ページを持っています：p1、p2、p3、p4、p5。document2 は 3 ページを持っています：p1'、p2'、p3'。2 つの Pdf ドキュメントをマージすると、結果のドキュメントは次のページを持ちます：p1、p1'、p2、p2'、p3、p3'、p4、空白ページ、p5、空白ページ。

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputFile | String | 最初のファイル。 |
| secInputFile | String | 2 番目のファイル。 |
| blankPageFile | String | 空白ページのある PDF ファイル。 |
| outputFile | String | 結果ファイル。 |

### 戻り値

操作が成功した場合は真。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

2 つの Pdf ドキュメントを新しい Pdf ドキュメントにマージし、ページを交互に配置し、空白の場所を空白のページで埋めます。例：document1 は 5 ページを持っています：p1、p2、p3、p4、p5。document2 は 3 ページを持っています：p1'、p2'、p3'。2 つの Pdf ドキュメントをマージすると、結果のドキュメントは次のページを持ちます：p1、p1'、p2、p2'、p3、p3'、p4、空白ページ、p5、空白ページ。

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| firstInputStream | Stream | 最初の Pdf ストリーム。 |
| secInputStream | Stream | 2 番目の Pdf ストリーム。 |
| blankPageStream | Stream | 空白ページのある Pdf ストリーム。 |
| outputStream | Stream | 出力 Pdf ストリーム。 |

### 戻り値

操作が成功した場合は真。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)


## Concatenate(string[], HttpResponse) {#concatenate_8}

ファイルを連結し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool Concatenate(string[] inputFiles, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFiles | String[] | 連結するファイルの配列。 |
| response | HttpResponse | レスポンスオブジェクト。 |

### 戻り値

連結が成功した場合は真。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Concatenate(Stream[], HttpResponse) {#concatenate_4}

ファイルを連結し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool Concatenate(Stream[] inputStream, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream[] | 連結するファイルを含むストリームの配列。 |
| response | HttpResponse | レスポンスオブジェクト。 |

### 戻り値

操作が成功した場合は真。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)