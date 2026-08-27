---
title: "OutputIntent"
linktitle: "OutputIntent"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメントの色特性を、対象の出力デバイスまたは文書が使用される製造環境の特性と一致させる出力インテントを表します。"
type: docs
weight: 3290
url: /ja/java/com.aspose.pdf/outputintent/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.OutputIntent

```
public final class OutputIntent extends Object
```

PDF ドキュメントの色特性を、印刷される対象出力デバイスまたは製造環境の特性と一致させる出力インテントを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OutputIntent](#OutputIntent-java.lang.String-) | 指定された出力条件識別子で {@link OutputIntent} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInfo](#getInfo--) | 対象デバイスまたは製造条件に関する追加情報やコメントを含む、人間が読めるテキストを取得します。 |
| [getOutputCondition](#getOutputCondition--) | 対象の出力デバイスまたは製造条件を簡潔に識別する、人間が読めるテキストを取得します。 |
| [getOutputConditionIdentifier](#getOutputConditionIdentifier--) | 対象の出力デバイスまたは製造条件を人間または機械が読める形式で識別するテキストを取得します。 |
| [getRegistryName](#getRegistryName--) | {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}) によって指定された条件が定義されているレジストリを識別するテキストを取得します。 |
| [getSubtype](#getSubtype--) | 出力インテントのサブタイプを取得します。 |
| [setInfo](#setInfo-java.lang.String-) | 対象デバイスまたは製造条件に関する追加情報やコメントを含む、人間が読めるテキストを設定します。 |
| [setOutputCondition](#setOutputCondition-java.lang.String-) | 人間が読める形式で、意図した出力デバイスまたは製造条件を簡潔に識別するテキストを取得または設定します。 |
| [setOutputConditionIdentifier](#setOutputConditionIdentifier-java.lang.String-) | 人間または機械が読める形式で、意図した出力デバイスまたは製造条件を識別するテキストを設定します。 |
| [setRegistryName](#setRegistryName-java.lang.String-) | {@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}/{@link #setOutputConditionIdentifier(String)}) によって指定された条件が定義されているレジストリを識別するテキストを設定します。 |

### OutputIntent {#OutputIntent-java.lang.String-}
指定された出力条件識別子で {@link OutputIntent} クラスの新しいインスタンスを初期化します。

### getInfo {#getInfo--}
```
public final String getInfo()
```

対象デバイスまたは製造条件に関する追加情報やコメントを含む、人間が読めるテキストを取得します。

**Returns:**
文字列値

### getOutputCondition {#getOutputCondition--}
```
public final String getOutputCondition()
```

対象の出力デバイスまたは製造条件を簡潔に識別する、人間が読めるテキストを取得します。

**Returns:**
文字列値

### getOutputConditionIdentifier {#getOutputConditionIdentifier--}
```
public final String getOutputConditionIdentifier()
```

対象の出力デバイスまたは製造条件を人間または機械が読める形式で識別するテキストを取得します。

**Returns:**
文字列値

### getRegistryName {#getRegistryName--}
```
public final String getRegistryName()
```

{@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}) によって指定された条件が定義されているレジストリを識別するテキストを取得します。

**Returns:**
文字列値

### getSubtype {#getSubtype--}
```
public final String getSubtype()
```

出力インテントのサブタイプを取得します。

**Returns:**
文字列値

### setInfo {#setInfo-java.lang.String-}
対象デバイスまたは製造条件に関する追加情報やコメントを含む、人間が読めるテキストを設定します。

### setOutputCondition {#setOutputCondition-java.lang.String-}
人間が読める形式で、意図した出力デバイスまたは製造条件を簡潔に識別するテキストを取得または設定します。

### setOutputConditionIdentifier {#setOutputConditionIdentifier-java.lang.String-}
人間または機械が読める形式で、意図した出力デバイスまたは製造条件を識別するテキストを設定します。

### setRegistryName {#setRegistryName-java.lang.String-}
{@code OutputConditionIdentifier}({@link #getOutputConditionIdentifier}/{@link #setOutputConditionIdentifier(String)}) によって指定された条件が定義されているレジストリを識別するテキストを設定します。
