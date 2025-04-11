---
title: PdfFileEditor.SplitToPages
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor メソッド。PDF ファイルを単一ページのドキュメントに分割します。
type: docs
weight: 370
url: /ja/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

PDF ファイルを単一ページのドキュメントに分割します。

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイル名。 |

### 戻り値

出力 PDF ストリーム。各ストリームは単一ページの PDF ドキュメントをバッファリングします。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

PDF ファイルを単一ページのドキュメントに分割します。

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 PDF ストリーム。 |

### 戻り値

ドキュメントのページを含むメモリストリームの配列。

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名テンプレートによって指定されます。

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイル名。 |
| fileNameTemplate | String | 結果ファイル名のテンプレート。%NUM% を含む必要があり、これはページ番号に置き換えられます。たとえば、c:/dir/page%NUM%.pdf が指定されている場合、結果ファイルは次の名前になります: c:/dir/page1.pdf, c:/dir/page2.pdf など。 |

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

PDF ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名テンプレートによって指定されます。

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| inputStream | Stream | ソースドキュメントのストリーム。 |
| fileNameTemplate | String | 結果ファイル名のテンプレート。%NUM% を含む必要があり、これはページ番号に置き換えられます。たとえば、c:/dir/page%NUM%.pdf が指定されている場合、結果ファイルは次の名前になります: c:/dir/page1.pdf, c:/dir/page2.pdf など。 |

### 参照

* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)