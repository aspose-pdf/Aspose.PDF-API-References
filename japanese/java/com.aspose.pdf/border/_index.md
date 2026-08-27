---
title: "Border"
linktitle: "Border"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "アノテーション境界の特性を表すクラス。"
type: docs
weight: 340
url: /ja/java/com.aspose.pdf/border/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Border

```
public final class Border extends Object
```

アノテーション境界の特性を表すクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Border](#Border-com.aspose.pdf.Annotation-) | ボーダーオブジェクトのコンストラクタです。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDash](#getDash--) | ダッシュパターンを取得します。 |
| [getEffect](#getEffect--) | ボーダー効果を取得します。 {@code BorderEffect} |
| [getEffectIntensity](#getEffectIntensity--) | 効果の強度を取得します。有効な値の範囲は [0..2] です。 |
| [getHCornerRadius](#getHCornerRadius--) | まだサポートされていません。水平コーナー半径を取得します。 |
| [getStyle](#getStyle--) | ボーダースタイルを取得します。 {@code BorderStyle} |
| [getVCornerRadius](#getVCornerRadius--) | 垂直コーナー半径を取得します。 |
| [getWidth](#getWidth--) | ボーダー幅を取得します。 |
| [setDash](#setDash-com.aspose.pdf.Dash-) | ダッシュパターンを設定します。 |
| [setEffect](#setEffect-com.aspose.pdf.BorderEffect-) | ボーダー効果を設定します。 {@code BorderEffect} |
| [setEffectIntensity](#setEffectIntensity-int-) | 効果の強度を設定します。 値の有効範囲は [0..2] です。 |
| [setHCornerRadius](#setHCornerRadius-double-) | 水平コーナー半径を設定します。 |
| [setStyle](#setStyle-com.aspose.pdf.BorderStyle-) | ボーダースタイルを設定します。 {@code BorderStyle} |
| [setWidth](#setWidth-int-) | ボーダー幅を設定します。 |

### Border {#Border-com.aspose.pdf.Annotation-}
ボーダーオブジェクトのコンストラクタです。

### getDash {#getDash--}
```
public Dash getDash()
```

ダッシュパターンを取得します。

**Returns:**
ダッシュオブジェクト

### getEffect {#getEffect--}
```
public BorderEffect getEffect()
```

ボーダー効果を取得します。 {@code BorderEffect}

**Returns:**
BorderEffect 要素

### getEffectIntensity {#getEffectIntensity--}
```
public int getEffectIntensity()
```

効果の強度を取得します。有効な値の範囲は [0..2] です。

**Returns:**
int 値です。

### getHCornerRadius {#getHCornerRadius--}
```
public final double getHCornerRadius()
```

まだサポートされていません。水平コーナー半径を取得します。

**Returns:**
double 値

### getStyle {#getStyle--}
```
public BorderStyle getStyle()
```

ボーダースタイルを取得します。 {@code BorderStyle}

**Returns:**
BorderStyle 要素 @see BorderStyle

### getVCornerRadius {#getVCornerRadius--}
```
public final double getVCornerRadius()
```

垂直コーナー半径を取得します。

**Returns:**
垂直コーナー半径。

### getWidth {#getWidth--}
```
public int getWidth()
```

ボーダー幅を取得します。

**Returns:**
int 値です。

### setDash {#setDash-com.aspose.pdf.Dash-}
ダッシュパターンを設定します。

### setEffect {#setEffect-com.aspose.pdf.BorderEffect-}
ボーダー効果を設定します。 {@code BorderEffect}

### setEffectIntensity {#setEffectIntensity-int-}
```
public void setEffectIntensity(int value)
```

効果の強度を設定します。 値の有効範囲は [0..2] です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setHCornerRadius {#setHCornerRadius-double-}
```
public final void setHCornerRadius(double value)
```

水平コーナー半径を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |

### setStyle {#setStyle-com.aspose.pdf.BorderStyle-}
ボーダースタイルを設定します。 {@code BorderStyle}

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

ボーダー幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |
