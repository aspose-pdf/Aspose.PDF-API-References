---
title: "Signature"
linktitle: "Signature"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF ドキュメント内の署名オブジェクトを表す抽象クラスです。署名は署名オブジェクトの値を持つフィールドで、最後のものは検証に使用されるデータを含みます。"
type: docs
weight: 4490
url: /ja/java/com.aspose.pdf/signature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Signature

```
public abstract class Signature extends Object
```

PDF 文書内の署名オブジェクトを表す抽象クラスです。署名は署名オブジェクトの値を持つフィールドであり、後者は文書の有効性を検証するために使用されるデータを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Signature](#Signature--) | {@code Signature} クラスの新しいインスタンスを初期化します。 |
| [Signature](#Signature-java.io.InputStream-java.lang.String-) | {@code Signature} クラスの新しいインスタンスを初期化します。 |
| [Signature](#Signature-java.lang.String-java.lang.String-) | {@code Signature} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [close](#close--) | 必要に応じて一時ストリームを閉じるデストラクタ。 |
| [getAuthority](#getAuthority--) | 文書に署名する人物または権限者の名前。 |
| [getByteRange](#getByteRange--) | ダイジェスト計算のための正確なバイト範囲を示す整数のペア（開始バイトオフセット、バイト長）の配列を取得します。 |
| [getContactInfo](#getContactInfo--) | 署名者が提供した情報を取得し、受信者が署名者に連絡して署名を検証できるようにします（例：電話番号）。 |
| [getCustomAppearance](#getCustomAppearance--) | カスタム外観を取得/設定します。 |
| [getCustomSign](#getCustomSign--) | ドキュメントをカスタムハッシュおよび署名するためのデリゲート（ベータ）。 {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [getCustomSignHash](#getCustomSignHash--) | ドキュメントハッシュをカスタム署名するためのデリゲート（ベータ）。 {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [getDate](#getDate--) | 署名時刻を取得します。 |
| [getDefaultSignatureLength](#getDefaultSignatureLength--) | 署名データのデフォルト長さ（バイト単位）を取得または設定します。これは署名の長さの推定値です。{@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) パラメータが設定されている場合、{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) を使用した署名に使用されます。デフォルト値は 3000 です。 |
| [getImageInternal](#getImageInternal--) | 画像ストリームを取得します。内部使用のみです。 |
| [getLocation](#getLocation--) | 署名の CPU ホスト名または物理的な場所を取得します。 |
| [getOcspSettings](#getOcspSettings--) | OCSP 設定を取得/設定します。 |
| [getReason](#getReason--) | 署名の理由を取得します（例： (I agreed!, Pip B.)）。 |
| [getSignatureAlgorithmInfo](#getSignatureAlgorithmInfo--) | 署名で使用されている署名アルゴリズムに関する情報を取得します。 |
| [getSignatureReferences](#getSignatureReferences--) | 署名参照を取得 |
| [getTimestampSettings](#getTimestampSettings--) | タイムスタンプ設定を取得します。 |
| [getUseLtv](#getUseLtv--) | LTV 検証フラグを取得/設定します。 |
| [isAvoidEstimatingSignatureLength](#isAvoidEstimatingSignatureLength--) | 署名の長さの推定を回避するかどうかを示すオプションを取得および設定します。署名ドキュメントの前に署名長さを推定しません。{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) および {@code ExternalSignature} を使用した署名に使用されます。{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) が {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}) より長い署名を返す場合、{@code SignatureLengthMismatchException} がスローされます。デフォルト値は {@code false} です。 |
| [isShowProperties](#isShowProperties--) | 署名プロパティの表示/非表示を強制します。ShowProperties が true の場合、署名フィールドは外観の事前定義フォーマット（表現文字列）を持ちます： ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- ここで {X} は X の値のプレースホルダーです。また、署名に画像がある場合、これらの文字列は画像上に配置されます。ShowProperties のデフォルトは true です。 |
| [setAuthority](#setAuthority-java.lang.String-) | ドキュメントに署名する人物または機関の名前を設定します。 |
| [setAvoidEstimatingSignatureLength](#setAvoidEstimatingSignatureLength-boolean-) | 署名の長さの推定を回避するかどうかを示すオプションを取得および設定します。署名ドキュメントの前に署名長さを推定しません。{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) および {@code ExternalSignature} を使用した署名に使用されます。{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) が {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}) より長い署名を返す場合、{@code SignatureLengthMismatchException} がスローされます。デフォルト値は {@code false} です。 |
| [setContactInfo](#setContactInfo-java.lang.String-) | 署名者が提供した情報を設定し、受信者が署名者に連絡して署名を検証できるようにします（例：電話番号）。 |
| [setCustomAppearance](#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-) | カスタム外観を取得/設定します。 |
| [setCustomSign](#setCustomSign-com.aspose.pdf.CustomSign-) | ドキュメントをカスタムハッシュおよび署名するためのデリゲート（ベータ）。 {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.} |
| [setCustomSignHash](#setCustomSignHash-com.aspose.pdf.SignHash-) | ドキュメントハッシュをカスタム署名するためのデリゲート（ベータ）。 {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.} |
| [setDate](#setDate-java.util.Date-) | 署名時刻を設定します。 |
| [setDefaultSignatureLength](#setDefaultSignatureLength-int-) | 署名データのデフォルト長さ（バイト単位）を取得または設定します。これは署名の長さの推定値です。{@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) パラメータが設定されている場合、{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) を使用した署名に使用されます。デフォルト値は 3000 です。 |
| [setImage](#setImage-java.io.InputStream-) | 画像ストリームを設定します。 |
| [setImageInternal](#setImageInternal-com.aspose.ms.System.IO.Stream-) |  |
| [setLocation](#setLocation-java.lang.String-) | 署名の CPU ホスト名または物理的な場所を設定します。 |
| [setOcspSettings](#setOcspSettings-com.aspose.pdf.OcspSettings-) | OCSP 設定を取得/設定します。 |
| [setReason](#setReason-java.lang.String-) | 署名の理由を設定します（例： (I agreed!, Pip B.)）。 |
| [setShowProperties](#setShowProperties-boolean-) | 署名プロパティの表示/非表示を強制します。ShowProperties が true の場合、署名フィールドは外観の事前定義フォーマット（表現文字列）を持ちます： ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- ここで {X} は X の値のプレースホルダーです。また、署名に画像がある場合、これらの文字列は画像上に配置されます。ShowProperties のデフォルトは true です。 |
| [setTimestampSettings](#setTimestampSettings-com.aspose.pdf.TimestampSettings-) | タイムスタンプ設定を設定します。 |
| [setUseLtv](#setUseLtv-boolean-) | LTV 検証フラグを取得/設定します。 |
| [verify](#verify--) | この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true、そうでない場合は false を返します。 |
| [verify](#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true、そうでない場合は false を返します。 |
| [verify](#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true、そうでない場合は false を返します。 |

### Signature {#Signature--}
```
public Signature()
```

{@code Signature} クラスの新しいインスタンスを初期化します。

### Signature {#Signature-java.io.InputStream-java.lang.String-}
{@code Signature} クラスの新しいインスタンスを初期化します。

### Signature {#Signature-java.lang.String-java.lang.String-}
{@code Signature} クラスの新しいインスタンスを初期化します。

### close {#close--}
```
public void close()
```

必要に応じて一時ストリームを閉じるデストラクタ。

### getAuthority {#getAuthority--}
```
public final String getAuthority()
```

文書に署名する人物または権限者の名前。

**Returns:**
文字列値

### getByteRange {#getByteRange--}
```
public int[] getByteRange()
```

ダイジェスト計算のための正確なバイト範囲を示す整数のペア（開始バイトオフセット、バイト長）の配列を取得します。

**Returns:**
int 値の配列

### getContactInfo {#getContactInfo--}
```
public String getContactInfo()
```

署名者が提供した情報を取得し、受信者が署名者に連絡して署名を検証できるようにします（例：電話番号）。

**Returns:**
文字列値

### getCustomAppearance {#getCustomAppearance--}
```
public final SignatureCustomAppearance getCustomAppearance()
```

カスタム外観を取得/設定します。

**Returns:**
SignatureCustomAppearance インスタンス

### getCustomSign {#getCustomSign--}
```
public final CustomSign getCustomSign()
```

ドキュメントをカスタムハッシュおよび署名するためのデリゲート（ベータ）。 {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash インスタンス

### getCustomSignHash {#getCustomSignHash--}
```
public final SignHash getCustomSignHash()
```

ドキュメントハッシュをカスタム署名するためのデリゲート（ベータ）。 {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

**Returns:**
SignHash インスタンス

### getDate {#getDate--}
```
public Date getDate()
```

署名時刻を取得します。

**Returns:**
日付の値

### getDefaultSignatureLength {#getDefaultSignatureLength--}
```
public final int getDefaultSignatureLength()
```

署名データのデフォルト長さ（バイト単位）を取得または設定します。これは署名の長さの推定値です。{@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) パラメータが設定されている場合、{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) を使用した署名に使用されます。デフォルト値は 3000 です。

**Returns:**
int 値です。

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.IO.Stream getImageInternal()
```

画像ストリームを取得します。内部使用のみです。

**Returns:**
ストリーム オブジェクト

### getLocation {#getLocation--}
```
public String getLocation()
```

署名の CPU ホスト名または物理的な場所を取得します。

**Returns:**
文字列値

### getOcspSettings {#getOcspSettings--}
```
public OcspSettings getOcspSettings()
```

OCSP 設定を取得/設定します。

**Returns:**
OcspSettings インスタンス

### getReason {#getReason--}
```
public String getReason()
```

署名の理由を取得します（例： (I agreed!, Pip B.)）。

**Returns:**
文字列値

### getSignatureAlgorithmInfo {#getSignatureAlgorithmInfo--}
```
public final com.aspose.pdf.engine.security.SignatureAlgorithmInfo getSignatureAlgorithmInfo()
```

署名で使用されている署名アルゴリズムに関する情報を取得します。

**Returns:**
{ SignatureAlgorithmInfo} のインスタンスで、署名アルゴリズムに関する詳細が含まれています。

### getSignatureReferences {#getSignatureReferences--}
```
public List <com.aspose.pdf.engine.security.impl.signatures.SignatureReference> getSignatureReferences()
```

署名参照を取得

**Returns:**
{@code java.util.List<SignatureReference> object}

### getTimestampSettings {#getTimestampSettings--}
```
public TimestampSettings getTimestampSettings()
```

タイムスタンプ設定を取得します。

**Returns:**
TimestampSettings

### getUseLtv {#getUseLtv--}
```
public final boolean getUseLtv()
```

LTV 検証フラグを取得/設定します。

**Returns:**
ブール値

### isAvoidEstimatingSignatureLength {#isAvoidEstimatingSignatureLength--}
```
public final boolean isAvoidEstimatingSignatureLength()
```

署名の長さの推定を回避するかどうかを示すオプションを取得および設定します。署名ドキュメントの前に署名長さを推定しません。{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) および {@code ExternalSignature} を使用した署名に使用されます。{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) が {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}) より長い署名を返す場合、{@code SignatureLengthMismatchException} がスローされます。デフォルト値は {@code false} です。

**Returns:**
ブール値

### isShowProperties {#isShowProperties--}
```
public boolean isShowProperties()
```

署名プロパティの表示/非表示を強制します。ShowProperties が true の場合、署名フィールドは外観の事前定義フォーマット（表現文字列）を持ちます： ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- ここで {X} は X の値のプレースホルダーです。また、署名に画像がある場合、これらの文字列は画像上に配置されます。ShowProperties のデフォルトは true です。

**Returns:**
ブール値

### setAuthority {#setAuthority-java.lang.String-}
ドキュメントに署名する人物または機関の名前を設定します。

### setAvoidEstimatingSignatureLength {#setAvoidEstimatingSignatureLength-boolean-}
```
public final void setAvoidEstimatingSignatureLength(boolean value)
```

署名の長さの推定を回避するかどうかを示すオプションを取得および設定します。署名ドキュメントの前に署名長さを推定しません。{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) および {@code ExternalSignature} を使用した署名に使用されます。{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) が {@code DefaultSignatureLength}({@code #getDefaultSignatureLength}/{@code #setDefaultSignatureLength(int)}) より長い署名を返す場合、{@code SignatureLengthMismatchException} がスローされます。デフォルト値は {@code false} です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setContactInfo {#setContactInfo-java.lang.String-}
署名者が提供した情報を設定し、受信者が署名者に連絡して署名を検証できるようにします（例：電話番号）。

### setCustomAppearance {#setCustomAppearance-com.aspose.pdf.SignatureCustomAppearance-}
カスタム外観を取得/設定します。

### setCustomSign {#setCustomSign-com.aspose.pdf.CustomSign-}
ドキュメントをカスタムハッシュおよび署名するためのデリゲート（ベータ）。 {@code The algorithm with which you hash and sign the document in the delegate must match the type of the certificate's private key.}

### setCustomSignHash {#setCustomSignHash-com.aspose.pdf.SignHash-}
ドキュメントハッシュをカスタム署名するためのデリゲート（ベータ）。 {@code The algorithm with which you sign the hash in the delegate must match the type of the certificate's private key.}

### setDate {#setDate-java.util.Date-}
署名時刻を設定します。

### setDefaultSignatureLength {#setDefaultSignatureLength-int-}
```
public final void setDefaultSignatureLength(int value)
```

署名データのデフォルト長さ（バイト単位）を取得または設定します。これは署名の長さの推定値です。{@code AvoidEstimatingSignatureLength}({@code #getAvoidEstimatingSignatureLength}/{@code #setAvoidEstimatingSignatureLength(boolean)}) パラメータが設定されている場合、{@code CustomSignHash}({@code #getCustomSignHash}/{@code #setCustomSignHash(SignHash)}) を使用した署名に使用されます。デフォルト値は 3000 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setImage {#setImage-java.io.InputStream-}
画像ストリームを設定します。

### setImageInternal {#setImageInternal-com.aspose.ms.System.IO.Stream-}


### setLocation {#setLocation-java.lang.String-}
署名の CPU ホスト名または物理的な場所を設定します。

### setOcspSettings {#setOcspSettings-com.aspose.pdf.OcspSettings-}
OCSP 設定を取得/設定します。

### setReason {#setReason-java.lang.String-}
署名の理由を設定します（例： (I agreed!, Pip B.)）。

### setShowProperties {#setShowProperties-boolean-}
```
public void setShowProperties(boolean value)
```

署名プロパティの表示/非表示を強制します。ShowProperties が true の場合、署名フィールドは外観の事前定義フォーマット（表現文字列）を持ちます： ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- ここで {X} は X の値のプレースホルダーです。また、署名に画像がある場合、これらの文字列は画像上に配置されます。ShowProperties のデフォルトは true です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setTimestampSettings {#setTimestampSettings-com.aspose.pdf.TimestampSettings-}
タイムスタンプ設定を設定します。

### setUseLtv {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```

LTV 検証フラグを取得/設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### verify {#verify--}
```
public boolean verify()
```

この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true、そうでない場合は false を返します。

**Returns:**
ドキュメントが有効な場合は true。

### verify {#verify-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true、そうでない場合は false を返します。

**Returns:**
ドキュメントが有効な場合は true。

### verify {#verify-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
この署名に関してドキュメントを検証し、ドキュメントが有効な場合は true、そうでない場合は false を返します。

**Returns:**
ドキュメントが有効な場合は true。
