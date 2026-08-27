---
title: "ValidationResult"
linktitle: "ValidationResult"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "証明書の検証プロセスの結果を表します。ValidationResult クラスは、証明書の検証結果に関する情報を提供します（それを含む）。"
type: docs
weight: 40
url: /ja/java/com.aspose.pdf.security.certificatevalidation/validationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationResult

```
public final class ValidationResult extends Object
```

証明書の検証プロセスの結果を表します。ValidationResult クラスは、証明書の検証結果に関する情報を提供し、ステータスや検証中に発生した問題を説明するメッセージを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ValidationResult](#ValidationResult--) | {@link ValidationResult} クラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMessage](#getMessage--) | 検証結果に関連付けられたメッセージを表します。Message プロパティは、検証結果の状態に関する追加のコンテキストや情報を提供します。 |
| [getStatus](#getStatus--) | 証明書の検証プロセスのステータスを取得します。Status プロパティは、証明書検証の結果を示します。可能な値は {@link ValidationStatus} 列挙体で定義されており、Valid、Invalid、Undefined などがあります。証明書が検証チェックに合格したかどうかの洞察を提供します。 |
| [setMessage](#setMessage-java.lang.String-) | 検証結果に関連付けられたメッセージを表します。Message プロパティは、検証結果の状態に関する追加のコンテキストや情報を提供します。 |
| [setStatus](#setStatus-int-) | 証明書の検証プロセスのステータスを取得します。Status プロパティは、証明書検証の結果を示します。可能な値は {@link ValidationStatus} 列挙体で定義されており、Valid、Invalid、Undefined などがあります。証明書が検証チェックに合格したかどうかの洞察を提供します。 |

### ValidationResult {#ValidationResult--}
```
public ValidationResult()
```

{@link ValidationResult} クラスのインスタンスを作成します。

### getMessage {#getMessage--}
```
public final String getMessage()
```

検証結果に関連付けられたメッセージを表します。Message プロパティは、検証結果の状態に関する追加のコンテキストや情報を提供します。

**Returns:**
文字列値

### getStatus {#getStatus--}
```
public final int getStatus()
```

証明書の検証プロセスのステータスを取得します。Status プロパティは、証明書検証の結果を示します。可能な値は {@link ValidationStatus} 列挙体で定義されており、Valid、Invalid、Undefined などがあります。証明書が検証チェックに合格したかどうかの洞察を提供します。

**Returns:**
ValidationStatus 要素

### setMessage {#setMessage-java.lang.String-}
検証結果に関連付けられたメッセージを表します。Message プロパティは、検証結果の状態に関する追加のコンテキストや情報を提供します。

### setStatus {#setStatus-int-}
```
public final void setStatus(int value)
```

証明書の検証プロセスのステータスを取得します。Status プロパティは、証明書検証の結果を示します。可能な値は {@link ValidationStatus} 列挙体で定義されており、Valid、Invalid、Undefined などがあります。証明書が検証チェックに合格したかどうかの洞察を提供します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ValidationStatus 要素 |
