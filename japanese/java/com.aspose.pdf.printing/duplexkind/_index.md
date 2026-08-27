---
title: "DuplexKind"
linktitle: "DuplexKind"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "プリンターの両面印刷設定を指定します。"
type: docs
weight: 20
url: /ja/java/com.aspose.pdf.printing/duplexkind/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.DuplexKind

```
public class DuplexKind extends Object
```

プリンターの両面印刷設定を指定します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [Default](#Default) | プリンターのデフォルト両面設定です。 |
| [Horizontal](#Horizontal) | 両面、横方向印刷。 |
| [Simplex](#Simplex) | 片面印刷。 |
| [Vertical](#Vertical) | 両面、縦方向印刷。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DuplexKind](#DuplexKind--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getNames](#getNames--) | Duplex 種類名の配列 |
| [toString](#toString-int-) | Duplex 種類名 |

### Default {#Default}
```
public static final int Default
```

プリンターのデフォルト両面設定です。

### Horizontal {#Horizontal}
```
public static final int Horizontal
```

両面、横方向印刷。

### Simplex {#Simplex}
```
public static final int Simplex
```

片面印刷。

### Vertical {#Vertical}
```
public static final int Vertical
```

両面、縦方向印刷。

### DuplexKind {#DuplexKind--}
```
public DuplexKind()
```



### getNames {#getNames--}
```
public static String [] getNames()
```

Duplex 種類名の配列

**Returns:**
String[] オブジェクト

### toString {#toString-int-}
```
public static String toString(int pdfPrintRange)
```

Duplex 種類名

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pdfPrintRange |  | PaperKind 要素 |

**Returns:**
用紙形式名
