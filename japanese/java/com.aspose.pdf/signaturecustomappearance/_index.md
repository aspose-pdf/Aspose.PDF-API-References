---
title: "SignatureCustomAppearance"
linktitle: "SignatureCustomAppearance"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "署名のカスタム外観オブジェクトを表す抽象クラスです。"
type: docs
weight: 4500
url: /ja/java/com.aspose.pdf/signaturecustomappearance/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SignatureCustomAppearance

```
public final class SignatureCustomAppearance extends Object
```

署名のカスタム外観オブジェクトを表す抽象クラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SignatureCustomAppearance](#SignatureCustomAppearance--) | {@link SignatureCustomAppearance} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBackgroundColor](#getBackgroundColor--) | 背景色を取得/設定します。デフォルト値: Transparent. |
| [getContactInfoLabel](#getContactInfoLabel--) | 連絡先情報ラベルを取得/設定します。デフォルト値: "Contact". |
| [getCulture](#getCulture--) | カルチャ情報の値を取得/設定します。デフォルト値: InvariantCulture. |
| [getDateSignedAtLabel](#getDateSignedAtLabel--) | 署名日ラベルを取得/設定します。デフォルト値: "Date". |
| [getDateTimeFormat](#getDateTimeFormat--) | 日時形式を取得/設定します。デフォルト値: "yyyy.MM.dd HH:mm:ss". |
| [getDateTimeLocalFormat](#getDateTimeLocalFormat--) | ローカル日時形式を取得/設定します。デフォルト値: "yyyy.MM.dd HH:mm:ss zzz". |
| [getDigitalSignedLabel](#getDigitalSignedLabel--) | デジタル署名ラベルを取得/設定します。デフォルト値: "Digitally signed by". |
| [getDigitalSubjectFormat](#getDigitalSubjectFormat--) | Subject文字列内の要素順序の形式を取得/設定します。結果例: C=UK, CN=Org, O=Organization または CN=Org, C=UK, O=Organization または O=Organization |
| [getFontFamilyName](#getFontFamilyName--) | フォントファミリ名を取得/設定します。ドキュメントに存在する必要があります。デフォルト値: Arial. |
| [getFontSize](#getFontSize--) | フォントサイズを取得/設定します。デフォルト値: 10. |
| [getForegroundColor](#getForegroundColor--) | 前景色（テキストの色）を取得/設定します。デフォルト値: Blue. |
| [getLocationLabel](#getLocationLabel--) | 場所ラベルを取得/設定します。デフォルト値: "Location". |
| [getReasonLabel](#getReasonLabel--) | 理由ラベルを取得/設定します。デフォルト値: "Reason". |
| [getRotation](#getRotation--) | 署名の回転を取得または設定します。 |
| [isForegroundImage](#isForegroundImage--) | 署名外観の画像が前景画像として描画されるかどうかを示す値を取得または設定します。デフォルト値: false. |
| [isShowContactInfo](#isShowContactInfo--) | 連絡先情報の表示可否を取得/設定します。デフォルト値: true. |
| [isShowLocation](#isShowLocation--) | 場所の表示可否を取得/設定します。デフォルト値: true. |
| [isShowReason](#isShowReason--) | 理由の表示可否を取得/設定します。デフォルト値: true. |
| [isUseDigitalSubjectFormat](#isUseDigitalSubjectFormat--) |  {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])} ) の使用状態を取得/設定します。 |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | 背景色を取得/設定します。デフォルト値: Transparent. |
| [setContactInfoLabel](#setContactInfoLabel-java.lang.String-) | 連絡先情報ラベルを取得/設定します。デフォルト値: "Contact". |
| [setCulture](#setCulture-java.util.Locale-) | カルチャ情報の値を取得/設定します。 |
| [setDateSignedAtLabel](#setDateSignedAtLabel-java.lang.String-) | 署名日ラベルを取得/設定します。デフォルト値: "Date". |
| [setDateTimeFormat](#setDateTimeFormat-java.lang.String-) | 日時形式を取得/設定します。デフォルト値: "yyyy.MM.dd HH:mm:ss". |
| [setDateTimeLocalFormat](#setDateTimeLocalFormat-java.lang.String-) | ローカル日時形式を取得/設定します。デフォルト値: "yyyy.MM.dd HH:mm:ss zzz". |
| [setDigitalSignedLabel](#setDigitalSignedLabel-java.lang.String-) | デジタル署名ラベルを取得/設定します。デフォルト値: "Digitally signed by". |
| [setDigitalSubjectFormat](#setDigitalSubjectFormat-int:A-) | Subject文字列内の要素順序の形式を取得/設定します。結果例: C=UK, CN=Org, O=Organization または CN=Org, C=UK, O=Organization または O=Organization |
| [setFontFamilyName](#setFontFamilyName-java.lang.String-) | フォントファミリ名を取得/設定します。ドキュメントに存在する必要があります。デフォルト値: Arial. |
| [setFontSize](#setFontSize-double-) | フォントサイズを取得/設定します。デフォルト値: 10. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | 前景色（テキストの色）を取得/設定します。デフォルト値: Blue. |
| [setForegroundImage](#setForegroundImage-boolean-) | 署名外観の画像が前景画像として描画されるかどうかを示す値を取得または設定します。デフォルト値: false. |
| [setLocationLabel](#setLocationLabel-java.lang.String-) | 場所ラベルを取得/設定します。デフォルト値: "Location". |
| [setReasonLabel](#setReasonLabel-java.lang.String-) | 理由ラベルを取得/設定します。デフォルト値: "Reason". |
| [setRotation](#setRotation-com.aspose.pdf.Rotation-) | 署名の回転を取得または設定します。 |
| [setShowContactInfo](#setShowContactInfo-boolean-) | 連絡先情報の表示可否を取得/設定します。デフォルト値: true. |
| [setShowLocation](#setShowLocation-boolean-) | 場所の表示可否を取得/設定します。デフォルト値: true. |
| [setShowReason](#setShowReason-boolean-) | 理由の表示可否を取得/設定します。デフォルト値: true. |
| [setUseDigitalSubjectFormat](#setUseDigitalSubjectFormat-boolean-) |  {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])} ) の使用状態を取得/設定します。 |

### SignatureCustomAppearance {#SignatureCustomAppearance--}
```
public SignatureCustomAppearance()
```

{@link SignatureCustomAppearance} クラスの新しいインスタンスを初期化します。

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

背景色を取得/設定します。デフォルト値: Transparent.

**Returns:**
com.aspose.pdf.Color インスタンス

### getContactInfoLabel {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```

連絡先情報ラベルを取得/設定します。デフォルト値: "Contact".

**Returns:**
文字列値

### getCulture {#getCulture--}
```
public final Locale getCulture()
```

カルチャ情報の値を取得/設定します。デフォルト値: InvariantCulture.

**Returns:**
ロケール値

### getDateSignedAtLabel {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```

署名日ラベルを取得/設定します。デフォルト値: "Date".

**Returns:**
文字列値

### getDateTimeFormat {#getDateTimeFormat--}
```
public final String getDateTimeFormat()
```

日時形式を取得/設定します。デフォルト値: "yyyy.MM.dd HH:mm:ss".

**Returns:**
文字列値

### getDateTimeLocalFormat {#getDateTimeLocalFormat--}
```
public final String getDateTimeLocalFormat()
```

ローカル日時形式を取得/設定します。デフォルト値: "yyyy.MM.dd HH:mm:ss zzz".

**Returns:**
文字列値

### getDigitalSignedLabel {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```

デジタル署名ラベルを取得/設定します。デフォルト値: "Digitally signed by".

**Returns:**
文字列値

### getDigitalSubjectFormat {#getDigitalSubjectFormat--}
```
public final int[] getDigitalSubjectFormat()
```

Subject文字列内の要素順序の形式を取得/設定します。結果例: C=UK, CN=Org, O=Organization または CN=Org, C=UK, O=Organization または O=Organization

**Returns:**
int 配列 @see SubjectNameElements

### getFontFamilyName {#getFontFamilyName--}
```
public final String getFontFamilyName()
```

フォントファミリ名を取得/設定します。ドキュメントに存在する必要があります。デフォルト値: Arial.

**Returns:**
文字列値

### getFontSize {#getFontSize--}
```
public final double getFontSize()
```

フォントサイズを取得/設定します。デフォルト値: 10.

**Returns:**
double 値

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

前景色（テキストの色）を取得/設定します。デフォルト値: Blue.

**Returns:**
com.aspose.pdf.Color インスタンス

### getLocationLabel {#getLocationLabel--}
```
public final String getLocationLabel()
```

場所ラベルを取得/設定します。デフォルト値: "Location".

**Returns:**
文字列値

### getReasonLabel {#getReasonLabel--}
```
public final String getReasonLabel()
```

理由ラベルを取得/設定します。デフォルト値: "Reason".

**Returns:**
文字列値

### getRotation {#getRotation--}
```
public final Rotation getRotation()
```

署名の回転を取得または設定します。

**Returns:**
回転要素

### isForegroundImage {#isForegroundImage--}
```
public final boolean isForegroundImage()
```

署名外観の画像が前景画像として描画されるかどうかを示す値を取得または設定します。デフォルト値: false.

**Returns:**
ブール値

### isShowContactInfo {#isShowContactInfo--}
```
public final boolean isShowContactInfo()
```

連絡先情報の表示可否を取得/設定します。デフォルト値: true.

**Returns:**
ブール値

### isShowLocation {#isShowLocation--}
```
public final boolean isShowLocation()
```

場所の表示可否を取得/設定します。デフォルト値: true.

**Returns:**
ブール値

### isShowReason {#isShowReason--}
```
public final boolean isShowReason()
```

理由の表示可否を取得/設定します。デフォルト値: true.

**Returns:**
ブール値

### isUseDigitalSubjectFormat {#isUseDigitalSubjectFormat--}
```
public final boolean isUseDigitalSubjectFormat()
```

 {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])} ) の使用状態を取得/設定します。

**Returns:**
ブール値

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
背景色を取得/設定します。デフォルト値: Transparent.

### setContactInfoLabel {#setContactInfoLabel-java.lang.String-}
連絡先情報ラベルを取得/設定します。デフォルト値: "Contact".

### setCulture {#setCulture-java.util.Locale-}
カルチャ情報の値を取得/設定します。

### setDateSignedAtLabel {#setDateSignedAtLabel-java.lang.String-}
署名日ラベルを取得/設定します。デフォルト値: "Date".

### setDateTimeFormat {#setDateTimeFormat-java.lang.String-}
日時形式を取得/設定します。デフォルト値: "yyyy.MM.dd HH:mm:ss".

### setDateTimeLocalFormat {#setDateTimeLocalFormat-java.lang.String-}
ローカル日時形式を取得/設定します。デフォルト値: "yyyy.MM.dd HH:mm:ss zzz".

### setDigitalSignedLabel {#setDigitalSignedLabel-java.lang.String-}
デジタル署名ラベルを取得/設定します。デフォルト値: "Digitally signed by".

### setDigitalSubjectFormat {#setDigitalSubjectFormat-int:A-}
```
public final void setDigitalSubjectFormat(int[] value)
```

Subject文字列内の要素順序の形式を取得/設定します。結果例: C=UK, CN=Org, O=Organization または CN=Org, C=UK, O=Organization または O=Organization

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 配列 @see SubjectNameElements |

### setFontFamilyName {#setFontFamilyName-java.lang.String-}
フォントファミリ名を取得/設定します。ドキュメントに存在する必要があります。デフォルト値: Arial.

### setFontSize {#setFontSize-double-}
```
public final void setFontSize(double value)
```

フォントサイズを取得/設定します。デフォルト値: 10.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
前景色（テキストの色）を取得/設定します。デフォルト値: Blue.

### setForegroundImage {#setForegroundImage-boolean-}
```
public final void setForegroundImage(boolean value)
```

署名外観の画像が前景画像として描画されるかどうかを示す値を取得または設定します。デフォルト値: false.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLocationLabel {#setLocationLabel-java.lang.String-}
場所ラベルを取得/設定します。デフォルト値: "Location".

### setReasonLabel {#setReasonLabel-java.lang.String-}
理由ラベルを取得/設定します。デフォルト値: "Reason".

### setRotation {#setRotation-com.aspose.pdf.Rotation-}
署名の回転を取得または設定します。

### setShowContactInfo {#setShowContactInfo-boolean-}
```
public final void setShowContactInfo(boolean value)
```

連絡先情報の表示可否を取得/設定します。デフォルト値: true.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setShowLocation {#setShowLocation-boolean-}
```
public final void setShowLocation(boolean value)
```

場所の表示可否を取得/設定します。デフォルト値: true.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setShowReason {#setShowReason-boolean-}
```
public final void setShowReason(boolean value)
```

理由の表示可否を取得/設定します。デフォルト値: true.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseDigitalSubjectFormat {#setUseDigitalSubjectFormat-boolean-}
```
public final void setUseDigitalSubjectFormat(boolean value)
```

 {@code DigitalSubjectFormat}({@link #getDigitalSubjectFormat}/{@link #setDigitalSubjectFormat(int[])} ) の使用状態を取得/設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |
