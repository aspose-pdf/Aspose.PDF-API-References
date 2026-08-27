---
title: "Metered"
linktitle: "Metered"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> メーターキーを設定するメソッドを提供します。 </p> <hr> この例では、メーター付きの公開キーと秘密キーを設定しようとします <pre> コンポーネントの jar ファイル: Metered matered =."
type: docs
weight: 3060
url: /ja/java/com.aspose.pdf/metered/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Metered

```
public class Metered extends Object
```

<p> メーターキーを設定するメソッドを提供します。 </p> <hr> この例では、メーターの公開キーと秘密キーを設定しようとします <pre> The component jar file: Metered matered = new Metered(); matered.setMeteredKey("PublicKey", "PrivateKey"); </pre>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Metered](#Metered--) | このクラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getConsumptionCredit](#getConsumptionCredit--) | 消費クレジットを取得します |
| [getConsumptionQuantity](#getConsumptionQuantity--) | 消費ファイルサイズを取得します |
| [setMeteredKey](#setMeteredKey-java.lang.String-java.lang.String-) | メーター付きの公開キーと秘密キーを設定します |

### Metered {#Metered--}
```
public Metered()
```

このクラスの新しいインスタンスを初期化します。

### getConsumptionCredit {#getConsumptionCredit--}
```
public static com.aspose.ms.System.Decimal getConsumptionCredit() throws Exception
```

消費クレジットを取得します

**Returns:**
消費量 @throws Metered API の問題がある場合は Exception をスローします。

### getConsumptionQuantity {#getConsumptionQuantity--}
```
public static com.aspose.ms.System.Decimal getConsumptionQuantity() throws Exception
```

消費ファイルサイズを取得します

**Returns:**
消費量 @throws Metered API の問題がある場合は Exception をスローします。

### setMeteredKey {#setMeteredKey-java.lang.String-java.lang.String-}
メーター付きの公開キーと秘密キーを設定します
