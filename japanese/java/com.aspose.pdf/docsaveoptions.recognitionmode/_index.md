---
title: "DocSaveOptions.RecognitionMode"
linktitle: "DocSaveOptions.RecognitionMode"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントがワードプロセッシング文書に変換される方法を制御できます。結果の文書が大幅に編集される予定がない場合は RecognitionMode.Textbox モードを使用してください。"
type: docs
weight: 1050
url: /ja/java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

PDF 文書がワードプロセッシング文書に変換される方法を制御できます。結果の文書を大幅に編集する予定がない場合は RecognitionMode.Textbox モードを使用してください。テキストボックスは少量の編集であれば簡単に修正できます。出力文書のさらなる編集が必要な場合は RecognitionMode.Flow モードを使用してください。フローモードの段落やテキストラインはテキストの修正が容易ですが、サポートされていない書式設定オブジェクトは RecognitionMode.Textbox モードよりも見栄えが悪くなります。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | テーブルの認識をサポートする代替フローモードです。 |
| [Flow](#Flow) | フル認識モードでは、エンジンがグループ化と多層分析を実行し、元のドキュメント作成者の意図を復元して、最大限に編集可能な文書を生成します。 |
| [Textbox](#Textbox) | このモードは高速で、PDF ファイルの元の外観を最大限に保持するのに適していますが、結果の文書の編集可能性は制限される可能性があります。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | 指定された名前でこの型の列挙定数を返します。 |
| [values](#values--) | 宣言された順序でこの列挙型の定数を含む配列を返します。 |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

テーブルの認識をサポートする代替フローモードです。

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

フル認識モードでは、エンジンがグループ化と多層分析を実行し、元のドキュメント作成者の意図を復元して、最大限に編集可能な文書を生成します。

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

このモードは高速で、PDF ファイルの元の外観を最大限に保持するのに適していますが、結果の文書の編集可能性は制限される可能性があります。

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
指定された名前でこの型の列挙定数を返します。

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

宣言された順序でこの列挙型の定数を含む配列を返します。

**Returns:**
宣言された順序でこの列挙型の定数を含む配列
