---
title: "FieldSerializationResult"
linktitle: "FieldSerializationResult"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォームフィールドのシリアライズ処理の結果を表します。"
type: docs
weight: 1390
url: /ja/java/com.aspose.pdf/fieldserializationresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FieldSerializationResult

```
public class FieldSerializationResult extends Object
```

フォームフィールドのシリアライズ処理の結果を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [FieldSerializationResult](#FieldSerializationResult--) | 新しい {@link FieldSerializationResult} クラスのインスタンスを初期化します。 |
| [FieldSerializationResult](#FieldSerializationResult-java.lang.String-) | 新しい {@link FieldSerializationResult} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getErrorMessages](#getErrorMessages--) | シリアライズ処理に関連するエラーメッセージを取得します。値: エラーメッセージのセット。 |
| [getFieldFullName](#getFieldFullName--) | フィールドの完全名を取得します。値: フィールドの完全名。 |
| [getFieldSerializationStatus](#getFieldSerializationStatus--) | フォームフィールドのシリアライズ状態を取得します。値: フィールドのシリアライズ状態。 |
| [getWarningMessages](#getWarningMessages--) | シリアライズ処理に関連する警告メッセージを取得します。値: 警告メッセージのセット。 |
| [updateStatus](#updateStatus-int-java.lang.String-) | シリアライズ状態を更新し、適切なセットにメッセージを追加します。 |

### FieldSerializationResult {#FieldSerializationResult--}
```
public FieldSerializationResult()
```

新しい {@link FieldSerializationResult} クラスのインスタンスを初期化します。

### FieldSerializationResult {#FieldSerializationResult-java.lang.String-}
新しい {@link FieldSerializationResult} クラスのインスタンスを初期化します。

### getErrorMessages {#getErrorMessages--}
```
public final HashSet < String > getErrorMessages()
```

シリアライズ処理に関連するエラーメッセージを取得します。値: エラーメッセージのセット。

**Returns:**
String インスタンスの HashSet

### getFieldFullName {#getFieldFullName--}
```
public final String getFieldFullName()
```

フィールドの完全名を取得します。値: フィールドの完全名。

**Returns:**
文字列値

### getFieldSerializationStatus {#getFieldSerializationStatus--}
```
public final int getFieldSerializationStatus()
```

フォームフィールドのシリアライズ状態を取得します。値: フィールドのシリアライズ状態。

**Returns:**
FieldSerializationStatus 要素

### getWarningMessages {#getWarningMessages--}
```
public final HashSet < String > getWarningMessages()
```

シリアライズ処理に関連する警告メッセージを取得します。値: 警告メッセージのセット。

**Returns:**
String インスタンスの HashSet

### updateStatus {#updateStatus-int-java.lang.String-}
シリアライズ状態を更新し、適切なセットにメッセージを追加します。
