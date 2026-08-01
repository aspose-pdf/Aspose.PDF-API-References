---
title: "PdfFileEditor.TryExtract"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。入力ファイルからページを抽出し、新しい PDF ファイルとして保存します。"
type: docs
weight: 410
url: /ja/net/aspose.pdf.facades/pdffileeditor/tryextract/
---
## TryExtract(string, int, int, string) {#tryextract_1}

入力ファイルからページを抽出し、新しい Pdf ファイルとして保存します。

```csharp
public bool TryExtract(string inputFile, int startPage, int endPage, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイルパス。 |
| startPage | Int32 | 開始ページ番号。 |
| endPage | Int32 | 終了ページ番号。 |
| outputFile | String | 出力 Pdf ファイル パス。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TryExtract メソッドは Extract メソッドと同様ですが、操作が失敗した場合に TryExtract メソッドは例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", 3, 7, "output.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(string, int[], string) {#tryextract_2}

番号配列で指定されたページを抽出し、新しい PDF ファイルとして保存します。

```csharp
public bool TryExtract(string inputFile, int[] pageNumber, string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイルパス。 |
| pageNumber | Int32[] | 入力ファイルのページインデックス。 |
| outputFile | String | 出力ファイルパス。 |

### 戻り値

操作が正常に完了した場合は true、そうでない場合は false。

## 備考

TryExtract メソッドは Extract メソッドと同様ですが、操作が失敗した場合に TryExtract メソッドは例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
bool result = pfe.TryExtract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf");
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryExtract(Stream, int[], Stream) {#tryextract}

番号配列で指定されたページを抽出し、新しい Pdf ファイルとして保存します。

```csharp
public bool TryExtract(Stream inputStream, int[] pageNumber, Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力ファイル ストリーム。 |
| pageNumber | Int32[] | 入力ファイルのページインデックス。 |
| outputStream | Stream | 出力ファイルストリーム。 |

### 戻り値

成功した場合は true、失敗した場合は false。

## 備考

TryExtract メソッドは Extract メソッドと同様ですが、操作が失敗した場合に TryExtract メソッドは例外をスローしません。

## 例

```csharp
PdfFileEditor pfe = new PdfFileEditor();
Stream sourceStream = new FileStream("file1.pdf", FileMode.Open, FileAccess.Read);
Stream outStream = new FileStream("out.pdf", FileMode.Create, FileAccess.Write);
bool result = pfe.TryExtract(sourceStream, new int[] { 3, 5, 8 }, outStream);
```

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


