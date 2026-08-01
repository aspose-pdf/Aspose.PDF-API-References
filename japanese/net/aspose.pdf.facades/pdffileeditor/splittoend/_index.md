---
title: "PdfFileEditor.SplitToEnd"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。 location から分割し、後半部分を新しいファイルとして保存します。"
type: docs
weight: 360
url: /ja/net/aspose.pdf.facades/pdffileeditor/splittoend/
---
## SplitToEnd(string, int, string) {#splittoend_1}

指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソース Pdf ファイル ストリーム。 |
| location | Int32 | 分割位置。 |
| outputStream | Stream | 出力 Pdf ファイル ストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

この操作の後、CloseConcatedStreams が指定されていない限り、ストリームは閉じられません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(string, int, string) {#splittoend_2}

位置から分割し、後半部分を新しいファイルとして保存します。

```csharp
public bool SplitToEnd(string inputFile, int location, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | ソース Pdf ファイル。 |
| location | Int32 | 分割位置。 |
| outputFile | String | 出力 Pdf ファイル パス。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitToEnd("input.pdf", 5, "out.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToEnd(Stream, int, Stream) {#splittoend}

指定された位置から分割し、後半部分を新しいファイルストリームとして保存します。

```csharp
public bool SplitToEnd(Stream inputStream, int location, Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソース Pdf ファイル ストリーム。 |
| location | Int32 | 分割位置。 |
| outputStream | Stream | 出力 Pdf ファイル ストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

この操作の後、CloseConcatedStreams が指定されていない限り、ストリームは閉じられません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitToEnd(sourceStream, 5, outStream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


