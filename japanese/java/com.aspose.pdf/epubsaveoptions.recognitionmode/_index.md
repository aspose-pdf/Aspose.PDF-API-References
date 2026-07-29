---
title: "EpubSaveOptions.RecognitionMode"
linktitle: "EpubSaveOptions.RecognitionMode"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ファイル（通常は固定レイアウトです）が変換される際、変換エンジンはグループ化と多層解析を実行して元のドキュメントを復元しようとします。"
type: docs
weight: 1250
url: /ja/java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

通常は固定レイアウトの PDF ファイルが変換される際、変換エンジンはグルーピングと多層解析を実行して元の文書作者の意図を復元し、フロー レイアウトで結果を生成しようとします。このプロパティは、コンテンツ認識の望ましい方法に合わせてその変換を調整します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Fixed](#Fixed) | このモードは高速で、元の見た目のページを最大限に保持するのに適していますが、残念ながら多くの EPUB リーダーは固定レイアウトの XHTML をサポートしていません。 |
| [Flow](#Flow) | フル認識モードでは、エンジンがグループ化と多層解析を実行し、元のドキュメントの作者の意図を復元し、フロー レイアウトの XHTML を生成しようとします。 |
| [PdfFlow](#PdfFlow) | この変換の主な考え方は、PDF ドキュメントの処理中に形成されるコンテンツ描画の「自然な」順序を保存することに基づいています。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

このモードは高速で、元の見た目のページを最大限に保持するのに適していますが、残念ながら多くの EPUB リーダーは固定レイアウトの XHTML をサポートしていません。

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

フル認識モードでは、エンジンがグループ化と多層解析を実行し、元のドキュメントの作者の意図を復元し、フロー レイアウトの XHTML を生成しようとします。

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

この変換の主な考え方は、PDF ドキュメントの処理中に形成されるコンテンツ描画の「自然な」順序を保存することに基づいています。

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列
