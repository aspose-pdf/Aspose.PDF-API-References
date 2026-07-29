---
title: "EpubSaveOptions"
linktitle: "EpubSaveOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "EPUB 形式へのエクスポート用保存オプション"
type: docs
weight: 1240
url: /ja/java/com.aspose.pdf/epubsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.EpubSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.EpubSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.EpubSaveOptions

```
public class EpubSaveOptions extends UnifiedSaveOptions
```

EPUB 形式へのエクスポート用保存オプション

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [EpubSaveOptions](#EpubSaveOptions--) | コンストラクタ |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getContentRecognitionMode](#getContentRecognitionMode--) | 通常は固定レイアウトの PDF ファイルが変換される際、変換エンジンはグルーピングと多層解析を実行して元の文書作者の意図を復元し、フロー レイアウトで結果を生成しようとします。このプロパティは、コンテンツ認識の望ましい方法に合わせてその変換を調整します。 |
| [getTitle](#getTitle--) | EPUB ドキュメントのタイトルを取得または設定します。 |
| [setContentRecognitionMode](#setContentRecognitionMode-com.aspose.pdf.EpubSaveOptions.RecognitionMode-) | PDF ファイル（通常は固定レイアウト）を変換する際、変換エンジンはグルーピングと多層解析を実行して、元の文書作者の意図を復元し、フロー レイアウトで結果を生成しようとします。 |
| [setTitle](#setTitle-java.lang.String-) | EPUB ドキュメントのタイトルを取得または設定します。 |

### EpubSaveOptions {#EpubSaveOptions--}
```
public EpubSaveOptions()
```

コンストラクタ

### getContentRecognitionMode {#getContentRecognitionMode--}
```
public EpubSaveOptions.RecognitionMode getContentRecognitionMode()
```

通常は固定レイアウトの PDF ファイルが変換される際、変換エンジンはグルーピングと多層解析を実行して元の文書作者の意図を復元し、フロー レイアウトで結果を生成しようとします。このプロパティは、コンテンツ認識の望ましい方法に合わせてその変換を調整します。

**Returns:**
RecognitionMode 要素 @see RecognitionMode

### getTitle {#getTitle--}
```
public final String getTitle()
```

EPUB ドキュメントのタイトルを取得または設定します。

**Returns:**
文字列値

### setContentRecognitionMode {#setContentRecognitionMode-com.aspose.pdf.EpubSaveOptions.RecognitionMode-}
PDF ファイル（通常は固定レイアウト）を変換する際、変換エンジンはグルーピングと多層解析を実行して、元の文書作者の意図を復元し、フロー レイアウトで結果を生成しようとします。

### setTitle {#setTitle-java.lang.String-}
EPUB ドキュメントのタイトルを取得または設定します。
