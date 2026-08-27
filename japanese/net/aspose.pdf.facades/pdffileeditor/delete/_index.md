---
title: "PdfFileEditor.Delete"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。番号配列で指定されたページを入力ファイルから削除し、新しい Pdf ファイルとして保存します。"
type: docs
weight: 270
url: /ja/net/aspose.pdf.facades/pdffileeditor/delete/
---
## Delete(string, int[], string) {#delete_1}

入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。

```csharp
public bool Delete(string inputFile, int[] pageNumber, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイルパス。 |
| pageNumber | Int32[] | 入力ファイルのページインデックス。 |
| outputFile | String | 出力ファイルパス。 |

### 戻り値

操作が成功した場合は True。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
pfe.Delete("input.pdf", new int[] { 2, 3 }, "out.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Stream, int[], Stream) {#delete}

入力ファイルから番号配列で指定されたページを削除し、新しい Pdf ファイルとして保存します。

```csharp
public bool Delete(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイル ストリーム。 |
| pageNumber | Int32[] | 入力ファイルのページインデックス。 |
| outputStream | Stream | 出力ファイルストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream intputStream = new FileStream("input.pdf", FileMode.Open, FileAccess.Read);
Stream outputStream = new FileStream("output.pdf", FileMode.Create, FileAccess.Write);
pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


