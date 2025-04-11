---
title: PdfFileEditor.TrySplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。Pdf ファイルを最初のページから指定された位置に分割し、前半部分を新しいファイルとして保存します。
type: docs
weight: 460
url: /ja/net/aspose.pdf.facades/pdffileeditor/trysplitfromfirst/
---
## TrySplitFromFirst(string, int, string) {#trysplitfromfirst_1}

Pdf ファイルを最初のページから指定された位置に分割し、前半部分を新しいファイルとして保存します。

```csharp
public bool TrySplitFromFirst(string inputFile, int location, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソース Pdf ファイル。 |
| location | Int32 | 分割ポイント。 |
| outputFile | String | 出力 Pdf ファイル。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TrySplitFromFirst メソッドは SplitFromFirst メソッドに似ていますが、TrySplitFromFirst メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TrySplitFromFirst("input.pdf", 5, "out.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, Stream) {#trysplitfromfirst}

開始から指定された位置まで分割し、出力ストリームに前半部分を保存します。

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソース Pdf ファイル ストリーム。 |
| location | Int32 | 分割ポイント。 |
| outputStream | Stream | 出力ファイル ストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

ストリームはこの操作の後に閉じられません。TrySplitFromFirst メソッドは SplitFromFirst メソッドに似ていますが、TrySplitFromFirst メソッドは操作が失敗した場合に例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.TrySplitFromFirst(sourceStream, 5, outStream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


## TrySplitFromFirst(string, int, HttpResponse) {#trysplitfromfirst_3}

ドキュメントを最初のページから指定された位置まで分割し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TrySplitFromFirst(string inputFile, int location, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソースファイル名。 |
| location | Int32 | 分割ポイント。 |
| response | HttpResponse | HttpResponse オブジェクト。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TrySplitFromFirst メソッドは SplitFromFirst メソッドに似ていますが、TrySplitFromFirst メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TrySplitFromFirst(Stream, int, HttpResponse) {#trysplitfromfirst_1}

ドキュメントを開始から指定された位置まで分割し、結果を HttpResponse オブジェクトに保存します。

```csharp
public bool TrySplitFromFirst(Stream inputStream, int location, HttpResponse response)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソースドキュメントのストリーム。 |
| location | Int32 | 分割ポイント。 |
| response | HttpResponse | 結果が保存される HttpResponse オブジェクト。 |

### 戻り値

操作が正常に完了した場合は true; それ以外の場合は false。

## 備考

TrySplitFromFirst メソッドは SplitFromFirst メソッドに似ていますが、TrySplitFromFirst メソッドは操作が失敗した場合に例外をスローしません。

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)