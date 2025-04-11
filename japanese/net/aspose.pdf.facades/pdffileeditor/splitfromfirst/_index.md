---
title: PdfFileEditor.SplitFromFirst
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。Pdf ファイルを最初のページから指定された位置まで分割し、前の部分を新しいファイルとして保存します。
type: docs
weight: 340
url: /ja/net/aspose.pdf.facades/pdffileeditor/splitfromfirst/
---
## SplitFromFirst(string, int, string) {#splitfromfirst_1}

Pdf ファイルを最初のページから指定された位置まで分割し、前の部分を新しいファイルとして保存します。

```csharp
public bool SplitFromFirst(string inputFile, int location, string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | ソース Pdf ファイル。 |
| location | Int32 | 分割ポイント。 |
| outputFile | String | 出力 Pdf ファイル。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.SplitFromFirst("input.pdf", 5, "out.pdf");
```

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SplitFromFirst(Stream, int, Stream) {#splitfromfirst}

開始から指定された位置まで分割し、出力ストリームに前の部分を保存します。

```csharp
public bool SplitFromFirst(Stream inputStream, int location, Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソース Pdf ファイル ストリーム。 |
| location | Int32 | 分割ポイント。 |
| outputStream | Stream | 出力ファイル ストリーム。 |

### 戻り値

成功の場合は true、失敗の場合は false。

## 備考

この操作の後、ストリームは閉じられません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
pfe.SplitFromFirst(sourceStream, 5, outStream);
```

### 関連項目

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)