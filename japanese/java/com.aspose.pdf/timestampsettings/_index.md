---
title: "TimestampSettings"
linktitle: "TimestampSettings"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "署名プロセス中に使用される OCSP 設定を表します。"
type: docs
weight: 5360
url: /ja/java/com.aspose.pdf/timestampsettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TimestampSettings

```
public class TimestampSettings extends Object
```

署名プロセス中に使用される OCSP 設定を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-) | 新しい {@code TimestampSettings} クラスのインスタンスを初期化します。 |
| [TimestampSettings](#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-) | 新しい {@code TimestampSettings} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBasicAuthCredentials](#getBasicAuthCredentials--) | 基本認証の資格情報を取得します。Username と password は文字列 "username:password" に結合されます。 |
| [getDigestHashAlgorithm](#getDigestHashAlgorithm--) | 内部ハッシュ関数のダイジェストアルゴリズムを取得/設定します。 |
| [getServerUrl](#getServerUrl--) | タイムスタンプサーバーの URL を取得します。 |
| [setBasicAuthCredentials](#setBasicAuthCredentials-java.lang.String-) | 基本認証の資格情報を設定します。ユーザー名とパスワードは文字列 "username:password" に結合されます。 |
| [setDigestHashAlgorithm](#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-) | 内部ハッシュ関数のダイジェストアルゴリズムを取得/設定します。 |
| [setServerUrl](#setServerUrl-java.lang.String-) | タイムスタンプサーバーの URL を設定します。 |

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-}
新しい {@code TimestampSettings} クラスのインスタンスを初期化します。

### TimestampSettings {#TimestampSettings-java.lang.String-java.lang.String-com.aspose.pdf.DigestHashAlgorithm-}
新しい {@code TimestampSettings} クラスのインスタンスを初期化します。

### getBasicAuthCredentials {#getBasicAuthCredentials--}
```
public String getBasicAuthCredentials()
```

基本認証の資格情報を取得します。Username と password は文字列 "username:password" に結合されます。

**Returns:**
文字列値

### getDigestHashAlgorithm {#getDigestHashAlgorithm--}
```
public final DigestHashAlgorithm getDigestHashAlgorithm()
```

内部ハッシュ関数のダイジェストアルゴリズムを取得/設定します。

**Returns:**
DigestHashAlgorithm 要素 @see DigestHashAlgorithm

### getServerUrl {#getServerUrl--}
```
public String getServerUrl()
```

タイムスタンプサーバーの URL を取得します。

**Returns:**
文字列値

### setBasicAuthCredentials {#setBasicAuthCredentials-java.lang.String-}
基本認証の資格情報を設定します。ユーザー名とパスワードは文字列 "username:password" に結合されます。

### setDigestHashAlgorithm {#setDigestHashAlgorithm-com.aspose.pdf.DigestHashAlgorithm-}
内部ハッシュ関数のダイジェストアルゴリズムを取得/設定します。

### setServerUrl {#setServerUrl-java.lang.String-}
タイムスタンプサーバーの URL を設定します。
