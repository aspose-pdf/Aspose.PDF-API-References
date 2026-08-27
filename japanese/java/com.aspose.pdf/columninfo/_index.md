---
title: "ColumnInfo"
linktitle: "ColumnInfo"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このクラスは列の情報を表します。"
type: docs
weight: 730
url: /ja/java/com.aspose.pdf/columninfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ColumnInfo

```
public final class ColumnInfo extends Object
```

このクラスは列の情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ColumnInfo](#ColumnInfo--) | ColumnInfo クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getColumnCount](#getColumnCount--) | 列数を示す整数値を取得します。 |
| [getColumnSpacing](#getColumnSpacing--) | <p> 列間の間隔を含む文字列を取得または設定します。各間隔の値は空白で区切る必要があります。デフォルトの単位はポイントですが、cm とインチもサポートされています。例: "120 2.5cm 1.5inch"。 </p><hr> <p> このプロパティが設定されていない場合、各間隔にはデフォルト値 0 が使用されます。 </p> |
| [getColumnWidths](#getColumnWidths--) | 列の幅を含む文字列を取得または設定します。各列の値は空白で区切る必要があります。デフォルトの単位はポイントですが、cm、インチ、および利用可能幅のパーセンテージもサポートされています。例: "120 2.5cm 1.5inch" |
| [setColumnCount](#setColumnCount-int-) | 列数を示す整数値を設定します。 |
| [setColumnSpacing](#setColumnSpacing-java.lang.String-) | <p> 列間の間隔を含む文字列を取得または設定します。各間隔の値は空白で区切る必要があります。デフォルトの単位はポイントですが、cm とインチもサポートされています。例: "120 2.5cm 1.5inch"。 </p><hr> <p> このプロパティが設定されていない場合、各間隔にはデフォルト値 0 が使用されます。 </p> |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | 列の幅を含む文字列を取得または設定します。各列の値は空白で区切る必要があります。デフォルトの単位はポイントですが、cm、インチ、および利用可能幅のパーセンテージもサポートされています。例: "120 2.5cm 1.5inch" |

### ColumnInfo {#ColumnInfo--}
```
public ColumnInfo()
```

ColumnInfo クラスの新しいインスタンスを初期化します。

### getColumnCount {#getColumnCount--}
```
public int getColumnCount()
```

列数を示す整数値を取得します。

**Returns:**
列数

### getColumnSpacing {#getColumnSpacing--}
```
public String getColumnSpacing()
```

<p> 列間の間隔を含む文字列を取得または設定します。各間隔の値は空白で区切る必要があります。デフォルトの単位はポイントですが、cm とインチもサポートされています。例: "120 2.5cm 1.5inch"。 </p><hr> <p> このプロパティが設定されていない場合、各間隔にはデフォルト値 0 が使用されます。 </p>

**Returns:**
文字列値

### getColumnWidths {#getColumnWidths--}
```
public String getColumnWidths()
```

列の幅を含む文字列を取得または設定します。各列の値は空白で区切る必要があります。デフォルトの単位はポイントですが、cm、インチ、および利用可能幅のパーセンテージもサポートされています。例: "120 2.5cm 1.5inch"

**Returns:**
文字列値

### setColumnCount {#setColumnCount-int-}
```
public void setColumnCount(int value)
```

列数を示す整数値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 列数 |

### setColumnSpacing {#setColumnSpacing-java.lang.String-}
<p> 列間の間隔を含む文字列を取得または設定します。各間隔の値は空白で区切る必要があります。デフォルトの単位はポイントですが、cm とインチもサポートされています。例: "120 2.5cm 1.5inch"。 </p><hr> <p> このプロパティが設定されていない場合、各間隔にはデフォルト値 0 が使用されます。 </p>

### setColumnWidths {#setColumnWidths-java.lang.String-}
列の幅を含む文字列を取得または設定します。各列の値は空白で区切る必要があります。デフォルトの単位はポイントですが、cm、インチ、および利用可能幅のパーセンテージもサポートされています。例: "120 2.5cm 1.5inch"
