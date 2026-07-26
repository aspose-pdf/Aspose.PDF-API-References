---
title: "TextFragmentAbsorber"
linktitle: "TextFragmentAbsorber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> テキストフラグメントの吸収オブジェクトを表します。テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p>."
type: docs
weight: 5120
url: /ja/java/com.aspose.pdf/textfragmentabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextAbsorber com.aspose.pdf.TextFragmentAbsorber, com.aspose.pdf.TextAbsorber, com.aspose.pdf.TextFragmentAbsorber

```
public final class TextFragmentAbsorber extends TextAbsorber
```

<p> テキストフラグメントの吸収オブジェクトを表します。テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストとフォントを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Find font that will be used to change document text font com.aspose.pdf.Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text and font of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre> <hr> <p> {@code TextFragmentAbsorber} オブジェクトは主にテキスト検索シナリオで使用されます。検索が完了すると、出現箇所は {@code TextFragment} オブジェクトとして表され、これらは {@code TextFragmentAbsorber.TextFragments} コレクションに含まれます。{@code TextFragment} オブジェクトは検索結果のテキスト、テキストプロパティへのアクセスを提供し、テキストの編集やテキスト状態（フォント、フォントサイズ、色など）の変更を可能にします。 </p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextFragmentAbsorber](#TextFragmentAbsorber--) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |
| [TextFragmentAbsorber](#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-) | <p> {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。これは、ドキュメントまたはページのすべてのテキストセグメントを検索します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページでテキストを検索し、テキストを置換する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Find font that will be used to change document text font Font font = FontRepository.findFont(\"Arial\"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all \"hello world\" text occurrences absorber.setPhrase ( \"hello world\"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( \"hi world\"); // Save document doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできます。 </p> |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [applyForAllFragments](#applyForAllFragments-float-) | 吸収されたすべてのテキストフラグメントにフォントサイズを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループするよりも高速に動作します。そうでない場合は、ループと同様に動作します。 |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-) | 吸収されたすべてのテキストフラグメントにフォントを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループするよりも高速に動作します。そうでない場合は、ループと同様に動作します。 |
| [applyForAllFragments](#applyForAllFragments-com.aspose.pdf.Font-float-) | 吸収されたすべてのテキストフラグメントにフォントとサイズを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループするよりも高速に動作します。そうでない場合は、ループと同様に動作します。 |
| [getErrors](#getErrors--) | {@code TextExtractionError} オブジェクトのリストです。テキスト抽出中に見つかったエラーに関する情報が含まれます。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| [getExtractionOptions](#getExtractionOptions--) | テキスト抽出オプションを取得します。 |
| [getPhrase](#getPhrase--) | <p> {@code TextFragmentAbsorber} が PDF ドキュメントまたはページで検索するフレーズを取得します。 </p> |
| [getRegexResults](#getRegexResults--) | 検索結果の辞書を取得します。キーは System.Text.RegularExpressions.Regex クラス、値は {@link TextFragment} です。例は、正規表現の配列を使用して最初の PDF ドキュメントページでテキストを検索する方法を示しています。 // Open document Document doc = new Document(\"input.pdf\"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults(); |
| [getRegexResultsInternal](#getRegexResultsInternal--) |  |
| [getText](#getText--) | PDF ドキュメントまたはページで {@code TextAbsorber} が抽出したテキストを取得します。 |
| [getTextEditOptions](#getTextEditOptions--) | テキスト編集オプションを取得します。これらのオプションは、要求されたシンボルをフォントで書き込めない場合の特別な動作を定義します。 |
| [getTextFragments](#getTextFragments--) | <p> {@code TextFragment} オブジェクトとして表される検索結果のコレクションを取得します。 </p> |
| [getTextReplaceOptions](#getTextReplaceOptions--) | テキスト置換オプションを取得します。オプションは、フラグメントテキストが短くまたは長く置換される際の動作を定義します。 |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> 検索オプションを取得します。これらのオプションにより、正規表現を使用した検索が可能になります。 </p> |
| [hasErrors_Fragment](#hasErrors_Fragment--) | この値は、テキスト抽出中にエラーが検出されたかどうかを示します。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。 |
| [removeAllText](#removeAllText-com.aspose.pdf.Document-) | ドキュメントからすべてのテキストを削除します。 |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-) | 指定されたページからすべてのテキストを削除します。 |
| [removeAllText](#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 指定されたページの指定された矩形領域内のテキストを削除します。 |
| [reset](#reset--) | この {@code TextFragmentAbsorber} オブジェクトの TextFragments コレクションをクリアします。 |
| [setExtractionOptions](#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-) | テキスト抽出オプションを設定します。 |
| [setPhrase](#setPhrase-java.lang.String-) | <p> {@code TextFragmentAbsorber} が PDF ドキュメントまたはページで検索するフレーズを設定します。 </p> |
| [setTextEditOptions](#setTextEditOptions-com.aspose.pdf.TextEditOptions-) | テキスト編集オプションを設定します。これらのオプションは、要求されたシンボルがフォントで表現できない場合の特別な動作を定義します。 |
| [setTextFragments](#setTextFragments-com.aspose.pdf.TextFragmentCollection-) | <p> {@code TextFragment} オブジェクトで表される検索結果のコレクションを設定します。 </p> |
| [setTextReplaceOptions](#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-) | テキスト置換オプションを設定します。これらのオプションは、フラグメントテキストがより短くまたは長く置換される際の動作を定義します。 |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> 検索オプションを設定します。これらのオプションにより、正規表現を使用した検索が可能になります。 </p> |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> 指定されたドキュメントで検索を実行します。 </p> <hr> <pre> The example demonstrates how to find text on PDF document and replace text of all search occurrences. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> 指定されたページで検索を実行します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page absorber.visit(doc.getPages().get(1)); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.XForm-) | 指定されたフォームオブジェクトで検索を実行します。 |

### TextFragmentAbsorber {#TextFragmentAbsorber--}
```
public TextFragmentAbsorber()
```

<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern:A-com.aspose.pdf.TextSearchOptions-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextEditOptions-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.util.regex.Pattern-com.aspose.pdf.TextSearchOptions-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextEditOptions-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-java.lang.String-com.aspose.pdf.TextSearchOptions-com.aspose.pdf.TextEditOptions-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### TextFragmentAbsorber {#TextFragmentAbsorber-com.aspose.pdf.TextEditOptions-}
<p> ドキュメントまたはページのすべてのテキストセグメントを検索する {@code TextFragmentAbsorber} の新しいインスタンスを初期化します。 </p> <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace the text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // Make the absorber to search all "hello world" text occurrences absorber.setPhrase ( "hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of the first text occurrence absorber.getTextFragments().get_Item(1).setText ( "hi world"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> <hr> <p> テキスト検索を実行し、検索結果へ {@code TextFragmentAbsorber.TextFragments} コレクションを介してアクセスできるようにします。 </p>

### applyForAllFragments {#applyForAllFragments-float-}
```
public void applyForAllFragments(float fontSize)
```

吸収されたすべてのテキストフラグメントにフォントサイズを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループするよりも高速に動作します。そうでない場合は、ループと同様に動作します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontSize |  | テキストのフォントサイズ。 |

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-}
吸収されたすべてのテキストフラグメントにフォントを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループするよりも高速に動作します。そうでない場合は、ループと同様に動作します。

### applyForAllFragments {#applyForAllFragments-com.aspose.pdf.Font-float-}
吸収されたすべてのテキストフラグメントにフォントとサイズを適用します。ページ上のすべてのフラグメントが吸収されている場合、フラグメントをループするよりも高速に動作します。そうでない場合は、ループと同様に動作します。

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

テキスト抽出オプションを取得します。

**Returns:**
TextExtractionOptions オブジェクト

### getPhrase {#getPhrase--}
```
public String getPhrase()
```

<p> {@code TextFragmentAbsorber} が PDF ドキュメントまたはページで検索するフレーズを取得します。 </p>

**Returns:**
文字列値 <hr> <pre> The example demonstrates how to perform search text several times and perform text replacements. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // search another word and replace it absorber.setPhrase ( "world"); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "John"); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getRegexResults {#getRegexResults--}
```
public final HashMap < Pattern , TextFragmentCollection > getRegexResults()
```

検索結果の辞書を取得します。キーは System.Text.RegularExpressions.Regex クラス、値は {@link TextFragment} です。例は、正規表現の配列を使用して最初の PDF ドキュメントページでテキストを検索する方法を示しています。 // Open document Document doc = new Document(\"input.pdf\"); Regex regexes = new Regex[] { new Regex( RegexOptions.IgnoreCase), new Regex( RegexOptions.IgnoreCase), }; // Create TextFragmentAbsorber object that searches all words starting 'h' and ending 'o' using regular expression. TextFragmentAbsorber absorber = new TextFragmentAbsorber(regexes, new TextSearchOptions(true)); doc.getPages().get_Item(1).accept(absorber); // Get results Dictionary results = absorber.getRegexResults();

**Returns:**
Dictionary インスタンス

### getRegexResultsInternal {#getRegexResultsInternal--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.ms.System.Text.RegularExpressions.Regex, TextFragmentCollection > getRegexResultsInternal()
```



### getText {#getText--}
```
public String getText()
```

PDF ドキュメントまたはページで {@code TextAbsorber} が抽出したテキストを取得します。

**Returns:**
文字列値 この例は、PDF ドキュメントのすべてのページからテキストを抽出する方法を示しています。 // open document Document doc = new Document(inFile); // create TextAbsorber object to extract text TextAbsorber absorber = new TextAbsorber(); // accept the absorber for all document's pages doc.getPages().accept(absorber); // get the extracted text String extractedText = absorber.getText();

### getTextEditOptions {#getTextEditOptions--}
```
public TextEditOptions getTextEditOptions()
```

テキスト編集オプションを取得します。これらのオプションは、要求されたシンボルをフォントで書き込めない場合の特別な動作を定義します。

**Returns:**
TextEditOptions オブジェクト

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

<p> {@code TextFragment} オブジェクトとして表される検索結果のコレクションを取得します。 </p>

**Returns:**
TextFragmentCollection オブジェクト <hr> <pre> The example demonstrates how to find text on the first PDF document page and replace all search occurrences with new text. // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Find font that will be used to change document text font Font font = FontRepository.findFont("Arial"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get(1).accept(absorber); // Change text of all search occurrences for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getTextReplaceOptions {#getTextReplaceOptions--}
```
public TextReplaceOptions getTextReplaceOptions()
```

テキスト置換オプションを取得します。オプションは、フラグメントテキストが短くまたは長く置換される際の動作を定義します。

**Returns:**
TextReplaceOptions 値

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> 検索オプションを取得します。これらのオプションにより、正規表現を使用した検索が可能になります。 </p>

**Returns:**
TextSearchOptions object <hr> <pre> この例は、正規表現を使用してテキスト検索を実行する方法を示しています。 // ドキュメントを開く Document doc = new Document("D:\\Tests\\input.pdf"); // TextFragmentAbsorber オブジェクトを作成 TextFragmentAbsorber absorber = new TextFragmentAbsorber(); // 正規表現を使用して、'h'で始まり'o'で終わるすべての単語を検索するようにアブソーバーを設定 absorber.setPhrase ( "h\w*?o"); // "hello"という単語を見つけて "Hi" に置き換える absorber.setTextSearchOptions ( new TextSearchOptions(true)); doc.getPages().get(1).accept(absorber); absorber.getTextFragments().get_Item(1).setText ( "Hi"); // ドキュメントを保存 doc.save("D:\\Tests\\output.pdf"); </pre>

### hasErrors_Fragment {#hasErrors_Fragment--}
```
public boolean hasErrors_Fragment()
```

この値は、テキスト抽出中にエラーが検出されたかどうかを示します。エラーの検索は TextSearchOptions.LogTextExtractionErrors = true の場合にのみ実行され、パフォーマンスが低下する可能性があります。

**Returns:**
ブール値

### removeAllText {#removeAllText-com.aspose.pdf.Document-}
ドキュメントからすべてのテキストを削除します。

### removeAllText {#removeAllText-com.aspose.pdf.Page-}
指定されたページからすべてのテキストを削除します。

### removeAllText {#removeAllText-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
指定されたページの指定された矩形領域内のテキストを削除します。

### reset {#reset--}
```
public void reset()
```

この {@code TextFragmentAbsorber} オブジェクトの TextFragments コレクションをクリアします。

### setExtractionOptions {#setExtractionOptions-com.aspose.pdf.TextExtractionOptions-}
テキスト抽出オプションを設定します。

### setPhrase {#setPhrase-java.lang.String-}
<p> {@code TextFragmentAbsorber} が PDF ドキュメントまたはページで検索するフレーズを設定します。 </p>

### setTextEditOptions {#setTextEditOptions-com.aspose.pdf.TextEditOptions-}
テキスト編集オプションを設定します。これらのオプションは、要求されたシンボルがフォントで表現できない場合の特別な動作を定義します。

### setTextFragments {#setTextFragments-com.aspose.pdf.TextFragmentCollection-}
<p> {@code TextFragment} オブジェクトで表される検索結果のコレクションを設定します。 </p>

### setTextReplaceOptions {#setTextReplaceOptions-com.aspose.pdf.TextReplaceOptions-}
テキスト置換オプションを設定します。これらのオプションは、フラグメントテキストがより短くまたは長く置換される際の動作を定義します。

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> 検索オプションを設定します。これらのオプションにより、正規表現を使用した検索が可能になります。 </p>

### visit {#visit-com.aspose.pdf.IDocument-}
<p> 指定されたドキュメントで検索を実行します。 </p> <hr> <pre> この例は、PDF ドキュメント上のテキストを検索し、すべての検索結果のテキストを置換する方法を示しています。 // ドキュメントを開く Document doc = new Document("D:\\Tests\\input.pdf"); // ドキュメントのテキストフォントを変更するために使用されるフォントを検索 Font font = FontRepository.findFont("Arial"); // "hello world" のすべてのテキスト出現を検索するために TextFragmentAbsorber オブジェクトを作成 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 最初のページでアブソーバーを受け入れる absorber.visit(doc); // 最初のテキスト出現のテキストを変更 absorber.getTextFragments().get_Item(1).setText ( "hi world"); // ドキュメントを保存 doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> 指定されたページで検索を実行します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページ上のテキストを検索し、テキストを置換する方法を示しています。 // ドキュメントを開く Document doc = new Document("D:\\Tests\\input.pdf"); // ドキュメントのテキストフォントを変更するために使用されるフォントを検索 Font font = FontRepository.findFont("Arial"); // "hello world" のすべてのテキスト出現を検索するために TextFragmentAbsorber オブジェクトを作成 TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // 最初のページでアブソーバーを受け入れる absorber.visit(doc.getPages().get(1)); // すべての検索結果のテキストを変更 for (TextFragment textFragment : {@code (Iterable<TextFragment>)}absorber.getTextFragments()) { textFragment.setText ( "hi world"); } // ドキュメントを保存 doc.save("D:\\Tests\\output.pdf"); </pre>

### visit {#visit-com.aspose.pdf.XForm-}
指定されたフォームオブジェクトで検索を実行します。
