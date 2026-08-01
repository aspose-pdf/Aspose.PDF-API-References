---
title: "PdfFileEditor.SplitToPages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfFileEditor メソッド。PDF ファイルを単一ページのドキュメントに分割します。"
type: docs
weight: 370
url: /ja/net/aspose.pdf.facades/pdffileeditor/splittopages/
---
## SplitToPages(string) {#splittopages_1}

PDF ファイルを単一ページのドキュメントに分割します。

```csharp
public MemoryStream[] SplitToPages(string inputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力 PDF ファイル名。 |

### 戻り値

出力 PDF ストリーム。各ストリームは単一ページの PDF ドキュメントをバッファします。

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream) {#splittopages}

Pdf ファイルを単一ページのドキュメントに分割します。

```csharp
public MemoryStream[] SplitToPages(Stream inputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 入力 Pdf ストリーム。 |

### 戻り値

ドキュメントのページを含むメモリストリームの配列。

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(string, string) {#splittopages_3}

Pdf ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名 temaplate によって指定されます。

```csharp
public void SplitToPages(string inputFile, string fileNameTemplate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputFile | String | 入力ファイル名。 |
| fileNameTemplate | String | 結果ファイル名のテンプレート。%NUM% を含める必要があり、ページ番号に置き換えられます。例えば、c:/dir/page%NUM%.pdf を指定すると、結果ファイルは次のような名前になります：c:/dir/page1.pdf、c:/dir/page2.pdf など。 |

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SplitToPages(Stream, string) {#splittopages_2}

Pdf ファイルを単一ページのドキュメントに分割し、指定されたパスに保存します。パスはフィールド名 temaplate によって指定されます。

```csharp
public void SplitToPages(Stream inputStream, string fileNameTemplate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputStream | Stream | 元ドキュメントのストリーム。 |
| fileNameTemplate | String | 結果ファイル名のテンプレート。%NUM% を含める必要があり、ページ番号に置き換えられます。例えば、c:/dir/page%NUM%.pdf を指定すると、結果ファイルは次のような名前になります：c:/dir/page1.pdf、c:/dir/page2.pdf など。 |

### 関連項目

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


