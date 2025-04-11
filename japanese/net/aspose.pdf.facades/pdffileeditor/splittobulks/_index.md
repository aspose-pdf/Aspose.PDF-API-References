---
title: PdfFileEditor.SplitToBulks
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。Pdf ファイルを複数のドキュメントに分割します。ドキュメントは単ページまたは複数ページです。
type: docs
weight: 350
url: /ja/net/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## SplitToBulks(string, int[][]) {#splittobulks_1}

Pdf ファイルを複数のドキュメントに分割します。ドキュメントは単ページまたは複数ページです。

```csharp
public MemoryStream[] SplitToBulks(string inputFile, int[][] numberOfPage)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイル。 |
| numberOfPage | Int32[][] | ドキュメントの開始ページと終了ページを含む二重要素の配列。 |

### 戻り値

出力 PDF ストリーム、それぞれのストリームは PDF ドキュメントをバッファリングします。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SplitToBulks(Stream, int[][]) {#splittobulks}

Pdf ファイルを複数のドキュメントに分割します。ドキュメントは単ページまたは複数ページです。

```csharp
public MemoryStream[] SplitToBulks(Stream inputStream, int[][] numberOfPage)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |
| numberOfPage | Int32[][] | 各ドキュメントの開始ページと終了ページ。 |

### 戻り値

出力 PDF ストリーム、それぞれのストリームは PDF ドキュメントをバッファリングします。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)