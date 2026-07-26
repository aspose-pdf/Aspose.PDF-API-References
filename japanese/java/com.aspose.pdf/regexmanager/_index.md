---
title: "RegexManager"
linktitle: "RegexManager"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "構成可能なタイムアウト設定を備えた正規表現操作用ラッパーを提供します。"
type: docs
weight: 4130
url: /ja/java/com.aspose.pdf/regexmanager/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.RegexManager

```
public class RegexManager extends Object
```

構成可能なタイムアウト設定を備えた正規表現操作用ラッパーを提供します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RegexManager](#RegexManager--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMatchTimeout](#getMatchTimeout--) | ライブラリ全体の正規表現操作のタイムアウトを取得または設定します。デフォルト値は 1000 ms です。値: デフォルトのタイムアウト期間を表す {@link double}。 |
| [setMatchTimeout](#setMatchTimeout-int-) | ライブラリ全体の正規表現操作のタイムアウトを取得または設定します。デフォルト値は 1000 ms です。値: |

### RegexManager {#RegexManager--}
```
public RegexManager()
```



### getMatchTimeout {#getMatchTimeout--}
```
public static int getMatchTimeout()
```

ライブラリ全体の正規表現操作のタイムアウトを取得または設定します。デフォルト値は 1000 ms です。値: デフォルトのタイムアウト期間を表す {@link double}。

**Returns:**
int 値です。

### setMatchTimeout {#setMatchTimeout-int-}
```
public static void setMatchTimeout(int value)
```

ライブラリ全体の正規表現操作のタイムアウトを取得または設定します。デフォルト値は 1000 ms です。値:

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ミリ秒でのデフォルトタイムアウト期間を表す A。 |
