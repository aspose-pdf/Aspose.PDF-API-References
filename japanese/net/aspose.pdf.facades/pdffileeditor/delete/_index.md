---
title: PdfFileEditor.Delete
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。入力ファイルから指定されたページを番号配列で削除し、新しい Pdf ファイルとして保存します。
type: docs
weight: 270
url: /ja/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

入力ファイルから指定されたページを番号配列で削除し、新しい Pdf ファイルとして保存します。

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイルのパス。 |
| pageNumber | Int32[] | 入力ファイルのページのインデックス。 |
| outputFile | String | 出力ファイルのパス。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

入力ファイルから指定されたページを番号配列で削除し、新しい Pdf ファイルとして保存します。

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイルのストリーム。 |
| pageNumber | Int32[] | 入力ファイルのページのインデックス。 |
| outputStream | Stream | 出力ファイルのストリーム。 |

### 戻り値

成功の場合は True、失敗の場合は False。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)