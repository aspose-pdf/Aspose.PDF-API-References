---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> フォント検索を実行します。システムにインストールされているフォントと標準 PDF フォントを検索します。また、カスタムフォントを開く機能も提供します。 </p> <hr> <pre> この例はデモンストレーションです。</pre>"
type: docs
weight: 1690
url: /ja/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> フォント検索を実行します。システムにインストールされているフォントと標準 PDF フォントを検索します。また、カスタムフォントを開く機能も提供します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示します。 // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | フォントへのパスをもう一つ追加します。 |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> 指定されたフォントでシステムフォントを追加します。 </p> <hr> <pre> この例はシステムフォントを追加する方法を示します。 InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> 指定されたフォント名でフォントを検索し、返します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示します。 // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> 指定されたフォント名でフォントを検索し、大小文字の区別を無視または尊重して返します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示します。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> 指定されたフォント名とフォントスタイルでフォントを検索し、返します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示します。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> 指定されたフォント名とフォントスタイルでフォントを検索し、大小文字の区別を無視または尊重して返します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示します。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | 実際のフォントディレクトリを含むリストのコピー。 |
| [getSources](#getSources--) | フォント ソース コレクションを取得します。 |
| [getSubstitutions](#getSubstitutions--) | フォント 置換 ストラテジー コレクションを取得します。 |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | 見つからないフォントは標準フォントに置き換えられます。 |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Font Sources のストレージ構成のステータスを返します。 <br> true の場合、ThreadStatic が使用され、各スレッドが独自の Font Sources を持ちます。 <br> false の場合、すべてのスレッドでグローバル 静的構成が使用されます。 </p> <hr> デフォルト値は True です。 |
| [loadFonts](#loadFonts--) | システムにインストールされたフォントと標準の Pdf フォントをロードします。このメソッドはフォント読み込みプロセスを高速化するために設計されました。デフォルトでは、任意のフォントへの最初のリクエスト時にフォントがロードされます。このメソッドを使用すると、Pdf ドキュメントが開かれる前にシステムおよび標準の Pdf フォントが即座にロードされます。 |
| [openFont](#openFont-java.io.InputStream-int-) | <p> 指定されたフォント ストリームでフォントを開きます。 </p> <hr> <pre> この例は、フォントを開き、最初のページのテキストのフォントを置き換える方法を示しています。 // Open font InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> 指定されたフォント ファイル パスでフォントを開きます。 </p> <hr> <pre> この例は、フォントを開き、最初のページのテキストのフォントを置き換える方法を示しています。 // Open font Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> 指定されたフォント ファイル パスとメトリクス ファイル パスでフォントを開きます。 </p> <hr> <pre> この例は、メトリクス付きの Type1 フォントを開き、最初のページのテキストのフォントを置き換える方法を示しています。 // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [reloadFonts](#reloadFonts--) | プロパティ {@code Sources}({@link #getSources}) で指定されたすべてのフォントを再読み込みします。 |
| [restoreLocalFontPath](#restoreLocalFontPath--) | デフォルトで標準フォント ディレクトリのリストを復元します。 |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | フォント パスのユーザーリストを設定します。 |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | 見つからないフォントをデフォルトフォントに置き換える必要がある場合は TRUE を設定します。デフォルト値は false です。 |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Font Sources のストレージ構成を設定するオプションです。true の場合、ThreadStatic が使用され、各スレッドが独自の Font Sources を持ちます。false の場合、すべてのスレッドでグローバル 静的構成が使用されます。 |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
フォントへのパスをもう一つ追加します。

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> 指定されたフォントでシステムフォントを追加します。 </p> <hr> <pre> この例は、システムフォントを追加する方法を示しています。 InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> 指定されたフォント名でフォントを検索し、返します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示しています。 // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> 大文字小文字の区別を無視または考慮して、指定されたフォント名でフォントを検索し、返します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示しています。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### findFont {#findFont-java.lang.String-int-}
<p> 指定されたフォント名とフォントスタイルでフォントを検索し、返します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示しています。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> 指定されたフォント名とフォントスタイルで、大小文字の区別を無視または尊重してフォントを検索し、返します。 </p> <hr> <pre> この例は、フォントを検索し、最初のページのテキストのフォントを置き換える方法を示しています。 // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

実際のフォントディレクトリを含むリストのコピー。

**Returns:**
String のリスト

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

フォント ソース コレクションを取得します。

**Returns:**
FontSourceCollection オブジェクト

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

フォント 置換 ストラテジー コレクションを取得します。

**Returns:**
FontSubstitutionCollection オブジェクト

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

見つからないフォントは標準フォントに置き換えられます。

**Returns:**
ブール値

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Font Sources のストレージ構成のステータスを返します。 <br> true の場合、ThreadStatic が使用され、各スレッドが独自の Font Sources を持ちます。 <br> false の場合、すべてのスレッドでグローバル 静的構成が使用されます。 </p> <hr> デフォルト値は True です。

**Returns:**
ブール値

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

システムにインストールされたフォントと標準の Pdf フォントをロードします。このメソッドはフォント読み込みプロセスを高速化するために設計されました。デフォルトでは、任意のフォントへの最初のリクエスト時にフォントがロードされます。このメソッドを使用すると、Pdf ドキュメントが開かれる前にシステムおよび標準の Pdf フォントが即座にロードされます。

### openFont {#openFont-java.io.InputStream-int-}
<p> 指定されたフォントストリームでフォントを開きます。 </p> <hr> <pre> この例は、フォントを開き、最初のページのテキストのフォントを置き換える方法を示しています。 // Open font InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> 指定されたフォントファイルパスでフォントを開きます。 </p> <hr> <pre> この例は、フォントを開き、最初のページのテキストのフォントを置き換える方法を示しています。 // Open font Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> 指定されたフォントファイルパスとメトリックファイルパスでフォントを開きます。 </p> <hr> <pre> この例は、メトリック付き Type1 フォントを開き、最初のページのテキストのフォントを置き換える方法を示しています。 // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

プロパティ {@code Sources}({@link #getSources}) で指定されたすべてのフォントを再読み込みします。

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

デフォルトで標準フォント ディレクトリのリストを復元します。

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
フォント パスのユーザーリストを設定します。

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

見つからないフォントをデフォルトフォントに置き換える必要がある場合は TRUE を設定します。デフォルト値は false です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Font Sources のストレージ構成を設定するオプションです。true の場合、ThreadStatic が使用され、各スレッドが独自の Font Sources を持ちます。false の場合、すべてのスレッドでグローバル 静的構成が使用されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isTheadLocal |  | ブール値 |
