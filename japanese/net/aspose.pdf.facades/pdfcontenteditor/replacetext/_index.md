---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。指定されたページの PDF ファイル内のテキストを置き換えます。置き換えられたテキストには TextState オブジェクトのフォントファミリーの色を指定できます
type: docs
weight: 450
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

指定されたページの PDF ファイル内のテキストを置き換えます。 [`TextState`](../../../aspose.pdf.text/textstate/) オブジェクト（フォントファミリー、色）を置き換えられたテキストに指定できます。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcString | String | 置き換えられる文字列。 |
| thePage | Int32 | ページ番号（0 は「すべてのページ」を意味します）。 |
| destString | String | 置き換えられた文字列。 |
| textState | TextState | テキスト状態（テキストの色、フォントなど）。 |

### 戻り値

置き換えが行われた場合は true を返します。

## 例

この例では、PDF ドキュメントの最初のページのテキストを置き換え、新しいテキストのために [`TextState`](../../../aspose.pdf.text/textstate/) テキストプロパティを設定する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### 関連項目

* クラス [TextState](../../../aspose.pdf.text/textstate/)
* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

PDF ファイル内のテキストを置き換えます。

```csharp
public bool ReplaceText(string srcString, string destString)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcString | String | 置き換えられる文字列。 |
| destString | String | 置き換え文字列。 |

### 戻り値

置き換えが行われた場合は true を返します。

## 例

この例では、PDF ドキュメント内のテキストを置き換える方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

指定されたページの PDF ファイル内のテキストを置き換えます。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcString | String | 置き換えられる文字列。 |
| thePage | Int32 | ページ番号（0 はすべてのページを意味します） |
| destString | String | 置き換え文字列。 |

### 戻り値

置き換えが行われた場合は true を返します。

## 例

この例では、指定されたページの PDF ドキュメント内のテキストを置き換える方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

指定された [`TextState`](../../../aspose.pdf.text/textstate/) オブジェクトを使用して PDF ファイル内のテキストを置き換えます。

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcString | String | 置き換えられる文字列 |
| destString | String | 置き換え文字列 |
| textState | TextState | テキスト状態（テキストの色、フォントなど） |

### 戻り値

置き換えが行われた場合は true を返します。

## 例

この例では、テキストを置き換え、新しいテキストのために [`TextState`](../../../aspose.pdf.text/textstate/) テキストプロパティを設定する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### 関連項目

* クラス [TextState](../../../aspose.pdf.text/textstate/)
* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

PDF ファイル内のテキストを置き換え、フォントサイズを設定します。

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| srcString | String | 置き換えられる文字列。 |
| destString | String | 置き換え文字列。 |
| fontSize | Int32 | フォントサイズ。 |

### 戻り値

置き換えが行われた場合は true を返します。

## 例

この例では、テキストを置き換え、新しいテキストのためにフォントサイズを設定する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### 関連項目

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)