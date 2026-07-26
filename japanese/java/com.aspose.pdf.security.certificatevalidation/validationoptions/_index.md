---
title: "ValidationOptions"
linktitle: "ValidationOptions"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメント内のデジタル署名を検証するためのオプションを表します。"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.security.certificatevalidation/validationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.certificatevalidation.ValidationOptions

```
public final class ValidationOptions extends Object
```

PDF ドキュメント内のデジタル署名を検証するためのオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ValidationOptions](#ValidationOptions--) | {@link ValidationOptions} クラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCheckCertificateChain](#getCheckCertificateChain--) | 検証プロセス中に証明書チェーンをチェックするかどうかを示す値を取得または設定します。プロパティが設定されている場合、証明書チェーンの存在がチェックされ、存在しない場合は検証結果が {@link ValidationStatus#Undefined} となり、これは Adobe Acrobat の動作に対応します。オンラインで失効ステータスのみを確認したい場合は、フィールドを {@code false} に設定してください。デフォルト値は {@code false} です。 |
| [getRequestTimeout](#getRequestTimeout--) | 検証プロセス中のネットワーク関連操作のタイムアウト時間（ミリ秒）を取得または設定します。RequestTimeout プロパティは、失効ステータスや OCSP サーバーなどのオンラインリソースにアクセスする際に、システムがネットワーク応答を待機できる最大時間を定義します。 |
| [getValidationMethod](#getValidationMethod--) | 証明書の検証に使用するメソッドを取得または設定します。 |
| [getValidationMode](#getValidationMode--) | PDF 文書のデジタル署名の検証モードを取得または設定します。ValidationMode プロパティは、検証プロセスの厳格さを決定します。 |
| [setCheckCertificateChain](#setCheckCertificateChain-boolean-) | 検証プロセス中に証明書チェーンをチェックするかどうかを示す値を取得または設定します。プロパティが設定されている場合、証明書チェーンの存在がチェックされ、存在しない場合は検証結果が {@link ValidationStatus#Undefined} となり、これは Adobe Acrobat の動作に対応します。オンラインで失効ステータスのみを確認したい場合は、フィールドを {@code false} に設定してください。デフォルト値は {@code false} です。 |
| [setRequestTimeout](#setRequestTimeout-int-) | 検証プロセス中のネットワーク関連操作のタイムアウト時間（ミリ秒）を取得または設定します。RequestTimeout プロパティは、失効ステータスや OCSP サーバーなどのオンラインリソースにアクセスする際に、システムがネットワーク応答を待機できる最大時間を定義します。 |
| [setValidationMethod](#setValidationMethod-int-) | 証明書の検証に使用するメソッドを取得または設定します。 |
| [setValidationMode](#setValidationMode-int-) | PDF 文書のデジタル署名の検証モードを取得または設定します。ValidationMode プロパティは、検証プロセスの厳格さを決定します。 |

### ValidationOptions {#ValidationOptions--}
```
public ValidationOptions()
```

{@link ValidationOptions} クラスのインスタンスを作成します。

### getCheckCertificateChain {#getCheckCertificateChain--}
```
public final boolean getCheckCertificateChain()
```

検証プロセス中に証明書チェーンをチェックするかどうかを示す値を取得または設定します。プロパティが設定されている場合、証明書チェーンの存在がチェックされ、存在しない場合は検証結果が {@link ValidationStatus#Undefined} となり、これは Adobe Acrobat の動作に対応します。オンラインで失効ステータスのみを確認したい場合は、フィールドを {@code false} に設定してください。デフォルト値は {@code false} です。

**Returns:**
ブール値

### getRequestTimeout {#getRequestTimeout--}
```
public final int getRequestTimeout()
```

検証プロセス中のネットワーク関連操作のタイムアウト時間（ミリ秒）を取得または設定します。RequestTimeout プロパティは、失効ステータスや OCSP サーバーなどのオンラインリソースにアクセスする際に、システムがネットワーク応答を待機できる最大時間を定義します。

**Returns:**
int 値です。

### getValidationMethod {#getValidationMethod--}
```
public final int getValidationMethod()
```

証明書の検証に使用するメソッドを取得または設定します。

**Returns:**
ValidationMethod 要素

### getValidationMode {#getValidationMode--}
```
public final int getValidationMode()
```

PDF 文書のデジタル署名の検証モードを取得または設定します。ValidationMode プロパティは、検証プロセスの厳格さを決定します。

**Returns:**
ValidationMode 要素

### setCheckCertificateChain {#setCheckCertificateChain-boolean-}
```
public final void setCheckCertificateChain(boolean value)
```

検証プロセス中に証明書チェーンをチェックするかどうかを示す値を取得または設定します。プロパティが設定されている場合、証明書チェーンの存在がチェックされ、存在しない場合は検証結果が {@link ValidationStatus#Undefined} となり、これは Adobe Acrobat の動作に対応します。オンラインで失効ステータスのみを確認したい場合は、フィールドを {@code false} に設定してください。デフォルト値は {@code false} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRequestTimeout {#setRequestTimeout-int-}
```
public final void setRequestTimeout(int value)
```

検証プロセス中のネットワーク関連操作のタイムアウト時間（ミリ秒）を取得または設定します。RequestTimeout プロパティは、失効ステータスや OCSP サーバーなどのオンラインリソースにアクセスする際に、システムがネットワーク応答を待機できる最大時間を定義します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setValidationMethod {#setValidationMethod-int-}
```
public final void setValidationMethod(int value)
```

証明書の検証に使用するメソッドを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ValidationMethod 要素 |

### setValidationMode {#setValidationMode-int-}
```
public final void setValidationMode(int value)
```

PDF 文書のデジタル署名の検証モードを取得または設定します。ValidationMode プロパティは、検証プロセスの厳格さを決定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ValidationMode 要素 |
