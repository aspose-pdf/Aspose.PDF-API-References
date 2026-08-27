---
title: "SaveOptions.MarginPartStyle"
linktitle: "SaveOptions.MarginPartStyle"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "余白の一部（上、下、左側または右側）に関する情報を表します。"
type: docs
weight: 4420
url: /ja/java/com.aspose.pdf/saveoptions.marginpartstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions.MarginPartStyle

```
public static class SaveOptions.MarginPartStyle extends Object
```

余白の一部（上、下、左側または右側）に関する情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MarginPartStyle](#MarginPartStyle-boolean-) | MarginPartStyle クラスのインスタンスを作成し、その値をポイントで初期化します。 |
| [MarginPartStyle](#MarginPartStyle-int-) | MarginPartStyle クラスのインスタンスを作成し、その値をポイントで設定します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValueInPoints](#getValueInPoints--) | マージンをポイントで表します。0 より大きい数である必要があります。 |
| [isAuto](#isAuto--) | このインスタンスが自動かどうかを示す値を取得または設定します。値: このインスタンスが自動の場合は {@code true}、それ以外の場合は {@code false} です。 |
| [setAuto](#setAuto-boolean-) | このインスタンスが自動かどうかを示す値を取得または設定します。値: このインスタンスが自動の場合は {@code true}、それ以外の場合は {@code false} です。 |
| [setValueInPoints](#setValueInPoints-int-) | マージンをポイントで表します。0 より大きい数である必要があります。 |

### MarginPartStyle {#MarginPartStyle-boolean-}
```
public MarginPartStyle(boolean isAuto)
```

MarginPartStyle クラスのインスタンスを作成し、その値をポイントで初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| isAuto |  | マージン自動をマーク |

### MarginPartStyle {#MarginPartStyle-int-}
```
public MarginPartStyle(int valueInPoints)
```

MarginPartStyle クラスのインスタンスを作成し、その値をポイントで設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| valueInPoints |  | ポイント単位の整数値 |

### getValueInPoints {#getValueInPoints--}
```
public final int getValueInPoints()
```

マージンをポイントで表します。0 より大きい数である必要があります。

**Returns:**
int 値です。

### isAuto {#isAuto--}
```
public final boolean isAuto()
```

このインスタンスが自動かどうかを示す値を取得または設定します。値: このインスタンスが自動の場合は {@code true}、それ以外の場合は {@code false} です。

**Returns:**
ブール値

### setAuto {#setAuto-boolean-}
```
public final void setAuto(boolean value)
```

このインスタンスが自動かどうかを示す値を取得または設定します。値: このインスタンスが自動の場合は {@code true}、それ以外の場合は {@code false} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setValueInPoints {#setValueInPoints-int-}
```
public final void setValueInPoints(int value)
```

マージンをポイントで表します。0 より大きい数である必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
