---
title: "TextAbsorber"
linktitle: "TextAbsorber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> テキストの吸収オブジェクトを表します。テキスト抽出を実行し、結果に {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p> <hr> <pre> 例。"
type: docs
weight: 4900
url: /ja/java/com.aspose.pdf/textabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber

```
public class TextAbsorber extends Object
```

<p> テキストの吸収オブジェクトを表します。テキスト抽出を実行し、{@code TextAbsorber.Text} オブジェクトを介して結果へのアクセスを提供します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for first page doc.getPages().get(1).accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> {@code TextAbsorber} オブジェクトは、Pdf ドキュメントまたはそのページからテキストを抽出するために使用されます。 </p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextAbsorber](#TextAbsorber--) | <p> {@code TextAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> テキスト抽出を実行し、抽出されたテキストに {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-) | <p> {@code TextAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> テキスト抽出を実行し、抽出されたテキストに {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> テキスト抽出を実行し、抽出されたテキストに {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p> |
| [TextAbsorber](#TextAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> テキスト抽出を実行し、抽出されたテキストに {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getErrors](#getErrors--) | {@code TextExtractionError} オブジェクトのリストです。テキスト抽出中に見つかったエラーに関する情報が含まれます。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| [getExtractionOptions](#getExtractionOptions--) | <p> テキスト抽出オプションを取得します。 </p> <hr> <pre> この例は、Pure テキストフォーマットモードを設定し、テキスト抽出を実行する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 抽出中に {@code TextExtractionOptions} でテキストフォーマットモードを定義できます。デフォルトモードは {@code TextExtractionOptions.TextFormattingMode.Pure} です。 </p> |
| [getText](#getText--) | <p> {@code TextAbsorber} が PDF ドキュメントまたはページから抽出したテキストを取得します。 </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | テキスト検索オプションを取得します。抽出されたテキストを限定する矩形を定義できます。デフォルトでは矩形は空です。つまり、ページの境界だけがテキスト抽出領域を定義します。 |
| [hasErrors](#hasErrors--) | この値は、テキスト抽出中にエラーが検出されたかどうかを示します。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | <p> テキスト抽出オプションを設定します。 </p> <hr> <pre> この例は、Pure テキストフォーマットモードを設定し、テキスト抽出を実行する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 抽出中に {@code TextExtractionOptions} でテキストフォーマットモードを定義できます。デフォルトモードは {@code TextExtractionOptions.TextFormattingMode.Pure} です。 </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | テキスト検索オプションを設定します。抽出されたテキストを限定する矩形を定義できます。デフォルトでは矩形は空です。つまり、ページの境界だけがテキスト抽出領域を定義します。 |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> 指定されたドキュメントからテキストを抽出します </p> <hr> <pre> この例は、PDF ドキュメントからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> 指定されたページからテキストを抽出します </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | <p> 指定された XForm からテキストを抽出します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // get the extracted text String extractedText = absorber.getText(); </pre> |

### TextAbsorber {#TextAbsorber--}
```
public TextAbsorber()
```

<p> {@code TextAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> テキスト抽出を実行し、抽出されたテキストに {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-}
<p> {@code TextAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> テキスト抽出を実行し、抽出されたテキストに {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextExtractionOptions-com.aspose.pdf.TextSearchOptions-}
<p> {@code TextAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> テキスト抽出を実行し、抽出されたテキストに {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p>

### TextAbsorber {#TextAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> {@code TextAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> テキスト抽出を実行し、抽出されたテキストに {@code TextAbsorber.Text} オブジェクトを介してアクセスできます。 </p>

### getErrors {#getErrors--}
```
public List < TextExtractionError > getErrors()
```

{@code TextExtractionError} オブジェクトのリストです。テキスト抽出中に見つかったエラーに関する情報が含まれます。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。

**Returns:**
TextExtractionError オブジェクトのリスト

### getExtractionOptions {#getExtractionOptions--}
```
public TextExtractionOptions getExtractionOptions()
```

<p> テキスト抽出オプションを取得します。 </p> <hr> <pre> この例は、Pure テキストフォーマットモードを設定し、テキスト抽出を実行する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 抽出中に {@code TextExtractionOptions} でテキストフォーマットモードを定義できます。デフォルトモードは {@code TextExtractionOptions.TextFormattingMode.Pure} です。 </p>

**Returns:**
TextExtractionOptions value

### getText {#getText--}
```
public String getText()
```

<p> {@code TextAbsorber} が PDF ドキュメントまたはページから抽出したテキストを取得します。 </p>

**Returns:**
String value <hr> <pre> この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre>

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

テキスト検索オプションを取得します。抽出されたテキストを限定する矩形を定義できます。デフォルトでは矩形は空です。つまり、ページの境界だけがテキスト抽出領域を定義します。

**Returns:**
TextSearchOptions value

### hasErrors {#hasErrors--}
```
public boolean hasErrors()
```

この値は、テキスト抽出中にエラーが検出されたかどうかを示します。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。

**Returns:**
ブール値

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
<p> テキスト抽出オプションを設定します。 </p> <hr> <pre> この例は、Pure テキストフォーマットモードを設定し、テキスト抽出を実行する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text with formatting TextAbsorber absorber = new TextAbsorber(); // set pure text formatting mode absorber.setExtractionOptions ( new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure)); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText(); </pre> <hr> <p> 抽出中に {@code TextExtractionOptions} でテキストフォーマットモードを定義できます。デフォルトモードは {@code TextExtractionOptions.TextFormattingMode.Pure} です。 </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
テキスト検索オプションを設定します。抽出されたテキストを限定する矩形を定義できます。デフォルトでは矩形は空です。つまり、ページの境界だけがテキスト抽出領域を定義します。

### visit {#visit-com.aspose.pdf.IDocument-}
<p> 指定されたドキュメントからテキストを抽出します </p> <hr> <pre> この例は、PDF ドキュメントからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> 指定されたページからテキストを抽出します </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.getPages(1)); // get the extracted text String extractedText = absorber.getText(); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
<p> 指定された XForm からテキストを抽出します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages absorber.visit(doc.Pages().get(1).getResources().getForms().get("Xform1")); // get the extracted text String extractedText = absorber.getText(); </pre>
