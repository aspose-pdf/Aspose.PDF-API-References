---
title: "com.aspose.ms.System.MulticastDelegate>"
linktitle: "com.aspose.ms.System.MulticastDelegate>"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "イベントを表すクラスです。"
type: docs
weight: 740
url: /ja/java/com.aspose.pdf/com.aspose.ms.system.multicastdelegate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfEvent<T>

```
public abstract class PdfEvent<T extends com.aspose.ms.System.MulticastDelegate> extends Object
```

イベントを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfEvent](#PdfEvent--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-T-) | デリゲートをもう1つ追加します。 |
| [assign](#assign-T-) | 現在のデリゲートだけを追加し、他をクリアします。 |
| [clear](#clear--) | デリゲートリストをクリアする |
| [isEmpty](#isEmpty--) | ハンドラのリストが空の場合に true を返します |
| [remove](#remove-T-) | リストからデリゲートを削除する |

### PdfEvent {#PdfEvent--}
```
public PdfEvent()
```



### add {#add-T-}
```
public final void add( T delegate)
```

デリゲートをもう1つ追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| デリゲート |  | ハンドラオブジェクト |

### assign {#assign-T-}
```
public final void assign( T delegate)
```

現在のデリゲートだけを追加し、他をクリアします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| デリゲート |  | ハンドラオブジェクト |

### clear {#clear--}
```
public final void clear()
```

デリゲートリストをクリアする

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

ハンドラのリストが空の場合に true を返します

**Returns:**
ブール値

### remove {#remove-T-}
```
public final void remove( T delegate)
```

リストからデリゲートを削除する

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| デリゲート |  | ハンドラオブジェクト |
