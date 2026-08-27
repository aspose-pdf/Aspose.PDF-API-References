---
title: "PdfContentEditor.ReplaceText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。指定された Page の PDF ファイル内のテキストを置換します。置換するテキストのフォントファミリや色は TextState オブジェクトで指定できます。"
type: docs
weight: 450
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

指定された Page の PDF ファイル内のテキストを置換します。[`TextState`](../../../aspose.pdf.text/textstate/) オブジェクト（フォントファミリ、色）で置換するテキストを指定できます。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcString | String | 置換される文字列です。 |
| thePage | Int32 | ページ番号 (0 は「すべてのページ」を意味します)。 |
| destString | String | 置換された文字列。 |
| textState | TextState | テキスト状態 (テキストカラー、フォントなど)。 |

### 戻り値

置換が行われた場合は true を返します。

## 例

この例では、PDF ドキュメントの最初のページのテキストを置換し、新しいテキストのために [`TextState`](../../../aspose.pdf.text/textstate/) テキストプロパティを設定する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// フォントを作成し、埋め込み対象としてマークします。
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// テキストを編集するために PdfContentEditor オブジェクトを作成する
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// textState オブジェクトを作成する
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// 指定されたフォントでテキストを変更する
editor.ReplaceText("hello world", 1, "hi world", textState);

// ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

PDFファイル内のテキストを置き換えます。

```csharp
public bool ReplaceText(string srcString, string destString)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcString | String | 置換される文字列です。 |
| destString | String | 文字列を置換しています。 |

### 戻り値

置換が行われた場合は true を返します。

## 例

この例では、PDF ドキュメントのテキストを置換する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// テキストを編集するために PdfContentEditor オブジェクトを作成する
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// テキストを変更する 
editor.ReplaceText("hello world", "hi world");

// ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

指定されたページの PDF ファイル内のテキストを置き換えます。

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcString | String | 置換される文字列。 |
| thePage | Int32 | ページ番号 (0 はすべてのページ) |
| destString | String | 文字列を置換しています。 |

### 戻り値

置換が行われた場合は true を返します。

## 例

この例では、指定されたページの PDF ドキュメントのテキストを置換する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// テキストを編集するために PdfContentEditor オブジェクトを作成する
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// テキストを変更する 
editor.ReplaceText("hello world", 1, "hi world");

// ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

指定された [`TextState`](../../../aspose.pdf.text/textstate/) オブジェクトを使用して PDF ファイルのテキストを置換します。

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcString | String | 置換する文字列 |
| destString | String | 文字列を置換中 |
| textState | TextState | テキスト状態 (テキストカラー、フォントなど) |

### 戻り値

置換が行われた場合は true を返します。

## 例

この例では、テキストを置換し、新しいテキストのために [`TextState`](../../../aspose.pdf.text/textstate/) テキストプロパティを設定する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// フォントを作成し、埋め込み対象としてマークします。
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// テキストを編集するために PdfContentEditor オブジェクトを作成する
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// textState オブジェクトを作成する
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// 指定されたフォントでテキストを変更する
editor.ReplaceText("hello world", "hi world", textState);

// ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

PDF ファイル内のテキストを置換し、フォントサイズを設定します。

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| srcString | String | 置換する文字列。 |
| destString | String | 文字列を置換しています。 |
| fontSize | Int32 | フォントサイズ。 |

### 戻り値

置換が行われた場合は true を返します。

## 例

この例では、テキストを置換し、新しいテキストのフォントサイズを設定する方法を示しています。

```csharp
// ドキュメントを開く
Document doc = new Document(inFile);

// フォントを作成し、埋め込み対象としてマークします。
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// テキストを編集するために PdfContentEditor オブジェクトを作成する
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 指定されたフォントでテキストを変更する
editor.ReplaceText("hello world", "hi world", 14);

// ドキュメントを保存する
doc.Save(outFile);
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


