---
title: PdfFileEditor.TrySplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。指定した位置から分割し、後半部分を新しいファイルとして保存します。
type: docs
weight: 470
url: /ja/net/aspose.pdf.facades/pdffileeditor/trysplittoend/
---
## TrySplitToEnd(string, int, string) {#trysplittoend_1}

指定した位置から分割し、後半部分を新しいファイルとして保存します。

```csharp
public bool TrySplitToEnd(string inputFile, int location, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソース Pdf ファイル。 |
| location | Int32 | 分割位置。 |
| outputFile | String | 出力 Pdf ファイルパス。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TrySplitToEnd メソッドは SplitToEnd メソッドに似ていますが、TrySplitToEnd メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitToEnd("input.pdf", 5, "out.pdf");
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(Stream, int, Stream) {#trysplittoend}

指定した位置から分割し、後半部分を新しいファイルストリームとして保存します。

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソース Pdf ファイルストリーム。 |
| location | Int32 | 分割位置。 |
| outputStream | Stream | 出力 Pdf ファイルストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

この操作の後、ストリームは閉じられません（CloseConcatedStreams が指定されていない限り）。TrySplitToEnd メソッドは SplitToEnd メソッドに似ていますが、TrySplitToEnd メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TrySplitToEnd(sourceStream, 5, outStream);
```

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitToEnd(Stream, int, HttpResponse) {#trysplittoend_1}

指定した位置から分割し、後半部分を HttpResponse オブジェクトに保存します。

```csharp
public bool TrySplitToEnd(Stream inputStream, int location, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソースドキュメントストリーム。 |
| location | Int32 | 分割点。 |
| response | HttpResponse | HttpResponse オブジェクト。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TrySplitToEnd メソッドは SplitToEnd メソッドに似ていますが、TrySplitToEnd メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitToEnd(string, int, HttpResponse) {#trysplittoend_3}

指定した位置から分割し、後半部分を HttpResponse オブジェクトに保存します。

```csharp
public bool TrySplitToEnd(string inputFile, int location, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイル名。 |
| location | Int32 | 分割点。 |
| response | HttpResponse | HttpResponse オブジェクト。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TrySplitToEnd メソッドは SplitToEnd メソッドに似ていますが、TrySplitToEnd メソッドは操作が失敗した場合に例外をスローしません。

### 参照

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)