---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "フォントをシステムフォントに置換するフォント置換戦略のクラスを表します。"
type: docs
weight: 110
url: /ja/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

フォントをシステムフォントに置換するフォント置換戦略のクラスを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | 新しい {@code SystemFontsSubstitution} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | デフォルトの置換フォントを取得または設定します。フォントは、他に有効な置換が見つからず、かつ元のフォントが対象置換カテゴリ（{@code FontCategories}）に属している場合に使用されます。 |
| [getFontCategories](#getFontCategories--) | システムフォントで置換すべき置換フォントカテゴリを取得または設定します。 |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | デフォルトの置換フォントを取得または設定します。フォントは、他に有効な置換が見つからず、かつ元のフォントが対象置換カテゴリ（{@code FontCategories}）に属している場合に使用されます。 |
| [setFontCategories](#setFontCategories-int-) | システムフォントで置換すべき置換フォントカテゴリを取得または設定します。 |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

新しい {@code SystemFontsSubstitution} クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fontCategories |  | システムフォントで置換する対象フォントカテゴリ |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

デフォルトの置換フォントを取得または設定します。フォントは、他に有効な置換が見つからず、かつ元のフォントが対象置換カテゴリ（{@code FontCategories}）に属している場合に使用されます。

**Returns:**
フォントオブジェクト

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

システムフォントで置換すべき置換フォントカテゴリを取得または設定します。

**Returns:**
SubstitutionFontCategories 要素 @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
デフォルトの置換フォントを取得または設定します。フォントは、他に有効な置換が見つからず、かつ元のフォントが対象置換カテゴリ（{@code FontCategories}）に属している場合に使用されます。

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

システムフォントで置換すべき置換フォントカテゴリを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | SubstitutionFontCategories 要素 @see SubstitutionFontCategories |
