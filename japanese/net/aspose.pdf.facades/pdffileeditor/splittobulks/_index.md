---
title: "PdfFileEditor.SplitToBulks"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor のメソッド。PDF ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにできます。"
type: docs
weight: 350
url: /ja/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Pdf ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにすることができます。

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイル。 |
| numberOfPage | Int32[][] | ドキュメントの開始ページと終了ページを示す double 要素の配列を含む配列。 |

### 戻り値

出力 PDF ストリーム。各ストリームは PDF ドキュメントをバッファします。

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Pdf ファイルを複数のドキュメントに分割します。ドキュメントは単一ページまたは複数ページにすることができます。

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| numberOfPage | Int32[][] | 各ドキュメントの開始ページと終了ページ。 |

### 戻り値

出力 PDF ストリーム。各ストリームは PDF ドキュメントをバッファします。

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


