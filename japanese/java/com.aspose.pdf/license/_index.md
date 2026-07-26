---
title: "ライセンス"
linktitle: "ライセンス"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "コンポーネントにライセンスを付与するためのメソッドを提供します。この例では、コンポーネントが含まれるフォルダー内で MyLicense.lic という名前のライセンスファイルを探します。"
type: docs
weight: 2670
url: /ja/java/com.aspose.pdf/license/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.License

```
public class License extends Object
```

コンポーネントのライセンス付与メソッドを提供します。この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で、MyLicense.lic という名前のライセンスファイルを検索しようとします。 License license = new License(); license.setLicense("MyLicense.lic");

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [License](#License--) | このクラスの新しいインスタンスを初期化します。この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリーアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で MyLicense.lic という名前のライセンスファイルを探します。 License license = new License(); license.setLicense("MyLicense.lic"); |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [clearLicense](#clearLicense--) | 現在のライセンスをクリアします。 |
| [getLicenseInfo](#getLicenseInfo--) | 現在のライセンス情報を取得します。 |
| [isInternalFIPSSecurity](#isInternalFIPSSecurity--) | デフォルトでは、デフォルトの JDK セキュリティを使用しています。デフォルト値は false です。カスタマイズされた Java 環境が必要なアルゴリズムをサポートできない場合、内部組み込みの FIPS セキュリティの使用を推奨します。 |
| [setInternalFIPSSecurity](#setInternalFIPSSecurity-boolean-) | デフォルトでは、デフォルトの JRE セキュリティを使用しています。デフォルト値は false です。カスタマイズされた Java 環境が必要なアルゴリズムをサポートできない場合、内部組み込みの FIPS セキュリティの使用を推奨します。 <p> なお、JVM の SecureRandom アルゴリズムは、いくつかの OS では /dev/random がホストマシンで一定量の「ノイズ」生成されるまで結果を返さないことがあります。Oracle の JVM が使用する乱数生成ライブラリは、UNIX プラットフォームでデフォルトで /dev/random に依存しています。/dev/random はより安全ですが、デフォルトの JVM 設定で遅延が発生する場合は /dev/urandom の使用が推奨されます。または /dev/random 用にエントロピーを生成するデバイスを追加してください。 <p> 以下の java オプションは遅延を回避し、securerandom.source 設定を上書きするのに役立ちます。 -Djava.security.egd=file:/dev/./urandom |
| [setLicense](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを付与します。ライセンスを含むストリームです。このメソッドを使用してストリームからライセンスをロードします。 License license = new License(); license.setLicense(myStream); |
| [setLicense](#setLicense-java.lang.String-) | コンポーネントにライセンスを付与します。ライセンスは次の場所で検索されます：1. 明示的なパス。2. コンポーネント JAR ファイルのフォルダー。この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリーアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で MyLicense.lic という名前のライセンスファイルを探します。 License license = new License(); license.setLicense("MyLicense.lic"); |

### License {#License--}
```
public License()
```

このクラスの新しいインスタンスを初期化します。この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリーアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で MyLicense.lic という名前のライセンスファイルを探します。 License license = new License(); license.setLicense("MyLicense.lic");

### clearLicense {#clearLicense--}
```
public final void clearLicense()
```

現在のライセンスをクリアします。

### getLicenseInfo {#getLicenseInfo--}
```
public final LicenseInfo getLicenseInfo()
```

現在のライセンス情報を取得します。

**Returns:**
LicenseInfo インスタンス

### isInternalFIPSSecurity {#isInternalFIPSSecurity--}
```
public static boolean isInternalFIPSSecurity()
```

デフォルトでは、デフォルトの JDK セキュリティを使用しています。デフォルト値は false です。カスタマイズされた Java 環境が必要なアルゴリズムをサポートできない場合、内部組み込みの FIPS セキュリティの使用を推奨します。

**Returns:**
ブール値

### setInternalFIPSSecurity {#setInternalFIPSSecurity-boolean-}
```
public static void setInternalFIPSSecurity(boolean internalFIPSSecurity)
```

デフォルトでは、デフォルトの JRE セキュリティを使用しています。デフォルト値は false です。カスタマイズされた Java 環境が必要なアルゴリズムをサポートできない場合、内部組み込みの FIPS セキュリティの使用を推奨します。 <p> なお、JVM の SecureRandom アルゴリズムは、いくつかの OS では /dev/random がホストマシンで一定量の「ノイズ」生成されるまで結果を返さないことがあります。Oracle の JVM が使用する乱数生成ライブラリは、UNIX プラットフォームでデフォルトで /dev/random に依存しています。/dev/random はより安全ですが、デフォルトの JVM 設定で遅延が発生する場合は /dev/urandom の使用が推奨されます。または /dev/random 用にエントロピーを生成するデバイスを追加してください。 <p> 以下の java オプションは遅延を回避し、securerandom.source 設定を上書きするのに役立ちます。 -Djava.security.egd=file:/dev/./urandom

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| internalFIPSSecurity |  | ブール値 |

### setLicense {#setLicense-java.io.InputStream-}
コンポーネントにライセンスを付与します。ライセンスを含むストリームです。このメソッドを使用してストリームからライセンスをロードします。 License license = new License(); license.setLicense(myStream);

### setLicense {#setLicense-java.lang.String-}
コンポーネントにライセンスを付与します。ライセンスは次の場所で検索されます：1. 明示的なパス。2. コンポーネント JAR ファイルのフォルダー。この例では、コンポーネントが含まれるフォルダー、呼び出しアセンブリが含まれるフォルダー、エントリーアセンブリのフォルダー、そして呼び出しアセンブリの埋め込みリソース内で MyLicense.lic という名前のライセンスファイルを探します。 License license = new License(); license.setLicense("MyLicense.lic");
