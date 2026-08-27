---
title: "PdfFileEditor.Concatenate"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。2 つのファイルを連結します。"
type: docs
weight: 260
url: /ja/net/aspose.pdf.facades/pdffileeditor/concatenate/
---
## Concatenate(string, string, string) {#concatenate_4}

2つのファイルを連結します。

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| firstInputFile | String | 結合する最初のファイル。 |
| secInputFile | String | 結合する2番目のファイル。 |
| outputFile | String | 出力ファイル。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
fileEditor.Concatenate("file1.pdf", "file2.pdf", "outfile.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream) {#concatenate_1}

2つのファイルを連結します。

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| firstInputStream | Stream | 最初のファイルのストリーム。 |
| secInputStream | Stream | 2番目のファイルのストリーム。 |
| outputStream | Stream | 結果ファイルが保存されるストリーム。 |

### 戻り値

操作が成功した場合は True。

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(stream1, stream2, outstream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Document[], Document) {#concatenate}

ドキュメントを連結します。

```csharp
public bool Concatenate(Document[] src, Document dest)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| src | Document[] | ソース文書の配列。 |
| dest | Document | 宛先文書。 |

### 戻り値

結合が成功した場合は True。

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string[], string) {#concatenate_6}

ファイルを1つのファイルに連結します。

```csharp
public bool Concatenate(string[] inputFiles, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFiles | String[] | 結合するファイルの配列。 |
| outputFile | String | 出力ファイルの名前。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate(new string[]  { "src1.pdf", "src2.pdf" }, "dest.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream[], Stream) {#concatenate_3}

ファイルを連結します。

```csharp
public bool Concatenate(Stream[] inputStream, Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream[] | 結合されるストリームの配列。 |
| outputStream | Stream | 結果ファイルが保存されるストリーム。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2 } , outstream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(string, string, string, string) {#concatenate_5}

2つの Pdf ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めた新しい Pdf ドキュメントに結合します。例: document1 は 5 ページ (p1, p2, p3, p4, p5) を持ち、document2 は 3 ページ (p1', p2', p3') を持ちます。2つの Pdf ドキュメントを結合すると、結果のドキュメントはページ順に p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。

```csharp
public bool Concatenate(string firstInputFile, string secInputFile, string blankPageFile, 
    string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| firstInputFile | String | 最初のファイル。 |
| secInputFile | String | 2番目のファイル。 |
| blankPageFile | String | 空白ページを含む PDF ファイル。 |
| outputFile | String | 結果ファイル。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Concatenate("src1.pdf", "src2.pdf", "blank.pdf", "dest.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Concatenate(Stream, Stream, Stream, Stream) {#concatenate_2}

2つの Pdf ドキュメントを交互にページを配置し、空白の場所を空白ページで埋めた新しい Pdf ドキュメントに結合します。例: document1 は 5 ページ (p1, p2, p3, p4, p5) を持ち、document2 は 3 ページ (p1', p2', p3') を持ちます。2つの Pdf ドキュメントを結合すると、結果のドキュメントはページ順に p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage となります。

```csharp
public bool Concatenate(Stream firstInputStream, Stream secInputStream, Stream blankPageStream, 
    Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| firstInputStream | Stream | 最初の Pdf ストリーム。 |
| secInputStream | Stream | 2番目の Pdf ストリーム。 |
| blankPageStream | Stream | 空白ページがある Pdf ストリーム。 |
| outputStream | Stream | 出力 Pdf ストリーム。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor fileEditor = new PdfFileEditor();
Stream stream1 = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream stream2 = new FileStream("file2.pdf", FileMode.Open, FileAccess.Read);
Stream blank = new FileStream("blank.pdf", FileMode.Open, FileAccess.Read);
Stream outstream = new FileStream("outfile.pdf", FileMode.Create, FileAccess.Write);
fileEditor.Concatenate(new Stream[] { stream1, stream2, blank } , outstream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


