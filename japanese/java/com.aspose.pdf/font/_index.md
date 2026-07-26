---
title: "フォント"
linktitle: "フォント"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> フォントオブジェクトを表します。 </p> <hr> <pre> この例は、最初のページでテキストを検索し、最初の検索結果のフォントを変更する方法を示しています。 // Open document Document doc."
type: docs
weight: 1650
url: /ja/java/com.aspose.pdf/font/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Font

**All Implemented Interfaces:**
Cloneable

```
public final class Font extends Object implements Cloneable
```

<p> フォントオブジェクトを表します。 </p> <hr> <pre> The example demonstrates how to search text on first page and change font of a first search occurrence. // Open document Document doc = new Document(\"input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Create font and mark it to be embedded Font font = FontRepository.findFont(\"Arial\"); font.isEmbedded(true); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont( font); // Save document doc.save(\"output.pdf\"); </pre> @see TextFragmentAbsorber @see FontRepository @see IDocument

## メソッド

| メソッド | 説明 |
| --- | --- |
| [doesFontContainAllCharacters](#doesFontContainAllCharacters-java.lang.String-) | フォントが指定された文字を含むかどうかを判定します |
| [getActualFontName](#getActualFontName--) | <p> 初期化されている場合、{@code Font} オブジェクトの実際のフォント名を取得します。フォントが置き換えられている場合や PDF 用の内部名がある場合でも取得できます。初期化されていない場合は空文字列が返されます。 </p> |
| [getAscentPoint](#getAscentPoint-java.lang.String-float-) | 最大上昇点を測定します。 |
| [getBaseFont](#getBaseFont--) | PDF フォントオブジェクトの BaseFont 値を取得します。フォントの PostScript 名としても知られています。 |
| [getDecodedFontName](#getDecodedFontName--) | PDF フォント（主に中国語/日本語/韓国語フォント）の中には、特定のフォント名を持つものがあります。この名前は PDF フォントプロパティ "BaseFont" の値で、場合によっては十六進形式で表されることがあります。直接この名前を読むと読めない形式になることがあります。可読形式を得るには、そのフォント固有の規則に従ってフォント名をデコードする必要があります。このプロパティはデコードされたフォント名を返すため、読めない {@code FontName} に遭遇した場合に使用してください。プロパティ {@code FontName} が既に可読形式であれば、このプロパティは {@code FontName} と同じになりますので、フォント名を可読形式で取得したいすべての場合にこのプロパティを使用できます。 |
| [getDescentPoint](#getDescentPoint-java.lang.String-float-) | 最大下降点を測定します。 |
| [getFontName](#getFontName--) | <p> {@code Font} オブジェクトのフォント名を取得します。 </p> |
| [getFontOptions](#getFontOptions--) | フォントの動作を調整するための便利なプロパティ |
| [getIFont](#getIFont--) | <p> システムフォントオブジェクト。 </p> <hr> <p> 内部使用のみ </p> |
| [getIPdfFont](#getIPdfFont--) | <p> PDF フォントオブジェクト。 </p> <hr> <p> 内部使用のみ </p> |
| [getLastFontEmbeddingError](#getLastFontEmbeddingError--) | このメソッドの目的は、フォントの埋め込みに失敗した場合のエラー説明を返すことです。エラーがなければ空文字列を返します。 |
| [getType](#getType--) | フォントのタイプ名 |
| [isAccessible](#isAccessible--) | <p> フォントがシステムに存在（インストール）しているかどうかを示す値を取得します。 </p> |
| [isEmbedded](#isEmbedded--) | <p> フォントが埋め込まれているかどうかを示す値を取得します。IFont に基づくフォントは自動的にサブセット化され埋め込まれます。 </p> <hr> <pre> The following example demonstrates how to find a font, mark it as embedded, search text on the document's page and replace the text font. // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont("Arial"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document("D:\\\\Tests\\\\input.pdf"); // create TextFragmentAbsorber object to find all "hello world" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber("hello world"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [isSubset](#isSubset--) | <p> フォントがサブセットであるかどうかを示す値を取得します。IFont に基づくフォントは自動的にサブセット化され埋め込まれます。 </p> <hr> <pre> The example demonstrates how to search text on first page and get the value that indicates whether the font is a subset. // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println("the font is a subset"); </pre> |
| [measureString](#measureString-java.lang.String-float-) | 文字列を測定します。 |
| [save](#save-java.io.OutputStream-) | フォントをストリームに保存します。フォントは元のドキュメントの変換コピーでのみ使用されることを想定した中間的な TTF 形式で保存されることに注意してください。フォントファイルは元のドキュメントのコンテキスト外で使用されることは想定されていません。 |
| [setEmbedded](#setEmbedded-boolean-) | フォントが埋め込まれているかどうかを示す値を設定します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。 |
| [setSubset](#setSubset-boolean-) | フォントがサブセットかどうかを示す値を設定します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。 |

### doesFontContainAllCharacters {#doesFontContainAllCharacters-java.lang.String-}
フォントが指定された文字を含むかどうかを判定します

### getActualFontName {#getActualFontName--}
```
public String getActualFontName()
```

<p> 初期化されている場合、{@code Font} オブジェクトの実際のフォント名を取得します。フォントが置き換えられている場合や PDF 用の内部名がある場合でも取得できます。初期化されていない場合は空文字列が返されます。 </p>

**Returns:**
文字列値 <hr> <pre> この例は、最初のページでテキストを検索し、最初のテキスト出現箇所の実際のフォント名を表示する方法を示しています。 // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View actual font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getActualFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getAscentPoint {#getAscentPoint-java.lang.String-float-}
最大上昇点を測定します。

### getBaseFont {#getBaseFont--}
```
public final String getBaseFont()
```

PDF フォントオブジェクトの BaseFont 値を取得します。フォントの PostScript 名としても知られています。

**Returns:**
文字列値

### getDecodedFontName {#getDecodedFontName--}
```
public String getDecodedFontName()
```

PDF フォント（主に中国語/日本語/韓国語フォント）の中には、特定のフォント名を持つものがあります。この名前は PDF フォントプロパティ "BaseFont" の値で、場合によっては十六進形式で表されることがあります。直接この名前を読むと読めない形式になることがあります。可読形式を得るには、そのフォント固有の規則に従ってフォント名をデコードする必要があります。このプロパティはデコードされたフォント名を返すため、読めない {@code FontName} に遭遇した場合に使用してください。プロパティ {@code FontName} が既に可読形式であれば、このプロパティは {@code FontName} と同じになりますので、フォント名を可読形式で取得したいすべての場合にこのプロパティを使用できます。

**Returns:**
文字列値

### getDescentPoint {#getDescentPoint-java.lang.String-float-}
最大下降点を測定します。

### getFontName {#getFontName--}
```
public String getFontName()
```

<p> {@code Font} オブジェクトのフォント名を取得します。 </p>

**Returns:**
文字列値 <hr> <pre> この例は、最初のページでテキストを検索し、最初のテキスト出現箇所のフォント名を表示する方法を示しています。 // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font name of first text occurrence System.out.println(absorber.getTextFragments().get_Item(1).getTextState().getFont().getFontName()); </pre> @see TextFragmentAbsorber @see IDocument

### getFontOptions {#getFontOptions--}
```
public IFontOptions getFontOptions()
```

フォントの動作を調整するための便利なプロパティ

**Returns:**
IFontOptions オブジェクト

### getIFont {#getIFont--}
```
public com.aspose.font.IFont getIFont()
```

<p> システムフォントオブジェクト。 </p> <hr> <p> 内部使用のみ </p>

**Returns:**
IFont オブジェクト

### getIPdfFont {#getIPdfFont--}
```
public com.aspose.pdf.engine.commondata.text.fonts.IPdfFont getIPdfFont()
```

<p> PDF フォントオブジェクト。 </p> <hr> <p> 内部使用のみ </p>

**Returns:**
IPdfFont オブジェクト

### getLastFontEmbeddingError {#getLastFontEmbeddingError--}
```
public String getLastFontEmbeddingError()
```

このメソッドの目的は、フォントの埋め込みに失敗した場合のエラー説明を返すことです。エラーがなければ空文字列を返します。

**Returns:**
エラーの説明

### getType {#getType--}
```
public String getType()
```

フォントのタイプ名

**Returns:**
String オブジェクト

### isAccessible {#isAccessible--}
```
public boolean isAccessible()
```

<p> フォントがシステムに存在（インストール）しているかどうかを示す値を取得します。 </p>

**Returns:**
ブール値 <hr> <pre> この例は、最初のページでテキストを検索し、フォントがシステムにインストールされているかどうかを示す値を取得する方法を示しています。 // Open document Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if (absorber.getTextFragments().get_Item(1).getTextState().getFont() .isAccessible()) System.out.println(\"the font is installed in the system\"); </pre> <hr> <p> システムで見つからないフォントに対しては、一部の操作は利用できません。 </p>

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

<p> フォントが埋め込まれているかどうかを示す値を取得します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。 </p> <hr> <pre> 以下の例は、フォントを検索し、埋め込みとしてマークし、ドキュメントのページ上でテキストを検索してフォントを置換する方法を示しています。 // Create font and mark it to be embedded com.aspose.pdf.Font font = com.aspose.pdf.FontRepository.findFont(\"Arial\"); font.isEmbedded ( true); // open document com.aspose.pdf.Document doc = new com.aspose.pdf.Document(\"D:\\Tests\\input.pdf\"); // create TextFragmentAbsorber object to find all \"hello world\" text occurrences com.aspose.pdf.TextFragmentAbsorber absorber = new com.aspose.pdf.TextFragmentAbsorber(\"hello world\"); // accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // change font for the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // save document doc.save(\"D:\\Tests\\output.pdf\"); </pre>

**Returns:**
ブール値 @see TextFragmentAbsorber @see FontRepository @see IDocument

### isSubset {#isSubset--}
```
public boolean isSubset()
```

<p> フォントがサブセットかどうかを示す値を取得します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。 </p> <hr> <pre> この例は、最初のページでテキストを検索し、フォントがサブセットかどうかを示す値を取得する方法を示しています。 // Open document Document doc = new Document(\"D:\\Tests\\input.pdf\"); // Create TextFragmentAbsorber object to find all \"hello world\" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // View font's IsSubset value of first text occurrence if(absorber.TextFragments[1].TextState.Font.IsSubset) System.out.println(\"the font is a subset\"); </pre>

**Returns:**
ブール値 @see TextFragmentAbsorber @see IDocument

### measureString {#measureString-java.lang.String-float-}
文字列を測定します。

### save {#save-java.io.OutputStream-}
フォントをストリームに保存します。フォントは元のドキュメントの変換コピーでのみ使用されることを想定した中間的な TTF 形式で保存されることに注意してください。フォントファイルは元のドキュメントのコンテキスト外で使用されることは想定されていません。

### setEmbedded {#setEmbedded-boolean-}
```
public void setEmbedded(boolean value)
```

フォントが埋め込まれているかどうかを示す値を設定します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSubset {#setSubset-boolean-}
```
public void setSubset(boolean value)
```

フォントがサブセットかどうかを示す値を設定します。IFont に基づくフォントは自動的にサブセット化され、埋め込まれます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
