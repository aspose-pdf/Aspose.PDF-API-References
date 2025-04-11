---
title: PdfFileEditor.SplitToEnd
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。指定された位置から分割し、後ろの部分を新しいファイルとして保存します
type: docs
weight: 360
url: /ja/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

指定された位置から分割し、後ろの部分を新しいファイルストリームとして保存します。

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソース Pdf ファイルストリーム。 |
| location | Int32 | 分割位置。 |
| outputStream | Stream | 出力 Pdf ファイルストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 備考

この操作の後、ストリームは CloseConcatedStreams が指定されない限り閉じられません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

位置から分割し、後ろの部分を新しいファイルとして保存します。

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソース Pdf ファイル。 |
| location | Int32 | 分割位置。 |
| outputFile | String | 出力 Pdf ファイルパス。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

指定された位置から分割し、後ろの部分を新しいファイルストリームとして保存します。

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソース Pdf ファイルストリーム。 |
| location | Int32 | 分割位置。 |
| outputStream | Stream | 出力 Pdf ファイルストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 備考

この操作の後、ストリームは CloseConcatedStreams が指定されない限り閉じられません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)